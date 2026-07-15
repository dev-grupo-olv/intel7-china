# site/ · Landing page institucional INTEL7 China

Página HTML standalone premium para uso institucional (apresentação Abrasel · convite iFood · circulação restrita stakeholders). Zero build · zero backend · funciona offline.

**Target de hospedagem:** `matheusbusson.com.br/missaochinafood`

## O que é

Single-page application (SPA) de apresentação editorial luxo institucional. Design dark cinemático · tipografia Fraunces (display serif variable) + Inter Tight (body) + JetBrains Mono (technical eyebrows) · palette Brasil (verde-esmeralda) + China (vermelho-cinabar) + dourado imperial · GSAP scroll-triggered · custom cursor + grain overlay + diagonal grid.

## Seções (numeradas editorial)

1. **00 · Hero** · abertura editorial · marquee cidades chinesas
2. **01 · Manifesto (Why)** · Golden Circle · 3 verdades convergentes
3. **02 · Diagnóstico** · 4 números-choque (10× · 80k · 60% · 7mi)
4. **03 · Tese · 3 pilares** · IA e Tech · Supply Chain · Equipamento e Maquinário
5. **04 · Roteiro · 5 blocos** · Pequim · Xangai · Yiwu · Cantão · HK com detalhamento
6. **05 · Núcleo** · Matheus · Felipe · Thiago
7. **06 · Apoio institucional** · Abrasel + iFood
8. **07 · Modelo comercial** · R$ 29.900 · 12x R$ 2.999 · 4 tipos de cadeira
9. **08 · BMC** · Business Model Canvas 9 blocos
10. **09 · SWOT** · Strengths · Weaknesses · Opportunities · Threats
11. **10 · PESTLE** · 6 forças macro externas
12. **11 · Flywheel** · SVG animado + 7 elementos
13. **12 · Concorrentes** · matriz vs 7 competidores
14. **13 · Mindmap** · estrutura visual
15. **14 · Timing** · cronograma julho → novembro 2026
16. **Footer institucional**

## Como abrir localmente

```bash
open ~/projects/intel7-china/site/index.html
```

Funciona em qualquer navegador (Safari · Chrome · Firefox · Edge). Zero dependência de servidor.

## Como apresentar em reunião presencial

- Abrir em fullscreen (`Cmd + Ctrl + F` no Safari · `F11` no Chrome)
- Rolar com espaço · seta · trackpad
- Cada seção tem entrada cinematográfica via GSAP quando entra no viewport
- Modo escuro do sistema para conforto visual

## Como exportar como PDF

1. Abrir `index.html` no navegador
2. `Cmd + P` (Mac) ou `Ctrl + P` (Windows)
3. Destino: **Salvar como PDF**
4. Layout: Retrato · Margens: Padrão
5. CSS `@media print` já ajusta: fundo branco · nav escondida

## Deploy · 3 opções (mais rápido primeiro)

### Opção A · Deploy no domínio `matheusbusson.com.br/missaochinafood` (recomendado)

**Se site atual do Matheus é WordPress:**
1. Acessar cPanel/hospedagem do domínio matheusbusson.com.br
2. Ir em File Manager · pasta `public_html/`
3. Criar pasta `missaochinafood/`
4. Upload `index.html` para dentro dessa pasta
5. Acessar `matheusbusson.com.br/missaochinafood/` (funciona imediatamente)

**Se site atual é Wix/Squarespace/Webflow:**
- Wix/Squarespace não permitem upload HTML custom em subpath
- Solução: usar subdomínio (ex: `missaochinafood.matheusbusson.com.br`) via Cloudflare Pages
- OU: hospedar em Vercel e adicionar CNAME `missaochinafood → intel7-china.vercel.app` (5 min)

### Opção B · Deploy Vercel + domain customizado (2 minutos)

```bash
cd ~/projects/intel7-china/site
npx vercel --prod
# Após deploy · pegar URL fornecida (ex: intel7-china-xyz.vercel.app)
# No Vercel dashboard · adicionar custom domain missaochinafood.matheusbusson.com.br
# No DNS matheusbusson.com.br · criar CNAME apontando para cname.vercel-dns.com
```

### Opção C · Deploy Netlify Drop (30 segundos · sem CLI)

1. Acessar https://app.netlify.com/drop
2. Arrastar pasta `~/projects/intel7-china/site/` inteira
3. Netlify gera URL do tipo `nome-aleatorio.netlify.app`
4. Ir em Site settings → Domain management → adicionar `missaochinafood.matheusbusson.com.br`
5. No DNS · criar CNAME conforme instrução Netlify

## Checklist pré-envio a stakeholder externo

- [ ] Testar em Safari + Chrome desktop
- [ ] Testar em iPhone (mobile responsive)
- [ ] Salvar como PDF e revisar paginação
- [ ] Confirmar todos dados (preços · datas · núcleo) refletem versão final travada 2026-07-15
- [ ] Deploy em URL público matheusbusson.com.br/missaochinafood/ ativa
- [ ] Testar preview em WhatsApp e LinkedIn (compartilhar link)

## Como atualizar

Este site é 100% self-contained (1 único arquivo `index.html` com tudo inline). Para atualizar:

1. Editar `index.html` diretamente (Cmd+F para procurar seção · edit inline)
2. Re-upload no servidor (subir novamente arquivo · substitui versão anterior)
3. Não há build step · CDN cache pode demorar até 15min para propagar

## Tech stack

- HTML5 semântico
- TailwindCSS via CDN
- GSAP 3.12 + ScrollTrigger via CDN
- Google Fonts (Fraunces + Inter Tight + JetBrains Mono)
- Zero dependência de servidor
- Zero build step
- Custom cursor · grain overlay · marquee texto perpétuo · SVG flywheel animado
- Print styles (`@media print`) para export PDF limpo

## Design system

- **Base:** dark cinemático (`#0a0d0a` · `#050705` void)
- **Cores acento:**
  - Bone (`#f5f2ea`) · off-white osso
  - Verde-Brasil (`#00a352`) · esmeralda saturado
  - Cinabar-China (`#b91c1c`) · vermelho profundo
  - Gold imperial (`#c9a961`) · dourado editorial premium (não amarelado)
- **Tipografia:**
  - Display: **Fraunces** variable (opsz + WONK · serif com garras · italic dramático)
  - Body: **Inter Tight** (mais condensed que Inter puro)
  - Mono: **JetBrains Mono** (technical eyebrows)
- **Motion:** GSAP + ScrollTrigger · fade-in stagger · number counters · parallax subtle · marquee perpétuo · flywheel rotation
- **Efeitos:** custom cursor + grain overlay SVG + diagonal grid + underline drawing SVG

## Referências de design (não visíveis · influências)

- Wall Street Journal editorial
- The New York Times Magazine spreads
- Apollo Magazine (art history editorial)
- Loro Piana / Zegna sites (luxo institucional)
- Rick Owens architecture

## Changelog

**v1.0 · 2026-07-15** · Página institucional criada com research completo + roteiro final travado + preço R$ 29.900 · design editorial luxo dark cinemático · GSAP scroll-triggered · pronta para deploy em matheusbusson.com.br/missaochinafood.
