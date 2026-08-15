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

> [!info] Fontes
> Síntese estruturada a partir do material original do desafio e do depoimento complementar de Luciano Almeida, gestor de tecnologia da Geolab.
>
> - [[fontes/transcricao-luciano-almeida|Depoimento de Luciano Almeida]]
> - [[fontes/mrd-utilizado-original|MRD utilizado recebido]]
> - [[mrd|MRD consolidado]]

### Tema

**Digitalização de processos no backoffice com retorno econômico e adoção interna.**

### Descrição consolidada

A Geolab já possui elevada maturidade tecnológica em sua operação industrial, com equipamentos modernos empregados na produção de medicamentos. A lacuna de digitalização não é generalizada: ela está concentrada em alguns setores e processos de backoffice que ainda dependem de papel, fluxos burocráticos ou formas tradicionais de trabalho.

A introdução de soluções de automação ou novos módulos de sistemas envolve custos de licenciamento, aquisição e implantação. Como a empresa já suporta outros custos tecnológicos, novos investimentos precisam apresentar retorno claro e atraente para donos e diretores.

Além da viabilidade econômica, existe um desafio de adoção. Parte do público interno resiste a mudanças e prefere manter a forma atual de trabalho. Portanto, a digitalização depende tanto da tecnologia adequada quanto de transformação cultural, participação das áreas e percepção de benefício no cotidiano.

O desafio central é encontrar uma solução que simultaneamente:

- torne processos do backoffice mais ágeis, eficientes e eficazes;
- seja simples e atraente para clientes internos e áreas operacionais;
- apresente retorno sobre investimento compreensível para a diretoria;
- tenha custo de implantação e operação compatível com os benefícios;
- possa ser efetivamente incorporada ao trabalho diário.

### Área do desafio

**Transformação digital.**

### Stakeholders explicitamente identificados

| Stakeholder | Interesse ou preocupação |
|---|---|
| Gestor e equipe de TI | Viabilizar soluções e apoiar a transformação das áreas |
| Clientes internos | Facilidade de uso, benefício prático e baixa fricção na mudança |
| Áreas operacionais e de backoffice | Processos mais eficientes sem ruptura desnecessária |
| Diretoria, donos e investidores internos | Retorno sobre investimento e controle de custos |

### Impactos informados no material do desafio

- aumento de custos;
- perda de produtividade;
- retrabalho;
- desperdício;
- impacto ambiental;
- dificuldade de gestão;
- perda de competitividade.

> [!note] Evidência pendente
> Os impactos foram informados qualitativamente. Ainda não há baseline quantitativo de custo, tempo, volume de papel, retrabalho ou produtividade.

### Situação atual

- A Geolab utiliza tecnologia moderna na produção.
- Alguns setores de backoffice ainda utilizam bastante papel.
- Há resistência interna à mudança de processos e ferramentas.
- Novas soluções precisam competir por orçamento com outros custos tecnológicos.
- O ERP utilizado é o **SAP**.
- Automação, módulos de sistemas e módulos do SAP são caminhos considerados.
- A TI atua como facilitadora para potencializar ideias das áreas.

### Resultado esperado

Uma abordagem progressiva de digitalização que demonstre valor em um processo real de backoffice, equilibre experiência do usuário e retorno financeiro e gere evidências para ampliar a transformação.

---

## Leitura estratégica

> [!warning] Interpretação
> Esta seção é análise do projeto e não deve ser tratada como declaração literal da Geolab.

O desafio combina cinco dimensões:

1. **Valor econômico:** justificar aquisição, licenciamento, implantação e operação.
2. **Processos:** reduzir papel, burocracia, espera e retrabalho.
3. **Adoção:** tornar a solução útil e simples para o cliente interno.
4. **Cultura:** apoiar a mudança da forma de trabalhar.
5. **Tecnologia e integração:** aproveitar sistemas existentes antes de adicionar novas plataformas.

### Correção de foco

O problema não deve ser reduzido prematuramente a OCR ou gestão documental. O processo prioritário ainda não foi identificado, e diferentes fluxos podem exigir soluções distintas.

O caminho de solução deve seguir:

```text
Selecionar processo real
        ↓
Medir baseline
        ↓
Identificar gargalo e comportamento
        ↓
Comparar alternativas
        ↓
Prototipar o menor fluxo viável
        ↓
Medir valor + adoção
        ↓
Definir integração e expansão
```

### Princípios para a solução

- Priorizar o uso de capacidades já licenciadas ou existentes quando forem adequadas.
- Avaliar automação determinística antes de aplicar IA.
- Usar IA somente onde houver valor mensurável.
- Tratar o SAP como sistema corporativo existente e evitar substituição ou duplicação sem necessidade comprovada.
- Verificar primeiro módulos, extensões, APIs e licenças SAP disponíveis antes de propor nova plataforma.
- Minimizar custos recorrentes e dependência de fornecedor.
- Projetar aprovação e operação para dispositivos adequados ao usuário.
- Incluir adoção e mudança cultural como parte do MVP, não como atividade posterior.
- Demonstrar retorno em linguagem executiva.

### Hipóteses iniciais

- Um único processo de backoffice pode servir como prova de valor para expansão posterior.
- O ganho percebido pelo usuário interno influencia diretamente a adoção.
- O aproveitamento de ferramentas existentes pode tornar o ROI mais atraente.
- Uma camada leve de workflow pode ser útil, mas isso depende do processo, da versão e das capacidades disponíveis no ambiente SAP.
- IA pode ajudar em classificação, extração, validação, resumo ou roteamento, desde que o caso escolhido exija essas capacidades.

### Métricas candidatas

#### Eficiência operacional

- tempo total do processo;
- tempo de espera para aprovação;
- quantidade de etapas manuais;
- taxa de retrabalho;
- custo operacional por ocorrência;
- volume de papel eliminado;
- percentual de processos rastreáveis ponta a ponta.

#### Retorno econômico

- custo de implantação;
- custo recorrente;
- economia mensal estimada;
- prazo de retorno do investimento;
- custo evitado com ferramentas ou integrações adicionais.

#### Adoção

- percentual de usuários ativos;
- taxa de conclusão sem suporte;
- tempo de treinamento;
- satisfação do usuário interno;
- percentual de processos que retornam ao fluxo manual;
- número de exceções e contornos externos ao sistema.

## Lacunas críticas

Antes de definir o MVP, é necessário descobrir:

1. quais processos de backoffice concentram maior dor e volume;
2. quem inicia, executa, aprova e audita cada processo;
3. qual versão do SAP está em uso, quais módulos, extensões, APIs e licenças estão disponíveis;
4. quais custos e tempos formam o baseline;
5. quais requisitos farmacêuticos, regulatórios e de segurança se aplicam;
6. quais usuários podem validar o protótipo;
7. qual investimento ou prazo de retorno seria considerado atraente;
8. quais critérios e restrições pertencem ao hackathon.

## Relacionamentos

- [[index|Índice do projeto]]
- [[mrd|MRD canônico]]
- [[fontes/transcricao-luciano-almeida|Depoimento de Luciano Almeida]]
- [[decisoes/README|Decisões]]
- [[../tasks/README|Backlog]]
- [[../prompts/README|Prompts]]
