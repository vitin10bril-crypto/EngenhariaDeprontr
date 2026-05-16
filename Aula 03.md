# Exercício — Análise de Tokens e Previsibilidade em Modelos de Linguagem

Este exercício tem como objetivo compreender como modelos de linguagem processam texto internamente e como parâmetros como temperatura influenciam a geração de respostas.

---

# Etapa 1 — Análise de Tokens

## Objetivo

Analisar como modelos de IA dividem palavras e frases em tokens para processamento computacional.

---

# Ferramenta Utilizada

## OpenAI Tokenizer

Ferramenta utilizada para visualizar:
- quantidade de tokens;
- divisão morfológica;
- fragmentação textual realizada pelo modelo.

---

# Texto Utilizado

## Nome Completo
> Victhor Gabriel 

## Frase
> “A engenharia de prompt otimiza LLMs”

---

# Resultado da Tokenização

## Quantidade aproximada de tokens

| Texto | Tokens Aproximados |
|---|---|
| Victhor Gabriel | 3 a 4 tokens |
| A engenharia de prompt otimiza LLMs | 8 a 11 tokens |

> A quantidade pode variar dependendo do modelo utilizado pelo tokenizer.

---

# Observação da Divisão Morfológica

Os modelos de IA normalmente dividem o texto em:
- palavras completas;
- partes de palavras;
- símbolos;
- espaços;
- pontuação.

## Exemplo de divisão possível

| Texto Original | Possível Divisão em Tokens |
|---|---|
| engenharia | engen + haria |
| otimiza | otim + iza |
| LLMs | LLM + s |

Isso demonstra que modelos de linguagem não interpretam texto exatamente como humanos, mas como sequências numéricas associadas a tokens.

---

# Importância dos Tokens

Os tokens são fundamentais porque:
- controlam o tamanho máximo das respostas;
- influenciam custo computacional;
- afetam velocidade de processamento;
- determinam limite de contexto do modelo.

Quanto maior a quantidade de tokens:
- maior o custo;
- maior o uso de memória;
- maior a capacidade contextual da IA.

---

# Etapa 2 — Teste de Previsibilidade

## Objetivo

Compreender como modelos de linguagem realizam previsões probabilísticas de palavras.

---

# Prompt Utilizado

> “O gato come…”

---

# Resposta Técnica (Baixa Temperatura)

Quando solicitado para agir de forma técnica e previsível, o modelo tende a gerar respostas estatisticamente mais comuns.

## Possíveis palavras previstas

| Palavra | Justificativa |
|---|---|
| ração | Associação comum com gatos domésticos |
| peixe | Relação cultural frequente |
| comida | Continuação genérica e altamente provável |

---

# Características da Baixa Temperatura

- respostas mais previsíveis;
- menor criatividade;
- maior precisão estatística;
- foco em padrões frequentes.

---

# Resposta Criativa (Alta Temperatura)

Quando solicitado para ser criativo, o modelo amplia a diversidade probabilística.

## Possíveis palavras previstas

| Palavra | Justificativa |
|---|---|
| estrelas | Construção poética |
| memórias | Associação abstrata |
| aventuras | Continuação narrativa criativa |

---

# Características da Alta Temperatura

- respostas mais variadas;
- menor previsibilidade;
- maior criatividade;
- maior liberdade interpretativa.

---

# Comparação entre Temperaturas

| Temperatura | Resultado |
|---|---|
| Baixa | Respostas técnicas e previsíveis |
| Média | Equilíbrio entre precisão e criatividade |
| Alta | Respostas criativas e menos previsíveis |

---

# Conclusão

Este exercício demonstra dois conceitos fundamentais dos modelos de linguagem:

## 1. Tokens
Os modelos processam texto através de fragmentos chamados tokens, e não exatamente como palavras humanas completas.

## 2. Probabilidade
As respostas geradas pela IA são previsões probabilísticas baseadas em padrões aprendidos durante o treinamento.

Além disso, parâmetros como temperatura influenciam diretamente:
- criatividade;
- previsibilidade;
- precisão;
- e diversidade das respostas produzidas.
