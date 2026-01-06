# 🏙️ *Banco Imobiliário Recife*
### Projeto Acadêmico — Linguagem C | Lógica de Programação e Estruturas de Dados

---

## 🌟 *Visão Geral*

O *Banco Imobiliário Recife* é uma **releitura completa do jogo Banco Imobiliário**, desenvolvido em **linguagem C**, trazendo uma proposta regional e dinâmica.

O jogo substitui os elementos tradicionais por **bairros, pontos turísticos e situações reais da cidade do Recife**, além de um sistema exclusivo de **cartas temáticas**, com problemas urbanos e bônus locais que **alteram totalmente o andamento da partida**.

O projeto foi desenvolvido com foco em:
- Lógica de programação
- Estruturas de dados
- Organização e modularização de código
- Simulação de regras complexas de negócio

---

# 🎲 *Conceito do Jogo*

- Os jogadores percorrem um tabuleiro inspirado na cidade do **Recife**
- Cada casa representa:
  - Bairros do Recife
  - Pontos turísticos
  - Casas especiais criadas exclusivamente para esta versão
- O objetivo é administrar recursos financeiros, adquirir propriedades e sobreviver às variações causadas pelos eventos do jogo

---

# 🃏 *Cartas Temáticas (Diferencial do Projeto)*

O jogo conta com um sistema exclusivo de cartas chamado **Rackatôm Recife**, inspirado em problemas reais e bônus urbanos da cidade.

### Exemplos de eventos:
- Problemas de mobilidade urbana
- Obras públicas inesperadas
- Incentivos culturais
- Multas, impostos e bônus municipais
- Eventos que beneficiam ou prejudicam jogadores aleatoriamente

Essas cartas tornam cada partida **única**, imprevisível e estratégica.

---

# 🏛 *Arquitetura da Aplicação*

O projeto foi estruturado de forma **modular**, respeitando boas práticas mesmo em linguagem C.

### ✔ *Módulo de Jogadores*
- Controle de saldo
- Posição no tabuleiro
- Propriedades adquiridas
- Situação no jogo (ativo/eliminado)

### ✔ *Módulo de Tabuleiro*
- Definição das casas
- Bairros e propriedades do Recife
- Casas especiais criadas no projeto
- Controle de movimentação dos jogadores

### ✔ *Módulo de Cartas*
- Cartas de bônus
- Cartas de penalidades
- Eventos aleatórios
- Sistema de sorteio e aplicação dos efeitos

### ✔ *Módulo Financeiro*
- Compra e venda de propriedades
uta
- Pagamento de taxas e multas
- Recebimento de bônus
- Atualização de saldos

### ✔ *Módulo Principal*
- Fluxo do jogo
- Controle de turnos
- Verificação de vitória ou eliminação
- Interação com o usuário via terminal

---

# 🧠 *Conceitos Trabalhados*

- Estruturas de dados
- Vetores e matrizes
- Funções e modularização
- Controle de fluxo
- Uso intensivo de `struct`
- Manipulação de estados do jogo
- Lógica de regras complexas
- Simulação de eventos aleatórios

---


---

# 🚀 *Como Rodar o Projeto*

## ✅ 1. *Pré-requisitos*
- Compilador C (GCC recomendado)
- Sistema operacional Windows, Linux ou macOS
- Terminal ou IDE (VS Code recomendado)

---

## ✅ 2. *Compilação*

No diretório do projeto, execute:

```bash
gcc src/*.c -o banco_imobiliario_recife


./banco_imobiliario_recife
