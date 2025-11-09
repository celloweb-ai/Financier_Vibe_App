# PRD FINAL

```
# FinChat – Product Requirements Document (PRD)

## 🧭 Visão Geral

**Nome do Produto**: FinChat (nome provisório)
**Tipo de Produto**: Assistente financeiro pessoal baseado em interface conversacional (CUI)
**Objetivo**: Ajudar usuários a gerenciar suas finanças de forma leve, empática e motivadora, por meio de conversas naturais e encantadoras.

---

## ✨ Manifesto do Produto

> Controlar finanças não deve ser chato.
> FinChat não é uma calculadora, é um companheiro financeiro.
> Ele deve ser:
- **Invisível**: Automatizado ao máximo.
- **Empático**: Nunca julga, sempre orienta.
- **Simples**: Se parece com uma planilha, falhamos.

---

## 👤 Persona do Agente

**Nome**: Nino
**Tom de Voz**: Inspirador e motivacional
- Fala como um amigo que acredita no potencial do usuário
- Usa frases positivas, celebra conquistas e transmite confiança
- Emojis são usados com moderação para reforçar leveza e afeto

**Regras de Comportamento**:
1. Motiva sem pressionar
2. Celebra o progresso, não a perfeição
3. Adapta o tom à jornada emocional do usuário

---

## 🛤️ Jornada do Usuário – Dia 1

1. Boas-vindas com saudação calorosa
2. Onboarding leve com definição de meta
3. Primeiro registro de despesa via texto ou voz
4. Confirmação empática e sugestão de categoria
5. Micro-relatório com resumo da semana
6. Sugestão proativa para ajudar na meta

---

## 🔧 Funcionalidades do MVP

### 1. Input Multimodal com Toque Humano

**Back-end**:
- NLP para texto
- Whisper (OpenAI) para voz
- Google Vision API para OCR
- Fallbacks amigáveis para entradas ambíguas

**Exemplo de Chat**:
Usuário: Gastei 30 no Uber.
Nino: Uber é vida, né? 🚗 Já anotei R$30 em Transporte. Quer salvar esse trajeto como favorito?

---

### 2. Categorização Contextual com Memória Afetiva

**Back-end**:  
- Aprendizado contínuo com correções manuais  
- Associação afetiva com estabelecimentos e categorias

**Exemplo de Chat**:

Usuário: Padaria da Esquina, R$15.
Nino: Ah, aquele pãozinho que alegra o dia! 😊 Costuma entrar como “Lazer”, tudo certo?

---

### 3. Feedback Proativo com Delicadeza

**Back-end**:  
- Regras de negócio + modelos preditivos simples  
- Sugestões motivacionais baseadas em metas e padrões

**Exemplo de Chat**:

Nino: Se você guardar R$5 por dia, sua viagem dos sonhos chega 1 semana antes. ✨ Que tal tentar?

---

### 4. Micro-Relatórios com Encanto Visual

**Back-end**:  
- Agregação de dados semanais  
- Cards visuais com destaques positivos e frases motivacionais

**Exemplo de Chat**:

Nino: Aqui está seu resumo da semana! 🎉

Total gasto: R$450
🥇 Destaque: Alimentação bem controlada!
💡 Dica: Que tal revisar os gastos com transporte?

---

## 📱 Interface Inicial

**Descrição**:  
Tela mobile-first, centrada em chat. Sem dashboards. Apenas Nino e o campo de entrada.

**Elementos**:
- Saudação do Nino  
- Campo de texto  
- Ícone de microfone  
- Ícone de anexo

**Exemplo**:

Nino: Olá, Marcus! Que bom te ver por aqui. Pronto para transformar sua relação com o dinheiro? Cada passo conta, e eu tô com você nessa! 🚀
[Campo de texto] [🎤] [📎]

---

## 🧰 Stack Tecnológica Sugerida

- **Frontend**: React Native  
- **Backend**: Node.js + Firebase  
- **IA e NLP**:
  - OpenAI API (chat e sugestões)  
  - Whisper (voz)  
  - Google Vision API (OCR)

**Justificativa**:  
Tecnologias maduras, com boa documentação e integração rápida para MVP mobile-first.

---

## 📊 Plano de Validação de Hipótese

**Hipótese**:  
Usuários preferem conversar com o app a preencher formulários.

**North Star Metric**:  
% de registros feitos via chat vs. formulários alternativos

**Método de Validação**:
- Teste A/B  
- Entrevistas qualitativas  
- Análise de tempo médio por registro

---

## 📈 Métricas Secundárias

1. **Tempo Médio de Registro**
   - Mede: Agilidade da interface  
   - Coleta: Timestamps de início/fim  
   - Relevância: Valida a restrição de <5s por registro

2. **Taxa de Uso de Input Multimodal**
   - Mede: Adoção de voz e imagem  
   - Coleta: Logs por tipo de input  
   - Relevância: Avalia aceitação dos canais alternativos

3. **Engajamento com Sugestões Proativas**
   - Mede: % de sugestões aceitas  
   - Coleta: Interações com mensagens proativas  
   - Relevância: Valida o papel do agente como parceiro ativo

```
