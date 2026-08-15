# AGENTS.md

## Objetivo

Orientar agentes de IA e colaboradores humanos no trabalho deste repositório.

## Fonte de verdade

A prioridade de contexto é:

1. `AGENTS.md`
2. `docs/index.md`
3. documentação específica em `docs/`
4. decisões registradas em `docs/decisoes/`
5. tarefas em `tasks/`
6. código e testes

Quando houver conflito, não invente uma resolução. Registre a divergência e proponha a atualização da fonte de verdade apropriada.

## Princípios agentic-first

- Trabalhar de forma incremental.
- Não presumir requisitos não documentados.
- Separar fatos, hipóteses e decisões.
- Preferir mudanças pequenas, reversíveis e verificáveis.
- Antes de alterar arquitetura, registrar a decisão em `docs/decisoes/`.
- Antes de iniciar implementação relevante, criar ou atualizar uma tarefa em `tasks/`.
- Atualizar documentação junto com mudanças de entendimento.
- Não apagar contexto histórico útil; consolidar e marcar conteúdo substituído quando necessário.

## Fluxo recomendado

1. Ler o contexto relevante.
2. Resumir o estado atual.
3. Identificar lacunas e dependências.
4. Propor próximo incremento.
5. Implementar somente o escopo necessário.
6. Validar resultado.
7. Atualizar documentação, decisão e tarefa associadas.

## Documentação

Os arquivos Markdown devem ser compatíveis com Obsidian sempre que fizer sentido:

- usar frontmatter YAML;
- usar links `[[wikilinks]]` para documentos internos;
- usar tags com parcimônia;
- evitar duplicação de informação;
- preferir documentos curtos e conectados.

## Convenções

### Fatos

Informações confirmadas devem ser registradas como fatos, com origem quando disponível.

### Hipóteses

Devem ser explicitamente marcadas como hipótese e não tratadas como requisito.

### Decisões

Decisões arquiteturais ou de produto devem registrar contexto, decisão, alternativas e consequências.

### Tarefas

Cada tarefa deve, quando aplicável, conter:

- objetivo;
- contexto;
- critérios de aceite;
- dependências;
- arquivos afetados;
- status.

## Segurança e qualidade

- Nunca adicionar segredos, tokens ou credenciais ao repositório.
- Não alterar comportamento existente sem verificar impacto.
- Quando houver código, criar validações/testes proporcionais ao risco.
- Para dados regulados ou sensíveis, registrar requisitos de segurança e conformidade antes da implementação.

## Estado atual

O projeto está na fase de **descoberta e validação do problema**. O [[docs/mrd|MRD canônico]] é a referência de requisitos de mercado e deve ser lido com a [[docs/consolidacao-etapa-01|Consolidação da Etapa 01]]. O PRD permanece bloqueado até a seleção de um processo, validação do baseline e investigação das capacidades do SAP.
