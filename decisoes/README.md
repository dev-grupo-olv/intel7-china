# Decisões · index de ADRs

Index de ADRs (Architecture Decision Records) formais do vertical INTEL7 China. ADR aqui documenta decisões estruturais · não decisões táticas do dia-a-dia (essas ficam em `reunioes/`).

## Quando abrir uma ADR

- Decisão de escopo (o que entra · o que sai do vertical)
- Decisão de estrutura (sub-sociedades · repos · governance)
- Decisão de kill/pivot (parar bloco · trocar modelo · rever pilar)
- Decisão institucional (formalizar parceria · encerrar relação · endosso público)
- Decisão financeira estrutural (ticket · política de cancelamento · fluxo de caixa)

## Formato ADR

Cada arquivo: `YYYY-MM-DD-{tema-curto}.md`. Estrutura mínima:

- **Título + data + status** (proposed · accepted · superseded · deprecated)
- **Contexto** · situação que motiva a decisão · qual problema
- **Opções consideradas** · alternativas com prós e contras
- **Decisão** · o que foi decidido · quem decidiu · quando
- **Consequências** · o que muda operacionalmente
- **Reversibilidade** · quão fácil é voltar atrás
- **Related** · ADRs adjacentes · docs afetadas

## ADRs registradas (2026-07-15)

Vazio no repo. ADR de adoção deste repo vai ser criada em paralelo no brain do Matheus (`~/brain/decisions/2026-07-15-intel7-china-repo-adocao.md`) e depois espelhada aqui.

## ADRs-alvo próximas (pipeline)

- **ADR-001 · Escopo vertical INTEL7 China** · consolidar movimento Brasil-China + produto de imersão num único vertical (já executado neste PR · formalizar em ADR retroativa)
- **ADR-002 · Sub-sociedade Thiago dentro do 50% Matheus INTEL7** · definir estrutura societária pós-Chicago (pendente)
- **ADR-003 · Papel Felipe no vertical China** · formalizar após reunião 2026-08-15
- **ADR-004 · Estrutura NewCo Corredor** · veículo formal (CNPJ · sócios · governance) · alvo 2027-Q1
- **ADR-005 · Contratação parceiro local China exclusivo vs backup** · definir se dependência é única (risk crítico) ou distribuída

## Related

- Brain do Matheus: `~/brain/decisions/` · ADRs OLV mais amplas
- `reunioes/README.md` · notas de reunião táticas
- `docs/nucleo/felipe-vecchi.md` · contexto que motiva ADR-003
- `docs/financeiro/projecao-3-anos.md` · contexto que motiva ADR-004

## Changelog

**v1.0 · 2026-07-15** · README esqueleto criado. Pipeline de 5 ADRs prioritárias mapeado.
