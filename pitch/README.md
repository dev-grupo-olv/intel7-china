# Pitch cinematográfico · movimento Brasil ↔ China

Página HTML standalone (~2600 linhas · 143 KB · GSAP + ScrollTrigger + Tailwind CDN · zero build) usada como material principal de venda + apresentação institucional do movimento Brasil-China. Renderiza em qualquer navegador · exporta pra PDF via `Cmd+P` · pronto pra hospedar em Vercel/GitHub Pages/Netlify.

**Origem:** movido em 2026-07-15 de `~/projects/brasil-china-abrasel/index.html` (última edição 2026-07-03 · versão 1.0). Estava desconectado do repo canônico China · consolidado aqui.

## Como usar

### Abrir localmente
```bash
open ~/projects/intel7-china/pitch/index.html
```
Ou arrastar `index.html` pra qualquer navegador (Safari · Chrome · Firefox · Edge). Não precisa de servidor.

### Apresentação presencial
- Abrir em fullscreen (`Cmd + Ctrl + F` no Safari · `F11` no Chrome)
- Rolar com espaço · seta · trackpad
- Cada seção tem entrada cinematográfica via GSAP quando entra no viewport
- Recomendado: modo escuro do sistema para conforto visual

### Enviar por email como PDF
1. Abrir `index.html` no navegador
2. `Cmd + P` (Mac) ou `Ctrl + P` (Windows)
3. Destino: **Salvar como PDF**
4. Layout: Retrato · Margens: Padrão
5. O CSS `@media print` já ajusta: fundo branco · nav escondida · elementos otimizados

### Compartilhar como link
Opções pra hospedar (todas gratuitas):
- **GitHub Pages** · subir a subpasta `pitch/` como repositório público · ativar Pages
- **Vercel** · `vercel --prod` no diretório (zero config · dá URL em 30s)
- **Netlify Drop** · arrastar a pasta em netlify.com/drop
- **Cloudflare Pages** · conectar repo

## Estrutura interna do HTML

Seções (por âncora `id=`):
- `#hero` · abertura cinematográfica
- `#manifesto` · quem escreve · por que agora
- `#diagnostico` · 4 números-chave (10x · 80k · 60% · 7 mi)
- `#versus` · Ver produto vs Fechar acordo
- `#mercado` · SAM R$ 30 bi · captura R$ 280 mi · comparáveis
- `#visao` · 3 pilares (Tech Import · Industry Deal · Market Intelligence)
- `#agenda` · dia-a-dia missão outubro 2026 (5-6 cidades)
- `#fluxo` · missão auto-financiada · cadeiras pagas · ROI 2027-2028
- `#movimento` · Abrasel SP/RJ/Campinas/Nacional · marketplaces · timing
- `#time` · Matheus · Felipe · Thiago (bio Felipe em `[EDITAR]`)
- `#traction` · Rob Food (nome antigo · corrigir pra NewCo/Rob Food) · Abrasel · Ghost Lab 7
- `#moat` · 5 diferenciais defensáveis
- Fechamento · CTA + contato

## Pendências no HTML (a sanitizar antes de circular externamente)

**Críticas:**
- `[EDITAR]` na bio de Felipe (seção Time · card do meio) · fechar antes de qualquer envio
- Grafia "Felipe Vechi" → sanitizar pra "Felipe Vecchi" (grafia oficial · dois C's)
- Referência "Rob Food" (seção Traction) → corrigir pra "NewCo (pós-fusão Oliver's + Rob Food)"

**Números `[fonte: validar]` no diagnóstico:**
- 10x (penetração marketplace F&B)
- 80k+ (ghost kitchens China)
- 60% (automação Tier 1)
- 7 mi (empregos F&B Brasil · fonte Abrasel Panorama)

Validar antes de compartilhar com stakeholder que faça due diligence.

**Contato:**
- Email atual: `matheus.oliveira.portella@gmail.com` (seção CTA)
- WhatsApp: link `wa.me/` sem número · colocar número real
- Se criar email institucional (ex: `contato@intel7china.com.br`), trocar em 2 lugares (CTA + footer)

**Logos institucionais:**
Dropar imagens em `pitch/assets/logos/`:
- Abrasel SP · RJ · Campinas · Nacional
- iFood · Rappi · 99Food · Uber Eats
- Depois adicionar em seções específicas (opcional · marquee de texto já resolve como MVP)

**Imagem de preview (OG):**
Criar `pitch/assets/og-cover.jpg` (1200×630px) · aparece quando link é compartilhado em WhatsApp · LinkedIn · Telegram. Meta tag já aponta pro path certo.

## Design system

- **Base** · dark cinemático (`#08080a`)
- **Cores** · verde-Brasil `#00a352` · amarelo-Brasil `#ffcc29` · vermelho-China `#e63946` · dourado executivo `#d4a574`
- **Tipografia** · Playfair Display (headline editorial) + Inter (corpo) + JetBrains Mono (eyebrow/mono)
- **Grid** · Tailwind CDN (max-width 7xl · padding lateral 6)
- **Animações** · GSAP + ScrollTrigger (fade + slide + escala)
- **Grão** · overlay SVG noise sutil

## Tech stack (zero build)

- HTML5 semântico
- TailwindCSS via CDN
- GSAP 3.12 + ScrollTrigger via CDN
- Google Fonts (Playfair Display + Inter + JetBrains Mono)
- Zero dependência de servidor
- Zero build step
- Portátil · um arquivo HTML resolve

## Roadmap opcional (v2)

Se após primeiras reuniões (Abrasel RJ · Campinas · iFood) fizer sentido evoluir:
- Versão inglês (para investor deck internacional)
- Versão mandarim simplificado (para contrapartes chinesas)
- Substituir placeholders `[fonte: validar]` por fontes confirmadas
- Adicionar seção "Depoimentos" após primeiros endossos
- Vídeo de 60s no hero (Matheus + Felipe + Thiago falando)
- Formulário de contato server-side (Vercel Functions)
- Analytics (Plausible/Umami · sem cookies · LGPD-friendly)
- Logo real do movimento (identidade visual dedicada)

## Checklist pré-envio

Antes de compartilhar com qualquer stakeholder externo:

- [ ] Substituir `[EDITAR]` na bio Felipe
- [ ] Sanitizar "Felipe Vechi" → "Felipe Vecchi"
- [ ] Sanitizar "Rob Food" → "NewCo (Oliver's + Rob Food)"
- [ ] Validar ou remover placeholders `[fonte: validar]`
- [ ] Confirmar contato email/WhatsApp real
- [ ] Testar em Safari + Chrome (desktop)
- [ ] Testar em iPhone (mobile)
- [ ] Salvar como PDF e revisar paginação
- [ ] Gerar `assets/og-cover.jpg` real
- [ ] Escolher plataforma de hosting e publicar
- [ ] Testar preview em WhatsApp e LinkedIn (compartilhar link)

## Next steps

- [ ] **P0** · Sanitizar 3 typos críticos (Vecchi · NewCo · bio Felipe) · @matheus · 2026-07-20
- [ ] **P0** · Validar 4 números `[fonte: validar]` · @matheus + @thiago · 2026-08-15
- [ ] **P1** · Gerar `og-cover.jpg` real · @matheus · 2026-08-30
- [ ] **P1** · Escolher hosting e publicar (Vercel recomendado) · @thiago · 2026-08-30
- [ ] **P2** · Versão inglês (pós validação BR) · @matheus + @felipe · 2026-Q4

## Related

- `docs/contexto/movimento-brasil-china.md` · texto institucional que embasa o pitch
- `docs/nucleo/felipe-vecchi.md` · perfil canônico Felipe (bio pro pitch)
- `docs/nucleo/matheus-busson.md` · perfil Matheus
- `docs/nucleo/thiago-dam.md` · perfil Thiago
- `docs/players/institucional.md` · Abrasel + institucional referenciado no pitch

## Changelog

**v1.1 · 2026-07-15** · Movido de `~/projects/brasil-china-abrasel/index.html` pra `pitch/` neste repo (consolidação). Sem mudança no HTML · README atualizado com contexto novo (typos a sanitizar · Rob Food/NewCo · integração com repo canônico).
**v1.0 · 2026-07-03** · Versão original criada em `~/projects/brasil-china-abrasel/` como pitch page cinematográfica standalone.
