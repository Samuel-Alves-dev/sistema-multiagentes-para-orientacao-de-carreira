# Desafio DIO - Simulação de Sistema Multiagentes para Orientação de Carreira

## 📖 Sobre o Projeto

Este projeto foi desenvolvido como parte de um desafio da DIO com o objetivo de explorar conceitos de Inteligência Artificial Generativa, Engenharia de Prompt e Sistemas Multiagentes.

A proposta consistiu em simular a colaboração entre dois Agentes de IA especializados, onde cada agente possui uma responsabilidade específica dentro do processo de orientação profissional.

O fluxo utiliza o conceito de **handoff**, permitindo que um agente colete e analise informações do usuário e transfira esse contexto para outro agente responsável por gerar um plano completo de desenvolvimento profissional.

---

## 🎯 Objetivo

Demonstrar como múltiplos agentes de IA podem trabalhar em conjunto para:

- Coletar informações do usuário.
- Analisar perfis profissionais.
- Recomendar carreiras compatíveis.
- Compartilhar contexto entre agentes.
- Criar planos de estudos personalizados.
- Simular aplicações reais de sistemas multiagentes.

---

## 🤖 Agente 1 - Entrevistador de Carreira

O primeiro agente foi responsável por realizar uma entrevista estruturada para compreender o perfil profissional do usuário.

### Funções

- Identificar interesses e motivações.
- Avaliar experiência prévia.
- Entender disponibilidade de estudo.
- Mapear preferências de trabalho.
- Compreender objetivos profissionais.
- Relacionar habilidades com áreas de tecnologia.
- Realizar uma análise de compatibilidade entre perfil e carreiras.

### Processo

O agente conduziu uma entrevista composta por 7 perguntas realizadas individualmente.

Após coletar todas as respostas, realizou uma análise interna baseada em:

- Afinidade com interesses.
- Demanda de mercado.
- Tempo de preparação para entrada na área.
- Aproveitamento de experiências anteriores.

### Resultado

Ao final da análise, o agente gerou:

- Ranking das 3 carreiras mais compatíveis.
- Explicação personalizada para cada sugestão.
- Vantagens e desafios de cada carreira.
- Contexto geral de mercado.

O usuário então escolheu uma das carreiras sugeridas para prosseguir para a próxima etapa.

---

## 🤖 Agente 2 - Planejador de Carreira

Após a escolha da carreira, o segundo agente recebeu todas as informações coletadas pelo Agente 1.

### Informações Recebidas

- Carreira escolhida.
- Disponibilidade semanal de estudo.
- Nível de experiência.
- Objetivo profissional.
- Preferência de atuação.
- Interesses tecnológicos.

### Funções

- Explicar o dia a dia da profissão escolhida.
- Mapear habilidades necessárias.
- Criar um roadmap de estudos personalizado.
- Sugerir projetos para portfólio.
- Preparar o usuário para entrevistas.
- Recomendar trilhas de aprendizagem da DIO.

### Resultado

O agente gerou um plano completo contendo:

- Visão da profissão.
- Mapa de skills.
- Roadmap de 90 dias.
- Projeto de portfólio.
- Simulação de entrevistas.
- Trilha recomendada na plataforma DIO.

---

## 🔗 Conceito de Handoff

Um dos principais conceitos demonstrados neste desafio foi o **handoff entre agentes**.

O Agente 1 foi responsável por coletar e analisar informações.

Após a escolha da carreira, essas informações foram transferidas para o Agente 2.

O segundo agente utilizou o contexto recebido para criar um plano totalmente personalizado.

Esse processo simula arquiteturas modernas de sistemas multiagentes utilizadas em aplicações reais de Inteligência Artificial.

---

## 🔄 Fluxo de Funcionamento

```text
Usuário
   ↓
Agente 1
(Entrevista com 7 perguntas)
   ↓
Análise de Perfil
   ↓
Ranking de 3 Carreiras
   ↓
Escolha da Carreira
   ↓
Handoff de Contexto
   ↓
Agente 2
(Planejador de Carreira)
   ↓
Visão da Profissão
   ↓
Mapa de Skills
   ↓
Roadmap de 90 Dias
   ↓
Projeto de Portfólio
   ↓
Preparação para Entrevistas
   ↓
Trilha DIO Recomendada
```

---

## 🚀 Tecnologias e Conceitos Utilizados

- Inteligência Artificial Generativa
- Engenharia de Prompt
- Sistemas Multiagentes
- Handoff entre Agentes
- Planejamento de Carreira Assistido por IA
- GitHub

---

## 📚 Aprendizados Obtidos

Durante o desenvolvimento deste desafio foi possível compreender:

- Como agentes de IA podem colaborar entre si.
- A importância da separação de responsabilidades entre agentes.
- Como realizar transferência de contexto entre agentes.
- A importância da Engenharia de Prompt para obtenção de resultados consistentes.
- Como estruturar fluxos de decisão utilizando IA.
- Como personalizar recomendações com base em dados coletados.
- Aplicações práticas de sistemas multiagentes no mercado.

---

## 🏆 Conclusão

Este desafio permitiu explorar conceitos fundamentais de Inteligência Artificial Generativa através da simulação de um sistema multiagente.

A colaboração entre os dois agentes demonstrou como é possível criar fluxos inteligentes de coleta, análise e utilização de informações para gerar recomendações altamente personalizadas.

Além disso, o projeto evidenciou a importância do conceito de handoff e o potencial dos sistemas multiagentes para aplicações reais em orientação profissional, educação e desenvolvimento de carreira.
