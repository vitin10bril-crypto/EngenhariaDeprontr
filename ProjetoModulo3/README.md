# EngenhariaDePrompt - Aplicações em IA

**Curso:** Análise e Desenvolvimento de Sistemas  
**Disciplina:** Engenharia de Prompt e Aplicações em Inteligência Artificial  
**Professora:** Kadidja Valeria Reginaldo de Oliveira  
**Instituição:** UDF - Universidade Distrito Federal

---

## 📌 Desafio Escolhido

**Sistema de Registro de Visitantes para Condomínio**

Um aplicativo web responsivo para gerenciar a entrada e saída de visitantes em condomínios residenciais, permitindo:
- Registro detalhado de visitantes (nome, apartamento, residente responsável, motivo da visita)
- Controle de horários de entrada e saída
- Edição e deleção de registros
- Busca e filtros de dados
- Exportação de dados em formato CSV
- Estatísticas em tempo real

---

## 🖥️ Protótipo

### Características do Protótipo:

**Funcionalidades Principais:**
- ✅ Formulário de registro com validação de campos obrigatórios
- ✅ Tabela dinâmica com todos os visitantes registrados
- ✅ Modal para edição de registros
- ✅ Sistema de busca em tempo real
- ✅ Exportação de dados em CSV
- ✅ Cards de estatísticas (total, entradas hoje, saídas hoje)
- ✅ Status visual (verde para "Dentro", vermelho para "Saído")

**Tecnologias Utilizadas:**
- HTML5 (estrutura semântica)
- CSS3 (design responsivo e gradientes)
- JavaScript Vanilla (funcionalidades interativas)
- LocalStorage (persistência de dados)

**Como Funciona:**
1. O usuário preenche o formulário de entrada com dados do visitante
2. O sistema salva os dados no LocalStorage do navegador
3. A tabela atualiza automaticamente mostrando o visitante
4. Ao registrar a saída, o status muda para "Saído"
5. É possível editar ou deletar registros a qualquer momento
6. Os dados podem ser exportados em CSV para análise posterior

**Link da Aplicação:**
file:///C:/Users/VICTHORGABRIELGONZAG/Downloads/condominio.html

---

## ⚙️ Plataforma Utilizada

**Plataforma:** HTML5 + CSS3 + JavaScript Vanilla (Vibeecode/Lowcode Frontend)

**Justificativa da Escolha:**

1. **Flexibilidade Total**: Não há dependência de plataformas externas - o código é puro e executável em qualquer navegador
2. **Rapidez no Desenvolvimento**: Sem necessidade de configuração complexa, apenas lógica frontend
3. **Personalização Completa**: Cada elemento pode ser customizado sem restrições
4. **Sem Custos**: Não requer servidores ou assinaturas premium
5. **Aprendizado Prático**: Demonstra conceitos reais de programação web mantendo simplicidade
6. **Portabilidade**: Pode ser hospedado em qualquer serviço (GitHub Pages, Vercel, Firebase, etc.)

---

## ✅ Vantagens Identificadas

### 1. **Prototipagem Rápida**
- Desenvolvimento de funcionalidade completa em poucas horas
- Visualização imediata das alterações no navegador
- Iterações rápidas sem necessidade de build/compilação

### 2. **Integração Simples com LocalStorage**
- Persistência de dados sem necessidade de backend
- Dados salvos localmente no navegador do usuário
- Funciona offline sem dependências externas

### 3. **Automação de Processos**
- Atualização automática de listas e estatísticas
- Filtros e buscas em tempo real
- Validação de formulários integrada
- Exportação automática de dados em CSV

### 4. **Interface Intuitiva e Responsiva**
- Design adaptável para desktop, tablet e mobile
- Grid layout flexível com CSS3
- Feedback visual imediato (cores, sombras, transições)

### 5. **Controle Total sobre Dados**
- Sem intermediários ou plataformas
- Dados armazenados localmente
- Sem dependência de APIs externas

---

## ⚠️ Limitações Encontradas

### 1. **Customização Limitada de Dados**
- **Problema**: LocalStorage tem limite de ~5-10MB por domínio
- **Impacto**: Não é viável para grandes volumes de dados (milhares de registros)
- **Solução Adotada**: Implementação de sistema simples ideal para pequenos condomínios (até 500 visitantes/mês)

### 2. **Dependência de Hospedagem e Segurança**
- **Problema**: Dados sensíveis armazenados no navegador do usuário
- **Impacto**: Qualquer pessoa com acesso ao dispositivo pode ver os dados
- **Solução Adotada**: Implementação de alertas de confirmação para deletar dados; recomendação de usar em ambiente controlado

### 3. **Risco de Lock-in Tecnológico**
- **Problema**: Se mudar de plataforma/framework, precisaria reescrever tudo
- **Impacto**: Escalabilidade limitada para versões futuras
- **Solução Adotada**: Código bem estruturado e documentado para facilitar migração para backend (Node.js, Python, etc.)

### 4. **Falta de Sincronização em Tempo Real**
- **Problema**: Dados não sincronizam entre múltiplos dispositivos
- **Impacto**: Cada máquina tem seus próprios dados isolados
- **Solução Adotada**: Sugestão para versão futura com backend + banco de dados

### 5. **Sem Suporte a Multi-usuário**
- **Problema**: Não há sistema de login ou controle de acesso
- **Impacto**: Qualquer pessoa pode editar/deletar registros
- **Solução Adotada**: Recomendação de adicionar autenticação em versão profissional

---

## 📚 Reflexão Crítica

### Como o Grupo Lidou com as Limitações:

**Estratégia 1: Aceitar Limitações e Focar no MVP**
- Optamos por criar um Produto Mínimo Viável (MVP) funcional
- Aceitamos que LocalStorage tem limitações, mas é suficiente para o escopo inicial
- Documentamos essas limitações claramente para versões futuras

**Estratégia 2: Design Escalável desde o Início**
- Estruturamos o código em funções modulares e reutilizáveis
- Separamos lógica de dados (JavaScript) da apresentação (HTML/CSS)
- Isso facilita migração para um backend sem reescrever a interface

**Estratégia 3: Implementar Medidas de Segurança Básicas**
- Adicionar confirmações de ação (delete, limpar todos)
- Validar todos os campos de entrada
- Alertas visuais para ações irreversíveis

**Estratégia 4: Documentação Completa**
- Comentários no código explicando funções principais
- Instruções de uso no footer da aplicação
- Arquivo README com guia técnico completo

**Estratégia 5: Plano de Evolução Realista**
- Versão 1.0 (Atual): Frontend puro com LocalStorage
- Versão 2.0 (Proposta): Backend com Node.js + MongoDB
- Versão 3.0 (Futura): App nativa mobile com Firebase
- Versão 4.0 (Futura): Dashboard com IA para análise de padrões

---

## 👥 Colaboração

### Organização do Projeto:

**Integrantes:**
- 👨‍💻 **Vitin Copilot** (GitHub Copilot)
- 👨‍💻 **Victhor Gabriel** (Desenvolvedor Front-end)

### Divisão de Responsabilidades:

| Tarefa | Responsável | Status |
|--------|-------------|--------|
| Análise de Requisitos | Ambos | ✅ Concluído |
| Design da Interface | Victhor Gabriel | ✅ Concluído |
| Desenvolvimento HTML/CSS | Ambos | ✅ Concluído |
| Lógica JavaScript | Vitin Copilot | ✅ Concluído |
| Testes de Funcionalidade | Ambos | ✅ Concluído |
| Documentação | Vitin Copilot | ✅ Concluído |
| Hospedagem no GitHub | Victhor Gabriel | ✅ Concluído |

### Metodologia:
- **Daily Standup**: Sincronização diária das tarefas
- **Code Review**: Revisão de código antes de merge
- **Versionamento**: Commits atômicos com mensagens claras
- **Feedback Iterativo**: Ajustes contínuos baseados em testes

---

## 📝 Registro da Aula

| Campo | Informação |
|-------|-----------|
| **Data** | 11/05/2026 |
| **Atividade** | Discussão Crítica + Mini-projeto de Aplicação |
| **Local** | Laboratório de Informática / Quadro Branco |
| **Professora** | Kadidja Valeria Reginaldo de Oliveira |
| **Duração** | 4 horas |
| **Participantes** | 2 desenvolvedores + 1 facilitadora |

### Resumo da Aula:
1. Apresentação do desafio de vibeecode/lowcode
2. Brainstorming de ideias de projetos
3. Seleção do projeto (Sistema de Visitantes)
4. Prototipagem rápida em HTML/CSS/JS
5. Discussão sobre vantagens e limitações
6. Apresentação e feedback

---

## 🚀 Próximos Passos

### Melhorias Sugeridas para o Protótipo (Curto Prazo):

1. **Validação de Email** ✨
   - Adicionar campo de email do visitante
   - Validação de formato de email

2. **Sistema de Notificações** 🔔
   - Toast notifications para ações bem-sucedidas
   - Avisos visuais em caso de erro

3. **Temas Personalizáveis** 🎨
   - Modo claro/escuro
   - Paletas de cores customizáveis

4. **Impressão de Registros** 🖨️
   - Gerar relatório em PDF
   - Impressão formatada da tabela

5. **Busca Avançada** 🔍
   - Filtros por data
   - Filtro por motivo de visita
   - Filtro por status (dentro/saído)

### Possíveis Evoluções para Projeto Final (Médio Prazo):

1. **Backend com Node.js + Express**
   - Servidor REST API
   - Autenticação com JWT
   - Banco de dados MySQL/MongoDB

2. **Integração com IA (Engenharia de Prompt)**
   - Análise automática de padrões de visitas
   - Sugestões de segurança baseadas em IA
   - Geração automática de relatórios com ChatGPT/Claude
   - Detecção de anomalias em visitantes

3. **Aplicação Mobile com React Native**
   - App para iOS e Android
   - Sincronização em tempo real
   - Notificações push

4. **Dashboard Avançado**
   - Gráficos e estatísticas visuais
   - Heatmaps de horários de pico
   - Histórico detalhado por apartamento

5. **Sistema de Autenticação**
   - Login para porteiros/síndicos
   - Controle de permissões
   - Auditoria de ações

6. **Integração com APIs Externas**
   - Envio de SMS/Email para residentes
   - Integração com câmeras de segurança
   - QR Code para identificação rápida

7. **Machine Learning**
   - Previsão de padrões de visitas
   - Detecção de comportamentos suspeitos
   - Análise preditiva de segurança

---

## 📚 Recursos Adicionais

- **Documentação Técnica**: Veja o código comentado em `visitantes-condominio.html`
- **Hospedagem**: GitHub Pages ou Vercel
- **Ferramentas Utilizadas**: VS Code, GitHub, ChatGPT, Copilot

---

## 📄 Licença

Este projeto é desenvolvido como atividade acadêmica da disciplina de **Engenharia de Prompt e Aplicações em IA**.

**Desenvolvido por:** Vitin Copilot & Victhor Gabriel  
**Instituição:** UDF - Universidade Distrito Federal  
**Professora:** Kadidja Valeria Reginaldo de Oliveira  
**© 2026** - Todos os direitos reservados

---

## 🎯 Objetivo da Disciplina

A capacidade de conversar efetivamente com sistemas de IA é o que separa os profissionais comuns dos inovadores.

**Compreender sobre:**
- ✅ Controlar sistemas de IA
- ✅ Direcionar respostas com precisão
- ✅ Extrair valor real de modelos de IA de forma estratégica

**Transformar ideias em instruções claras e eficazes, capazes de gerar respostas:**
1. Úteis
2. Criativas
3. Confiáveis

