---
title: MRD — Digitalização do Backoffice Geolab
aliases:
  - MRD Geolab
tags:
  - senai-indtech
  - geolab
  - mrd
  - backoffice
  - transformacao-digital
status: ativo
empresa: Geolab Indústria Farmacêutica S/A
erp: SAP
ultima_atualizacao: 2026-08-15
---

# MRD — Digitalização do Backoffice Geolab

> [!info] Status e fontes
> Este é o MRD canônico atualmente adotado no projeto. Foi consolidado a partir do [[fontes/mrd-utilizado-original|MRD recebido]], do [[fontes/transcricao-luciano-almeida|depoimento de Luciano Almeida]] da informação complementar de que o ERP da Geolab é o **SAP** e dos seis artefatos consolidados em [[consolidacao-etapa-01|Consolidação da Etapa 01]].
>
> O documento descreve requisitos de mercado. Ele não define ainda produto, MVP ou arquitetura.

## 1. Resumo executivo

A Geolab é uma indústria farmacêutica com equipamentos modernos e forte presença de tecnologia na produção de medicamentos. Em contraste, alguns setores do backoffice ainda utilizam bastante papel e mantêm formas tradicionais de trabalho.

A digitalização enfrenta duas barreiras centrais:

1. **viabilidade econômica:** novas soluções podem envolver aquisição, licenciamento, implantação e operação, exigindo retorno claro para donos e diretores;
2. **adoção:** parte do público interno resiste à mudança, de modo que benefício percebido, participação das áreas e transformação cultural são essenciais.

O ERP utilizado é o **SAP**. Antes de adquirir ou desenvolver uma nova plataforma, a iniciativa deve avaliar as capacidades, módulos, integrações e licenças já disponíveis no ambiente corporativo.

A oportunidade é digitalizar progressivamente um processo relevante do backoffice, demonstrando ganho operacional, adoção real e retorno econômico antes de expandir. A etapa mais recente introduziu uma visão integrada de até sete áreas e dois contextos distintos — fluxo operacional e desenvolvimento de genérico — que devem permanecer separados até validação.

## 2. Problema

### Problema central

Como digitalizar processos do backoffice da Geolab de forma economicamente justificável e efetivamente adotada, aproveitando o ambiente SAP e outras ferramentas existentes sem criar novas ilhas de informação?

### Dimensões

| Dimensão | Problema observado |
|---|---|
| Econômica | Custos tecnológicos adicionais precisam apresentar retorno atraente |
| Operacional | Alguns setores ainda utilizam papel e formas tradicionais de trabalho |
| Cultural | Existe resistência interna a mudanças de processo e tecnologia |
| Adoção | A solução precisa funcionar no cotidiano e gerar benefício percebido |
| Tecnológica | É necessário avaliar SAP, ferramentas existentes, automação e novas soluções |
| Executiva | Diretoria e donos precisam compreender custo, benefício e risco |

## 3. Evidências, inferências e lacunas

| Informação | Estado |
|---|---|
| Luciano Almeida é gestor de tecnologia da Geolab | Fato declarado |
| A produção utiliza equipamentos modernos e tecnologia embarcada | Fato declarado |
| Alguns setores ainda utilizam bastante papel | Fato declarado |
| Existe resistência de públicos internos à mudança | Fato declarado |
| Aquisição, licenciamento e implantação dificultam novos investimentos | Fato declarado |
| A solução deve ser atraente para áreas operacionais e diretoria | Fato declarado |
| O ERP utilizado é o SAP | Fato informado pelo usuário |
| A produção é “altamente automatizada” | Não confirmado; corrigido para tecnologicamente equipada |
| Financeiro, fiscal, compras e RH são as áreas prioritárias | Não confirmado |
| Microsoft 365 está licenciado ou subutilizado | Não confirmado; a fala menciona Microsoft Office |
| Qualidade e regulatório participam do processo escolhido | Hipótese plausível, a confirmar |
| TI possui capacidade interna de integração | Não confirmado |
| A produção deve servir como prova social | Estratégia possível, não requisito confirmado |
| Ciclo de 8–14 meses e custo de R$ 1,0–1,4 milhão | Reportado em artefato da etapa; origem primária e definição do ciclo pendentes |
| Genérico com ciclo de 48 meses e custo de R$ 10 milhões | Reportado em artefato da etapa; composição pendente de validação |
| Redução de cerca de 30% no tempo e 11% no custo | Estimativa matematicamente coerente, ainda não medida |
| Sete áreas compartilham um fluxo único | Visão de solução, não processo validado |

## 4. Público e stakeholders

### Confirmados

| Stakeholder | Necessidade |
|---|---|
| Gestor e equipe de tecnologia | Apoiar ideias das áreas e viabilizar soluções aplicáveis |
| Clientes internos | Obter benefício prático com baixa fricção na mudança |
| Áreas operacionais e de backoffice | Tornar processos mais ágeis, eficientes e eficazes |
| Diretoria e donos | Aprovar investimentos sustentados por retorno e custo compatíveis |

### Prováveis, sujeitos a confirmação

- gestor responsável pelo processo escolhido;
- auditoria interna;
- qualidade e regulatório;
- segurança da informação;
- equipe responsável pelo SAP;
- jurídico ou proteção de dados, conforme o processo.

## 5. Necessidades de mercado

- reduzir dependência de papel;
- reduzir espera, esforço manual, retrabalho e controles paralelos;
- tornar o benefício visível ao usuário interno;
- demonstrar retorno em linguagem executiva;
- implantar de forma progressiva, sem ruptura desnecessária;
- aproveitar o SAP e ferramentas existentes quando forem adequados;
- evitar duplicação de dados, regras e governança;
- permitir mensuração antes e depois;
- considerar treinamento, cocriação e acompanhamento da adoção;
- manter rastreabilidade proporcional ao processo e às obrigações aplicáveis;
- evitar redigitação e perda de contexto nas passagens entre áreas;
- separar fabricação, desenvolvimento de produto e análise regulatória.

## 6. Requisitos de mercado

| ID | Requisito | Prioridade | Base |
|---|---|---:|---|
| MR-01 | Demonstrar retorno com métricas verificáveis | Essencial | Entrevista |
| MR-02 | Resolver um processo específico e relevante do backoffice | Essencial | Escopo e estratégia incremental |
| MR-03 | Oferecer benefício perceptível e baixa fricção ao usuário interno | Essencial | Entrevista |
| MR-04 | Avaliar capacidades disponíveis no SAP antes de adicionar plataforma | Essencial | SAP confirmado + controle de custo |
| MR-05 | Permitir implantação progressiva sem interromper a operação | Essencial | Redução de risco |
| MR-06 | Evitar ilhas de dados e integrar-se ao ambiente corporativo quando necessário | Alta | Boa governança; integração a validar |
| MR-07 | Incluir cocriação, treinamento e acompanhamento de adoção | Alta | Barreira cultural confirmada |
| MR-08 | Produzir métricas operacionais, econômicas e de adoção | Alta | Necessidade de justificar investimento |
| MR-09 | Manter rastreabilidade e controles adequados ao processo escolhido | Alta | Contexto industrial; requisitos específicos pendentes |
| MR-10 | Minimizar custo total de propriedade e dependência desnecessária | Alta | Barreira econômica confirmada |
| MR-11 | Ser operável no cotidiano com dependência de TI compatível com a governança | Média | Hipótese a validar com a área |
| MR-12 | Usar IA apenas onde superar alternativa determinística em valor mensurável | Média | Princípio do projeto, não exigência da entrevista |
| MR-13 | Preservar contexto e evitar redigitação nas passagens entre áreas | Alta | Necessidade proposta na Etapa 01; ocorrência real a medir |

## 7. Alternativas a comparar

| Alternativa | Quando considerar | Risco principal |
|---|---|---|
| Otimizar o processo sem novo software | Gargalo causado por regra ou sequência inadequada | Ganho limitado se faltar capacidade digital |
| Usar função ou módulo já disponível no SAP | Capacidade já licenciada e adequada | Complexidade ou experiência insuficiente |
| Estender ou integrar o SAP | Registro corporativo precisa permanecer no ERP | Custo, prazo e acesso à integração |
| Usar ferramenta corporativa já contratada | Workflow simples e integração controlável | Criar controle paralelo |
| Automação leve ou RPA | Processo estável, repetitivo e baseado em regras | Fragilidade diante de exceções e mudanças |
| Aplicação específica | Necessidade clara não atendida pelas alternativas | Nova manutenção e custo total |
| IA aplicada | Há classificação, extração, resumo ou decisão assistida mensurável | Complexidade, erro e governança sem retorno |

## 8. Métricas de sucesso candidatas

Os valores-alvo dependem do processo selecionado e ainda não devem ser inventados.

### Operacionais

- tempo total e tempo de espera;
- horas mensais de trabalho manual;
- taxa de retrabalho;
- etapas e aprovações manuais;
- volume de papel;
- custo por ocorrência;
- percentual de casos concluídos no fluxo digital.

### Econômicas

- custo de implantação;
- custo recorrente;
- custo total de propriedade;
- economia ou custo evitado;
- ROI;
- prazo de payback;
- custo de expansão para outros processos.

### Adoção

- percentual de usuários ativos;
- percentual de transações realizadas no novo fluxo;
- taxa de conclusão sem suporte;
- tempo de treinamento;
- satisfação do usuário;
- retorno ao processo manual;
- exceções realizadas fora do sistema.

## 9. Riscos

| Risco | Tratamento inicial |
|---|---|
| Solução implantada e não adotada | Cocriação, teste de usabilidade e acompanhamento |
| ROI baseado em estimativa frágil | Baseline rastreável e premissas explícitas |
| Escopo amplo demais | Um processo e um fluxo principal no MVP |
| Duplicação de capacidade do SAP | Inventário de módulos, APIs e licenças |
| Dependência de integração indisponível | Protótipo desacoplado com contrato de integração |
| IA sem necessidade | Comparação obrigatória com alternativa determinística |
| Requisito regulatório presumido | Validar obrigações do processo antes da arquitetura |
| Uso de dados sensíveis no hackathon | Dados sintéticos e controles mínimos |
| Falta de disponibilidade dos usuários | Validação curta com representante identificado |
| Mistura entre ciclo operacional e desenvolvimento de genérico | Manter baselines e objetivos separados |
| Estimativas apresentadas como resultado | Identificar fonte, fórmula e grau de confiança |
| Escopo de sete áreas no MVP | Usar a cadeia completa somente como visão futura |

## 10. Premissas de trabalho

As premissas abaixo orientam a descoberta, mas não são fatos confirmados:

- um processo bem escolhido pode funcionar como prova de valor;
- ganhos visíveis podem reduzir resistência;
- capacidades já contratadas podem melhorar o ROI;
- a integração com SAP pode ser necessária, dependendo do processo;
- uma implantação incremental tende a reduzir risco.

## 11. Perguntas em aberto

### Processo

- O que exatamente representa o ciclo reportado de 8 a 14 meses?
- Quais etapas pertencem à rotina de produto registrado e quais ao desenvolvimento?
- Quais processos ainda usam papel?
- Quais apresentam maior volume, demora, retrabalho ou risco?
- Quem solicita, executa, aprova e audita?
- Qual deles é demonstrável no hackathon?

### SAP e ambiente tecnológico

- A versão é SAP ECC, SAP S/4HANA ou outra?
- Quais módulos estão implantados?
- Quais APIs, integrações e extensões estão liberadas?
- Existem SAP Fiori, SAP BTP ou ferramenta corporativa de workflow?
- Quais licenças já estão disponíveis?
- Há ambiente de homologação ou somente simulação?

### Economia

- Qual é a fonte primária dos números de tempo e custo recebidos?
- Como se distribuem os R$ 10 milhões do genérico? O resumo e a tabela divergem.
- Existe baseline de custo e tempo?
- Qual investimento e payback são aceitáveis?
- Qual custo pode ser evitado?
- Quem aprova o piloto e a expansão?

### Adoção

- Quem resiste e por quê?
- Houve tentativa anterior? Qual resultado?
- Quem pode cocriar e validar o protótipo?
- Quais dispositivos e canais fazem parte da rotina?

### Segurança, qualidade e regulação

- Que dados o processo manipula?
- Quais requisitos de auditoria, qualidade, LGPD ou regulação se aplicam?
- Qual política de retenção e controle de acesso é necessária?

### Hackathon

- Quais são os critérios e pesos da avaliação?
- Qual é o prazo e o formato de entrega?
- É exigido protótipo funcional?
- Haverá acesso a representantes da Geolab?

## 12. Insumos consolidados da etapa atual

A [[consolidacao-etapa-01|Consolidação da Etapa 01]] passa a complementar este MRD com:

- visão conceitual de compras até produção;
- Business Model Canvas interno;
- quatro candidatos de MVP;
- estimativas de ganhos classificadas como não validadas;
- separação entre fluxo operacional e desenvolvimento de genérico;
- riscos de escopo, evidência e consistência financeira.

A cadeia completa de sete áreas é uma **visão de expansão**. O produto mínimo continua limitado a uma passagem de bastão validada.

## 13. Gate de validação do MRD

O MRD estará validado para iniciar o PRD quando houver:

- processo prioritário selecionado;
- usuário, gestor e aprovador identificados;
- dor específica confirmada;
- fluxo atual minimamente mapeado;
- baseline ou estimativa rastreável;
- critério de sucesso definido;
- capacidades relevantes do SAP investigadas;
- restrições do hackathon registradas.

## 14. Próxima decisão

Selecionar e comparar ao menos três processos candidatos com base em:

- dor real;
- volume e frequência;
- impacto econômico;
- facilidade de adoção;
- demonstrabilidade;
- integração com SAP;
- disponibilidade de dados;
- diferencial para o hackathon.

## Relacionamentos

- [[desafios|Desafio Geolab]]
- [[consolidacao-etapa-01|Consolidação da Etapa 01]]
- [[fontes/transcricao-luciano-almeida|Transcrição de Luciano Almeida]]
- [[fontes/mrd-utilizado-original|MRD recebido]]
- [[mrd-preliminar|MRD preliminar substituído]]
- [[decisoes/README|Decisões]]
- [[../tasks/README|Backlog]]
