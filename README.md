# Professor IA — Do Zero ao Avançado

Este projeto e ambiente da IDE estão configurados com o **Professor IA: Do Zero ao Avançado**, uma Skill projetada para atuar como tutor particular, mentor e avaliador de aprendizagem personalizada em qualquer assunto.

---

## 📁 Estrutura de Arquivos

- [SKILL.md](file:///Users/vlaudimird.marques/Skill_Teacher/SKILL.md): Definição completa das diretrizes pedagógicas, estrutura das aulas, níveis de aprendizagem e comandos da Skill.
- [PROMPT_EXECUCAO.md](file:///Users/vlaudimird.marques/Skill_Teacher/PROMPT_EXECUCAO.md): Modelo de prompt pronto para iniciar uma nova trilha de aprendizagem.
- [TEMPLATE_PROGRESSO.md](file:///Users/vlaudimird.marques/Skill_Teacher/TEMPLATE_PROGRESSO.md): Modelo para acompanhamento de aulas, matriz de domínio, plano de revisão e bloco de continuidade entre conversas.
- [AGENTS.md](file:///Users/vlaudimird.marques/Skill_Teacher/AGENTS.md): Regras de comportamento e contexto para o agente nesta IDE.
- `.agents/skills/professor-ia-zero-ao-avancado/`: Instalação local da Skill no workspace.
- `~/.gemini/config/skills/professor-ia-zero-ao-avancado/`: Instalação global da Skill na sua IDE (disponível para todos os projetos).

---

## 🚀 Como Iniciar uma Trilha de Aprendizagem

Você pode simplesmente mandar uma mensagem no chat da IDE dizendo o que quer aprender, por exemplo:

> *"Quero aprender Python, começando do zero até conseguir criar automações no trabalho."*

Ou usar o formato guiado de [PROMPT_EXECUCAO.md](file:///Users/vlaudimird.marques/Skill_Teacher/PROMPT_EXECUCAO.md):
```text
Quero aprender [ASSUNTO], começando do meu nível atual e avançando progressivamente até [OBJETIVO FINAL].

- Meu nível atual: [ZERO / BÁSICO / INTERMEDIÁRIO / AVANÇADO / NÃO SEI]
- Meu objetivo prático: [O QUE QUERO CONSEGUIR FAZER]
- Tempo disponível: [MINUTOS POR DIA OU HORAS POR SEMANA]
- Preferência: [EXPLICAÇÕES / EXERCÍCIOS / PROJETOS / COMBINADO]
- Contexto em que vou aplicar o conhecimento: [TRABALHO / ESTUDO / PROJETO / INTERESSE PESSOAL]
```

---

## 🛠️ Comandos Disponíveis

Você pode usar comandos em linguagem natural a qualquer momento:

| Comando | Descrição |
|---|---|
| `/iniciar [assunto]` | Inicia uma nova trilha de estudos |
| `/diagnostico` | Faz uma avaliação rápida de conhecimentos prévios |
| `/mapa` | Apresenta a trilha completa de aprendizagem |
| `/aula` | Inicia ou continua a próxima aula |
| `/explicar-simples` | Explica como para um iniciante absoluto |
| `/aprofundar` | Aprofunda o conteúdo técnico |
| `/exemplos` | Apresenta novos exemplos práticos |
| `/exercicios` | Gera exercícios progressivos |
| `/desafio` | Apresenta um problema desafiador |
| `/projeto` | Propõe ou orienta o desenvolvimento de um projeto prático |
| `/avaliar` | Testa seu domínio atual do conteúdo |
| `/revisar` | Faz recuperação de conteúdos anteriores (revisão espaçada) |
| `/flashcards` | Cria cartões de memorização e recuperação ativa |
| `/resumo` | Apresenta uma síntese do progresso |
| `/retomar` | Continua com base no seu Bloco de Continuidade |
