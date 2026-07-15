# Movimento Brasil ↔ China · Abrasel + Marketplaces

Camada **institucional** do movimento China · lastreada Abrasel (associação BR de bares e restaurantes) + marketplaces (iFood âncora · Rappi · 99Food · Uber Eats como stakeholders). Complementa o produto de imersão INTEL7 (ticket R$ 42k) com endosso institucional e distribuição.

**Núcleo humano:** Matheus Busson · Felipe Vecchi · Thiago Dam (mesmo núcleo do produto de imersão)

## O que é

Um movimento nomeado publicamente "Brasil ↔ China · Abrasel + Marketplaces" · pitch cinematográfico já materializado em `pitch/index.html` · MVP de circulação restrita a stakeholders institucionais.

## Por que existe

Sem endosso institucional (Abrasel · marketplaces · câmaras), o produto de imersão vira "mais uma empresa de viagem". Com endosso, o produto vira **infraestrutura de acesso** que a categoria adota. Diferença de posicionamento define diferença de preço e defensabilidade.

## Estrutura de 3 pilares (captura de valor)

Detalhes em `docs/pilares/`. Resumo:

1. **Tech Import** · stack de operação food service China → Brasil (automação cozinha · IA · ghost kitchens · POS integrado)
2. **Industry Deal** · fábricas chinesas + preço-fonte (equipamento · packaging · insumos)
3. **Market Intelligence** · inteligência operacional Meituan/Ele.me + fluxos cross-border TMall

## Roadmap em 2 fases

| Fase | Período | O que acontece | Status |
|---|---|---|---|
| **Fase 1** · Missão exploratória auto-financiada | Outubro 2026 · 12 dias · 5-6 cidades · 8-12 cadeiras pagas | Missão paga a viagem + gera intel + fecha primeiros deals | Planejamento ativo |
| **Fase 2** · Comercialização nacional | 2027+ | Programa de importação/consultoria/deal-flow em escala BR | Pré-operacional |

## Cidades da missão exploratória outubro 2026

Diferente do roteiro do produto de imersão INTEL7 (que é Pequim → Xangai → Yiwu → Cantão → Hong Kong), a missão institucional cobre:

- **Shenzhen** · operação · hardware · robótica
- **Xangai** · Meituan HQ · marketplace
- **Hangzhou** · Alibaba HQ · TMall Global
- **Pequim** · diplomacia · regulação · MOFCOM
- **Guangzhou / Cantão** · fechamento · regulação food safety · Canton Fair

Reconciliação com roteiro produto: **overlap parcial** (Xangai · Cantão · Pequim). Diferenças (Shenzhen · Hangzhou vs Yiwu · Hong Kong) refletem que o produto é mais atacado/varejo/turismo-de-negócios e o movimento institucional é mais tech/marketplace/regulação. Reconciliar quando fechar agenda final · owner Matheus + Thiago.

## Stakeholders institucionais mapeados

- **Abrasel SP** · aprovada (endosso ativo)
- **Abrasel RJ** · em curso
- **Abrasel Campinas** · em curso
- **Abrasel Nacional** · alvo pós-RJ+Campinas
- **iFood** · âncora marketplace BR
- **Rappi · 99Food · Uber Eats** · marketplaces secundários no radar

Detalhes em `docs/players/institucional.md` e `docs/players/marketplaces.md`.

## Cadeiras pagas · como a viagem se paga sozinha

Modelo de auto-financiamento da missão exploratória outubro 2026 (4 tipos de cadeira):

- **Co-Líder** · empresário que entra como par de curadoria (define agenda co-junto)
- **Corporativa** · empresa que paga cadeira pra executivo próprio
- **Abrasel** · cadeira institucional endossada pela associação
- **Setorial** · cadeira reservada a segmento específico (equipamento · packaging · tech)

Detalhes financeiros em `docs/missao-outubro-2026/cadeiras-missao.md`.

## ROI projetado corredor · 3 anos (2027 → 2029)

**SAM (Serviceable Addressable Market):** ~R$ 30 bilhões (fluxo importação equipamento + tech + insumos China → BR estimado). `[fonte: validar]`
**Captura em 3 anos:** R$ 280 milhões · 0,9% do SAM via NewCo Corredor + programa Abrasel
**Margem projetada:** 12-18% · comparável a trading houses agro-commodities (Cofco · Chinamex)

Referências institucionais de modelo (comparáveis):
- **CCAB / ANBA** · Câmara Árabe-Brasileira · modelo missão país-país + intel setorial
- **iFood · Delivery Hero** · modelo marketplace bilateral
- **Cofco · Chinamex** · trading houses BR-China agro (referência de margem e estrutura)

Detalhes em `docs/financeiro/projecao-3-anos.md`.

## Pitch cinematográfico já produzido

Página HTML standalone (2599 linhas · 143 KB · GSAP + ScrollTrigger + Tailwind CDN · zero build) disponível em `pitch/index.html`. Renderiza em qualquer navegador · exporta pra PDF via `Cmd+P` · pronto pra hospedar em Vercel/GitHub Pages/Netlify. Uso: apresentação presencial (fullscreen) · envio por email (PDF) · compartilhamento por link após hosting.

## Blockers conhecidos

- **Números do diagnóstico** · 4 estimativas com tag `[fonte: validar]` no pitch (10x penetração · 80k ghost kitchens · 60% automação · 7mi empregos). Validar antes de circular externamente.
- **Bio Felipe Vecchi no pitch** · versão antiga do pitch grafou "Felipe Vechi" (typo · grafia oficial é Vecchi com dois C's). Sanitizar quando editar HTML.
- **Contato institucional Abrasel RJ + Campinas** · Abrasel SP já aprovada, RJ e Campinas em curso. Acompanhar cadência.
- **Logos institucionais** · placeholders no HTML (`assets/logos/`) aguardando arquivos reais.

## Next steps

- [ ] **P0** · Sanitizar typo "Vechi" → "Vecchi" no pitch/index.html · @matheus · 2026-07-20
- [ ] **P0** · Confirmar aprovação Abrasel RJ · @matheus · 2026-08-15
- [ ] **P1** · Validar 4 números `[fonte: validar]` do diagnóstico com fontes primárias · @matheus + @thiago · 2026-08-15
- [ ] **P1** · Reconciliar cidades roteiro produto vs missão institucional (agenda única outubro) · @matheus + @thiago · 2026-09-01
- [ ] **P2** · Dropar logos institucionais em pitch/assets/logos/ · @matheus · 2026-08-30
- [ ] **P2** · Criar OG cover (1200×630) pra preview de link em WhatsApp/LinkedIn · @matheus · 2026-08-30

## Related

- `docs/contexto/por-que-china.md` · tese macro estratégica
- `docs/missao-outubro-2026/` · planejamento operacional da missão
- `docs/pilares/` · detalhamento dos 3 pilares
- `docs/players/institucional.md` · Abrasel · MOFCOM · CCAB
- `docs/players/marketplaces.md` · Meituan · Ele.me · iFood · Rappi
- `docs/financeiro/projecao-3-anos.md` · captura R$ 280 mi
- `pitch/` · página HTML cinematográfica pronta

## Changelog

**v1.0 · 2026-07-15** · Documento criado na consolidação do brasil-china-abrasel local pro repo intel7-china. Origem: `~/projects/brasil-china-abrasel/README.md` + `~/projects/brasil-china-abrasel/index.html` (2599 linhas · 143 KB · última edição 2026-07-03).
