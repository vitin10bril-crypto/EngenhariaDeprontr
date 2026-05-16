# 🧪 Exercício — Influência de Contexto, Persona e Restrições em Prompts

Este exercício demonstra como diferentes estruturas de prompt alteram diretamente:
- o comportamento da IA;
- o estilo de resposta;
- o nível técnico;
- e o formato final gerado.

A comparação evidencia como contexto, persona e restrições funcionam como mecanismos de controle na Engenharia de Prompt.

---

# 📌 Objetivo do Exercício

Analisar como a IA modifica suas respostas quando o prompt possui:
- linguagem neutra;
- definição de persona;
- ou restrições extremamente específicas.

---

# 🟢 Versão Neutra

## Prompt

> Faça um código funcional para calcular a média de notas de um aluno.

---

# 🤖 Resposta Gerada

A IA respondeu de maneira:
- didática;
- explicativa;
- detalhada;
- e acessível para iniciantes.

O modelo:
- explicou conceitos;
- descreveu funções;
- apresentou exemplos;
- e forneceu versões em múltiplas linguagens.

---

## 📌 Características da Resposta

| Aspecto | Resultado |
|---|---|
| Linguagem | Educacional |
| Profundidade | Média |
| Explicações | Muitas |
| Público-alvo | Iniciantes |
| Estrutura | Tutorial |

---

# 📌 Observação

Como o prompt não definiu:
- formato;
- nível técnico;
- limite de tamanho;
- nem público específico,

a IA assumiu automaticamente uma postura genérica e instrucional.

---

# 🟡 Versão com Persona

## Prompt

> Você é um Dev Sênior arrogante, monte um programa de média de aluno em Python.

---

# 🤖 Resposta Gerada

A IA alterou completamente:
- o tom;
- a personalidade;
- a forma de comunicação;
- e o estilo textual.

A resposta tornou-se:
- mais agressiva;
- informal;
- confiante;
- e com linguagem típica de ambientes técnicos.

---

# 📌 Características da Resposta

| Aspecto | Resultado |
|---|---|
| Linguagem | Informal/Técnica |
| Persona | Dev Sênior arrogante |
| Estilo | Direto e crítico |
| Organização | Modular |
| Complexidade | Maior |

---

# 📌 Impacto da Persona

A definição de persona influenciou:
- vocabulário;
- tom emocional;
- organização lógica;
- e comportamento textual da IA.

Mesmo produzindo um código funcional, o modelo passou a interpretar o contexto como uma conversa entre programadores experientes.

---

# 🔴 Evento Restritivo

## Prompt

> Crie um código funcional que calcule a média de notas de um aluno.
>
> Regras:
> - usar apenas Python puro;
> - não utilizar bibliotecas;
> - responder somente com código;
> - sem explicações;
> - o menor código possível.

---

# 🤖 Resposta Gerada

```python
n = [float(x) for x in input("Notas: ").split()]
print(sum(n)/len(n) if n else 0)
