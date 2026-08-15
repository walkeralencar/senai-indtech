# SENAI IndTech

Projeto para organização, análise e desenvolvimento de solução para desafios industriais do SENAI IndTech.

## Abordagem

Este repositório adota uma abordagem **agentic-first**: contexto, decisões, tarefas e regras de execução ficam versionados junto ao código para permitir colaboração consistente entre pessoas e agentes de IA.

## Estrutura

```text
.
├── AGENTS.md                  # Regras operacionais para agentes
├── README.md                  # Visão geral do projeto
├── docs/
│   ├── index.md               # Índice navegável para Obsidian
│   ├── desafios.md            # Desafios industriais transcritos e estruturados
│   ├── mrd.md                 # MRD canônico
│   ├── consolidacao-etapa-01.md # Consolidação dos artefatos da etapa
│   ├── design-system.md        # Tokens, princípios e componentes
│   ├── design-system.html      # Referência visual navegável
│   ├── fontes/                # Evidências e insumos preservados
│   └── decisoes/
│       └── README.md          # Registro de decisões
├── prompts/
│   └── README.md              # Prompts reutilizáveis do projeto
└── tasks/
    └── README.md              # Backlog e tarefas executáveis por agentes
```

## Navegação

- [[docs/index|Índice do projeto]]
- [[docs/desafios|Desafios industriais]]
- [[docs/mrd|MRD canônico]]
- [[docs/consolidacao-etapa-01|Consolidação da Etapa 01]]
- [[docs/design-system|Design System]]
- [Referência visual HTML](docs/design-system.html)
- [[docs/decisoes/README|Decisões]]
- [[tasks/README|Backlog]]
- [[prompts/README|Prompts]]

## Princípio de trabalho

Antes de implementar qualquer solução:

1. Ler `AGENTS.md`.
2. Consultar `docs/` para obter o contexto atual.
3. Registrar hipóteses e decisões relevantes.
4. Trabalhar a partir de tarefas pequenas e verificáveis.
5. Atualizar a documentação quando o entendimento do problema evoluir.
