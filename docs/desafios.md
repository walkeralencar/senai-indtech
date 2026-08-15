---
title: Desafios Industriais
tags:
  - senai-indtech
  - desafio-industrial
  - geolab
  - transformacao-digital
  - backoffice
status: ativo
empresa: Geolab Indústria Farmacêutica S/A
area: Transformação digital
---

# Desafios Industriais

## Geolab Indústria Farmacêutica S/A

> [!info] Origem
> Transcrição estruturada a partir do material do desafio industrial fornecido pela Geolab.

### Tema

**Digitalização de processos no backoffice.**

### Descrição

A empresa deseja digitalizar os processos em que ainda existem muito papel e fluxo burocrático com uso de controles fora do ERP principal, que é muito bom.

A problemática está vinculada ao grupo diretor da empresa que gosta do papel e não tem uma diretriz clara e que dê autonomia com os devidos investimentos para poder evoluir com a digitalização e automação de vários processos que poderiam inclusive ter apoio de inteligência artificial em seu desenvolvimento.

Envolve um misto de área de TI subordinada à área financeira que visa redução de custo e cultura ausente de inovação nos setores.

### Área do desafio

**Transformação digital.**

### Qual o impacto atual desse problema para a indústria?

- Aumento de custos;
- perda de produtividade;
- retrabalho;
- desperdício;
- impacto ambiental;
- dificuldade de gestão;
- perda de competitividade.

### Caso exista alguma solução atual, descreva brevemente

A equipe de TI busca ativamente caminhos para mudar o entendimento dos setores e da alta gestão para poder avançar com a transformação e adoção de tecnologia.

### O que a indústria espera como possível solução?

- Adoção do ERP em processos que ainda estão rodando por fora;
- aplicação de automatização em processos repetitivos;
- adoção de aplicativos móveis para aprovações da alta gestão;
- melhoria operacional;
- aumento da eficiência.

---

## Leitura inicial do problema

> [!warning] Interpretação
> Esta seção é análise inicial e **não faz parte da transcrição original**.

O desafio aparenta combinar quatro dimensões principais:

1. **Processos:** fluxos burocráticos e dependência de papel.
2. **Integração:** controles paralelos ao ERP.
3. **Governança:** falta de diretriz clara, autonomia e investimento.
4. **Cultura:** resistência à digitalização e baixa maturidade de inovação.

### Linha de solução a investigar

```text
Documento/Papel
      ↓
Captura digital
      ↓
OCR / extração estruturada
      ↓
Workflow e regras
      ↓
Aprovação digital/mobile
      ↓
Integração com ERP
      ↓
Auditoria + indicadores
```

### Hipóteses iniciais

- O ERP existente deve permanecer como sistema principal de registro sempre que possível.
- Uma camada de workflow/orquestração pode reduzir processos paralelos sem exigir substituição do ERP.
- IA pode ser aplicada na classificação, extração, validação e roteamento de documentos/processos.
- O MVP deve demonstrar ganho mensurável em pelo menos um fluxo real de backoffice.

### Métricas candidatas

- tempo médio do processo;
- tempo médio de aprovação;
- quantidade de etapas manuais;
- número de controles externos ao ERP;
- volume de papel eliminado;
- taxa de retrabalho;
- custo operacional por processo;
- percentual de processos rastreáveis ponta a ponta.

## Relacionamentos

- [[index|Índice do projeto]]
- [[decisoes/README|Decisões]]
- [[../tasks/README|Backlog]]
- [[../prompts/README|Prompts]]
