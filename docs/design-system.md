# Design System — SENAI IndTech / Geolab

## Status

Design system de trabalho do projeto, derivado da linguagem BlueGold Premium e adaptado exclusivamente ao desafio de digitalização do backoffice da Geolab.

> Este sistema não representa a identidade corporativa oficial da Geolab, do SENAI ou da SAP. É uma linguagem visual para protótipos, documentação e apresentação do hackathon.

## Princípios

1. **Clareza executiva:** decisões, métricas e riscos devem ser compreendidos rapidamente.
2. **Confiança industrial:** o visual deve comunicar precisão, rastreabilidade e estabilidade.
3. **Tecnologia humana:** pessoas e adoção aparecem no centro; automação não é retratada como substituição.
4. **Evidência antes da promessa:** fatos, hipóteses, estimativas e decisões usam estados visuais diferentes.
5. **Progressão:** a transformação é mostrada como uma jornada incremental, não como ruptura total.

## Paleta

| Token | Valor | Uso |
|---|---|---|
| `navy-950` | `#07111F` | Fundo principal |
| `navy-900` | `#0D1B2E` | Superfícies |
| `blue-500` | `#4EA1FF` | Ação e informação |
| `cyan-300` | `#77C7FF` | Destaque de dados |
| `gold-500` | `#D6B45B` | Decisão e valor |
| `gold-300` | `#F0D98A` | Ênfase premium |
| `text` | `#F4F7FB` | Texto principal |
| `muted` | `#9FB2CA` | Texto secundário |
| `success` | `#5ED2A0` | Validado/concluído |
| `warning` | `#F2B766` | Hipótese/atenção |
| `danger` | `#FF7B86` | Bloqueio/risco |

## Tipografia

- Interface e texto: `Inter`, `Segoe UI`, sistema sans-serif.
- Números e códigos: `JetBrains Mono`, `SFMono-Regular`, monoespaçada.
- Títulos: sans-serif com peso 700–800, caixa alta apenas em rótulos curtos.

## Forma e profundidade

- Raio grande: `24px`.
- Raio pequeno: `15px`.
- Borda: branco entre 8% e 14% de opacidade.
- Sombra: ampla e difusa, nunca pesada.
- Dourado: usado para decisão, valor e direção; nunca como preenchimento dominante.

## Estados semânticos

| Estado | Cor | Exemplo |
|---|---|---|
| Fato confirmado | Verde | ERP SAP confirmado |
| Hipótese | Âmbar | Ciclos e ganhos ainda em validação |
| Estimativa | Azul | Projeções de tempo e custo |
| Bloqueio | Vermelho | PRD bloqueado |
| Decisão | Dourado | Escolher o processo do MVP |

## Componentes prioritários

- topbar e navegação contextual;
- hero executivo;
- cards de princípio e de hipótese;
- badges de estado;
- KPIs com origem da informação;
- tabelas comparativas;
- alertas de evidência;
- fluxo de processo;
- linha do tempo;
- botões primário, secundário e discreto;
- campos de formulário;
- rodapé com versão e status.

## Regras de conteúdo

- Usar “estimativa”, “hipótese” ou “reportado” quando não houver baseline confirmado.
- Nunca misturar desenvolvimento de produto com produção de lote conhecido.
- Não prometer redução de prazo da Anvisa.
- Não apresentar integração SAP como implementada.
- Preferir títulos diretos, métricas com unidade e chamadas para decisão.

## Referência visual

O arquivo `design-system-geolab.html` contém tokens, componentes e padrões responsivos em funcionamento.

