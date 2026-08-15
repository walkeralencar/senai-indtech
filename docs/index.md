---
title: SENAI IndTech - Índice
aliases:
  - Home
  - Índice
tags:
  - senai-indtech
  - moc
status: ativo
---

# SENAI IndTech

## Contexto principal

- [[desafios|Desafio Geolab]]
- [[mrd|MRD canônico]]
- [[consolidacao-etapa-01|Consolidação da Etapa 01]]
- [[hipoteses-de-ciclo|Hipóteses de Ciclo]]
- [[fontes/transcricao-luciano-almeida|Fonte — depoimento de Luciano Almeida]]
- [[fontes/mrd-utilizado-original|Fonte — MRD recebido]]
- [[decisoes/README|Registro de decisões]]
- [[../tasks/README|Backlog e tarefas]]
- [[../prompts/README|Prompts reutilizáveis]]

## Estado atual

O repositório está na fase de **descoberta e validação do problema**. O MRD utilizado pela equipe foi confrontado com a transcrição e consolidado no [[mrd|MRD canônico]].

O desafio da Geolab é digitalizar processos de backoffice conciliando:

1. eficiência operacional;
2. adoção pelo cliente interno;
3. retorno sobre investimento atrativo para a diretoria;
4. uso coerente do SAP e das ferramentas existentes.

Seis novos artefatos foram preservados e consolidados. Eles introduzem uma visão integrada de sete áreas, candidatos de MVP e estimativas de tempo e custo. O MRD permanece ativo, mas o PRD continua bloqueado: as duas hipóteses de ciclo já foram contextualizadas, mas falta confirmá-las com a Geolab, selecionar um processo específico, mapear o fluxo atual e confirmar o baseline.

## Fluxo de trabalho agentic-first

```mermaid
flowchart LR
    A[Contexto] --> B[MRD]
    B --> C[Validação]
    C --> D[PRD]
    D --> E[MVP]
    E --> F[FRD]
    F --> G[Execução]
```

## Próximas áreas a estruturar

- critérios e restrições do hackathon;
- confirmar com a Geolab as hipóteses de desenvolvimento de produto e produção de lote conhecido;
- confirmar números e fontes de tempo e custo;
- comparar e selecionar os processos candidatos;
- stakeholders e usuários do processo;
- baseline operacional e econômico;
- inventário do ambiente SAP;
- critérios de adoção;
- seleção e validação do MVP;
- riscos, segurança e conformidade;
- narrativa e demonstração.
