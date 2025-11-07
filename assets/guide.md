# Guia Estratégico: 5 Interações no Lovable para Vibe Coding

Este guia foi desenhado para extrair o máximo do plano gratuito diário do Lovable e cumprir os requisitos do desafio, indo do conceito macro aos detalhes do portfólio.

## Estratégia de 5 Turnos

### Interação 1: O "Big Bang" (Gerando a Base)
* **Objetivo:** Estabelecer a estrutura principal do app com base no seu PRD.
* **Sua Vibe:** "Tech Lead passando o briefing inicial."
* **Prompt Sugerido:**
    > # MISSÃO
Você é o Tech Lead e Product Designer de uma startup. Sua missão é estruturar o conceito do "FinChat" (nome provisório), um assistente financeiro pessoal baseado inteiramente em interfaces conversacionais (CUI - Conversational User Interface).

# MANIFESTO DO PRODUTO (A "VIBE")
Nós acreditamos que controlar finanças não deve ser chato. Nosso app não é uma calculadora, é um companheiro financeiro. Ele deve ser:
- **Invisível:** O máximo de automação possível.
- **Empático:** Nunca julga os gastos do usuário, apenas orienta.
- **Simples:** Se parece com uma planilha, nós falhamos.

# DETALHAMENTO DAS FUNCIONALIDADES
Para cada funcionalidade abaixo, eu preciso que você defina *como* ela funciona no back-end conceitual e dê um exemplo de interação no front-end (chat):

1.  **Input Multimodal:** Aceitar texto ("gastei 30 no uber"), voz (áudio transcrito) e idealmente leitura de comprovantes (imagens).
2.  **Categorização Contextual:** O agente deve aprender com o usuário. Se ele sempre classifica "Padaria da Esquina" como "Lazer" (e não alimentação), o agente deve se adaptar.
3.  **Feedback Loop (Agente Proativo):** O agente não espera o usuário perguntar. Ele deve analisar padrões e sugerir ações: "Parece que se você economizar R$5 por dia, atinge sua meta de viagem 1 semana antes. Topa tentar?".
4.  **Micro-Relatórios:** Cards visuais simples dentro do chat que resumem a semana, sem precisar sair da tela de conversa.

# RESTRIÇÕES DO MVP
- Deve ser mobile-first.
- Foco total na rapidez de inserção (o usuário deve gastar menos de 5 segundos para registrar algo).

# O QUE VOCÊ DEVE ENTREGAR
1.  **Persona do Agente:** Defina o nome, tom de voz e 3 regras de comportamento do nosso assistente IA.
2.  **Jornada do Usuário (Dia 1):** Descreva passo a passo a primeira interação de um novo usuário com o app.
3.  **Stack Tecnológica Sugerida:** Que ferramentas de IA e frameworks (ex: React Native, OpenAI API, etc.) você recomenda para este MVP e por quê?
4.  **Plano de Validação de Hipótese:** Como vamos medir se as pessoas realmente preferem conversar a usar formulários? Defina 1 métrica principal (North Star Metric).
    >
    > **Instrução Adicional:** Com base neste PRD, crie a interface inicial do "FinChat". Ela deve ser **mobile-first** e centrada inteiramente em uma interface de chat (como o WhatsApp ou Telegram), sem dashboards complexos na tela inicial. O usuário deve ver apenas uma saudação amigável do agente e o campo para digitar.

### Interação 2: Ajuste de Vibe Visual (Look & Feel)
* **Objetivo:** Garantir que o app não pareça "frio" ou "bancário".
* **Sua Vibe:** "Designer Diretor de Arte refinando a estética."
* **Prompt Sugerido:**
    > Vamos ajustar a vibe visual. Eu quero que o app pareça amigável, moderno e calmo. Use tons de [Sua Cor Preferida, ex: menta ou azul suave] e tipografia arredondada para parecer menos intimidante. Adicione botões de "Ação Rápida" logo acima do campo de digitação com opções como: "💸 Registrar Gasto", "🎯 Ver Metas", "📊 Resumo Semanal".

### Interação 3: Dando Vida ao Agente (A "Alma" do App)
* **Objetivo:** Simular a inteligência conversacional para os prints do seu README.
* **Sua Vibe:** "Roteirista definindo a personalidade do personagem."
* **Prompt Sugerido:**
    > Agora, simule uma conversa na tela de chat para demonstrar o Agente Proativo.
    >
    > Mostre a seguinte interação estática na tela:
    > 1. **Usuário:** "Gastei 80 reais em hambúrguer."
    > 2. **FinChat:** "Anotado! 🍔 Classifiquei como 'Alimentação/Delivery'. Dica: Você já usou 70% do seu orçamento de delivery essa semana. Que tal cozinhar no sábado? 😊"

### Interação 4: O Plano de MVP (Documentação Visual)
* **Objetivo:** Gerar o conteúdo técnico exigido no desafio, mas de forma visual dentro do protótipo.
* **Sua Vibe:** "Product Manager definindo o roadmap."
* **Prompt Sugerido:**
    > Crie uma segunda tela chamada "Sobre o MVP" (acessível por um ícone de menu).
    > Nesta tela, exiba em cards organizados:
    > 1. **As 5 Funcionalidades-Chave** (resumidas do PRD).
    > 2. **Stack Tecnológica Sugerida** (ex: React Native + OpenAI GPT-4o mini + Supabase).
    > 3. **Métrica de Sucesso** (ex: "% de usuários que registram gastos por 7 dias seguidos").

### Interação 5: O "Money Shot" (Polimento Final)
* **Objetivo:** Preparar a tela principal para o print perfeito que vai para o seu GitHub.
* **Sua Vibe:** "Marketing preparando o material de lançamento."
* **Prompt Sugerido:**
    > Para finalizar, vamos polir a tela principal para apresentação. Adicione um cabeçalho acolhedor com "Olá, Marcus! 👋" no topo. Garanta que a conversa simulada esteja bem visível e que o design pareça um produto pronto para uso. Este será o print principal do meu portfólio.
