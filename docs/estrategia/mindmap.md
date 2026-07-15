# Mindmap · estrutura visual do projeto INTEL7 China

**Framework Tony Buzan (1974).** Visualização hierárquica-associativa do projeto INTEL7 China. Documento canônico para orientação executiva rápida (30 segundos de leitura → entendimento macro).

Usado em: apresentação Abrasel · onboarding cadeiras · comunicação institucional · site LP.

## Mindmap canônico (formato Mermaid)

```mermaid
mindmap
  root((INTEL7 China))
    Why · Propósito
      Pioneiro do movimento BR-CN próxima década
      Empresário brasileiro precisa acesso in-situ à China
      Janela antes que Meituan/KeeTa consolide operação BR
      Missão comercial anual ancorada Canton Fair Fase 3 FOOD
    How · Método
      Curadoria institucional não turismo
      Acesso fabricantes + empresas referência
      Parcerias formais Abrasel + iFood
      Operação in-country parceiro local
      Núcleo com pé no chão setorial food
    What · Produto
      Missão outubro 2026
      14-15 dias · 5 cidades
      8-12 cadeiras
      R\$ 29.900 à vista ou 12x R\$ 2.999
      4 tipos cadeira: Co-Líder Corporativa Abrasel Setorial
    Roteiro · 5 blocos
      Pequim 3-4d
        Peking Duck abertura
        Cerimônia apresentação missão
        4Paradigm IA
        Meituan HQ Marketplace
        Restaurante brasileiro na China
      Xangai 3-4d
        Coffee break + patrocinador entrega valor
        Cruzeiro Rio Huangpu
        DJI + logística
        Meituan regional
        Alibaba + ghost kitchens
      Yiwu Mercadão 1d
        75000 lojas 5 distritos
        Supply Chain sourcing
        Tema paralelo entrega de valor
      Cantão Canton Fair 4d
        Fase 3 FOOD 31 out - 4 nov 2026
        Curadoria fabricantes pré-marcada
        4 dias completos
      Hong Kong opcional 1d
        Missão oficial termina no último dia Canton Fair
        Disney entretenimento
        Saída aérea barata
    Pilares técnicos · 3
      IA e Tech
        4Paradigm IA de decisão
        Meituan/KeeTa playbook Brasil
        Dark kitchens tech-first
        POS integrado
        Drone delivery
      Supply Chain
        Packaging + descartáveis biodegradáveis
        Insumos food service
        Uniforme + utensílios custom
        Consolidação container Yiwu → Santos
      Equipamento e Maquinário
        Fornos + fritadeiras + linhas produção
        Robôs wok
        POS hardware
        Certificação ANVISA + INMETRO
    Núcleo · 3 sócios
      Matheus Busson
        CEO Grupo OLV
        Diretor MKT NewCo
        8 marcas F&B ativas SP
        Curadoria comercial + institucional
      Felipe Vecchi
        Especialista Delivery
        257k IG verified
        12M views/mês orgânicos
        Founder Temakeria + Gyomō
        Sócio Comunidade INTEL7
      Thiago Dam
        CEO Ghost Lab 7
        Stack multiagente produção 4+ anos
        5 máquinas orquestradas
        Execução tech + operacional
    Apoio institucional
      Abrasel
        SP aprovada
        RJ + Campinas em curso
        Nacional alvo 2027
        Reunião Gabriel presidente 2026-07-16
        Precedente NRA Chicago 2026 800+ brasileiros
      iFood
        Inclinado positivamente
        Aliança Uber defensiva maio 2025
        Contatos Naty + Bruna via Felipe
        Fase 1 observador → Fase 2 endosso → Fase 3 cadeira Corporativa
      Câmaras BR-CN (Fase 2)
        CCIBC 1986 SP
        CCDIBC 2002
        CCCB lado chinês
        CEBC nível C-level (Fase 3)
      Parceiro local China
        Contato aberto viagem Matheus jan/fev 2026
        Tradução + logística in-country
    Timing · janela única 2026
      Canton Fair Fase 3 FOOD 31 out - 4 nov 2026 confirmado
      Brasil visa-free China 11 mai - 31 dez 2026
      Meituan/KeeTa Brasil desde 30/10/2025 com \$1bi
      Precedente NRA Chicago maio 2026 (Abrasel apoiou)
    Fases · roadmap
      Fase 1 · Missão 1 outubro 2026
        Validação modelo
        8-12 cadeiras
        Endosso Abrasel Regional + iFood observador
      Fase 2 · Ano 1 2027
        2 missões março + outubro
        30 cadeiras
        Abrasel Nacional endosso Q1 2027
        NewCo Corredor formalizada Q1 2027
        iFood Fase 2 endosso
      Fase 3 · Escala 2028+
        4 missões/ano
        80+ cadeiras acumuladas
        Programa Abrasel Nacional recorrente
        iFood Fase 3 cadeira Corporativa
        Delivery Hero global assinatura report
```

## Mindmap simplificado (para hero da LP)

```mermaid
mindmap
  root((INTEL7 China))
    WHY
      Pioneiro corredor BR-CN
      Antes que Meituan consolide BR
    WHAT
      Missão outubro 2026
      14-15 dias · 5 cidades
      R\$ 29.900 ou 12x R\$ 2.999
    HOW
      Curadoria não turismo
      Abrasel + iFood
      Núcleo food service real
    ROTEIRO
      Pequim
      Xangai
      Yiwu Mercadão
      Cantão Canton Fair Fase 3
      Hong Kong opcional
    PILARES
      IA e Tech
      Supply Chain
      Equipamento e Maquinário
    NÚCLEO
      Matheus Busson
      Felipe Vecchi
      Thiago Dam
```

## Visualização de dependências críticas (grafo)

```mermaid
graph TB
    A[Missão outubro 2026] --> B{Canton Fair Fase 3<br/>FOOD confirmada}
    A --> C{Endosso Abrasel<br/>Regional + Nacional}
    A --> D{iFood inclinado<br/>positivamente}
    A --> E{Visa-free BR-CN<br/>ativo até 31 dez 2026}
    A --> F{Parceiro local<br/>China contratado}

    B --> B1[Registro Canton Fair<br/>badge por cadeira]
    B --> B2[Hospedagem Pazhou<br/>URGENTE reservar]

    C --> C1[Reunião Gabriel<br/>2026-07-16]
    C --> C2[Aprovação RJ + Campinas<br/>até 2026-08-15]
    C --> C3[Head Missões<br/>Internacionais Abrasel]

    D --> D1[Convite iFood<br/>Naty/Bruna via Felipe]
    D --> D2[Cadeira Corporativa<br/>executivo iFood]

    F --> F1[Backup parceiro<br/>in-country stand-by]

    A --> G[Vendas cadeiras<br/>abertura setembro 2026]
    G --> G1[8-12 cadeiras<br/>deadline 15/set/2026]
    G --> G2[LP + pitch cinematográfico<br/>upload julho 2026]

    A --> H[Escritórios parceiros BR]
    H --> H1[ANVISA + INMETRO<br/>até 2026-09-30]
    H --> H2[Despachante Santos<br/>até 2026-10-30]
    H --> H3[Consultor tributário<br/>até 2026-10-30]
    H --> H4[Auditor QC in-country<br/>até 2026-09-15]

    classDef critical fill:#b91c1c,stroke:#7f1d1d,color:#fff
    classDef important fill:#c9a961,stroke:#8f6f2f,color:#000
    classDef standard fill:#0a0d0a,stroke:#00a352,color:#fff

    class B,C,D,E,F critical
    class B1,B2,C1,C2,D1,H1 important
```

## Visualização temporal (Gantt)

```mermaid
gantt
    title INTEL7 China · Roadmap operacional
    dateFormat  YYYY-MM-DD
    section Fase 1 · Missão 1
    Reunião Felipe × Gabriel Abrasel      :milestone, m1, 2026-07-16, 1d
    LP publicada                          :2026-07-16, 15d
    Aprovação Abrasel RJ + Campinas       :2026-07-31, 2026-08-15
    Convite iFood + patrocinador Xangai   :2026-07-31, 2026-08-30
    Reserva hospedagem Pazhou URGENTE     :crit, 2026-07-31, 5d
    Contratação escritórios parceiros BR  :2026-08-15, 2026-10-30
    Abertura vendas cadeiras              :2026-09-01, 2026-09-15
    Deadline vai ou não vai (8+)          :crit, milestone, 2026-09-15, 1d
    Registro Canton Fair badges           :2026-09-01, 15d
    Kit briefing entrega cadeiras         :2026-09-30, 15d
    MISSÃO OUTUBRO 2026                   :crit, active, 2026-10-24, 15d
    Canton Fair Fase 3 FOOD               :crit, 2026-10-31, 5d
    Relatório pós-missão                  :2026-11-07, 30d

    section Fase 2 · Ano 1
    Report co-Abrasel publicado           :2026-12-15, 30d
    Follow-up cases publicáveis           :2027-01-01, 90d
    Missão 2 · março 2027                 :2027-03-01, 20d
    Abrasel Nacional endosso Q1 2027      :milestone, 2027-03-31, 1d
    NewCo Corredor formalizada            :2027-01-01, 90d
    Missão 3 · outubro 2027               :2027-10-24, 20d

    section Fase 3 · Escala
    4 missões/ano                         :2028-01-01, 730d
    Programa Abrasel Nacional recorrente  :2028-01-01, 730d
    iFood Fase 3 cadeira Corporativa      :2028-01-01, 365d
```

## Como usar este mindmap

**Para reunião Abrasel (Felipe × Gabriel 2026-07-16):**
- Abrir mindmap simplificado (hero da LP) · projetar no iPad em fullscreen
- Explicar cada ramo em 30 segundos
- Retornar ao root após cada ramo (mantém foco no root INTEL7 China)

**Para onboarding cadeira:**
- Dia 2 da missão (cerimônia de abertura) · projetar mindmap canônico no telão hotel Pequim
- Mostrar como cada elemento se conecta a próxima cadeira
- Rotate por ramos conforme cadeira pede detalhes

**Para comunicação institucional:**
- Mindmap simplificado no rodapé do relatório co-Abrasel
- Mindmap canônico em anexo técnico
- Cada versão em PT + inglês (Fase 2)

**Para site LP:**
- Mindmap canônico como seção interativa (Mermaid.js live rendering)
- Cadeira clica no ramo · expande sub-nós
- Efeito wow: cadeira "descobre" a densidade do projeto sozinha

## Como manter atualizado

- **Trimestral** · atualizar mindmap canônico com progresso Fase 1 → Fase 2 → Fase 3
- **Post-missão** · adicionar cadeiras alumni como ramo separado (rede)
- **Post-endosso Abrasel Nacional** · elevar ramo Abrasel para nível root (sub-hub)
- **Post-NewCo Corredor** · elevar ramo Ecosistema para nível root (sub-hub)

## Related

- `docs/estrategia/why.md` · Golden Circle (alimenta root/Why)
- `docs/estrategia/business-model-canvas.md` · BMC (detalha What/Como/Recursos)
- `docs/estrategia/swot.md` · SWOT (alimenta Timing + Ameaças)
- `docs/estrategia/pestle.md` · PESTLE (alimenta Timing + Fatores macro)
- `docs/estrategia/flywheel.md` · Flywheel (alimenta Fases roadmap)
- `docs/estrategia/concorrentes.md` · concorrentes (contexto competitivo)

## Changelog

**v1.0 · 2026-07-15** · Mindmap canônico Mermaid + versão simplificada hero + grafo dependências críticas + Gantt temporal 2026-2028 · 4 formatos de visualização para uso em contextos diferentes (reunião · onboarding · comunicação · site).
