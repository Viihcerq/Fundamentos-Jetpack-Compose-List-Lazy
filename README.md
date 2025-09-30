# Projeto: Lista de Jogos Favoritos com Jetpack Compose

Este projeto foi desenvolvido para a disciplina de Fundamentos do Jetpack Compose, criando um aplicativo Android que exibe uma lista de jogos e permite a filtragem dinâmica por estúdio.

---

## ✒️ Integrantes da Equipe

Vitoria Cerqueira, rm:552509
Felipe Pereira, rm: 551978
Leonardo Queiroz, rm:552500

---

## ✨ Funcionalidades

O aplicativo possui uma tela única com diversas funcionalidades interativas para gerenciar e visualizar a lista de jogos.

### 1. Tela Principal e Listagem de Jogos

Ao iniciar, o aplicativo exibe a lista completa de jogos favoritos em uma rolagem vertical. Cada item da lista mostra o nome do jogo, o estúdio e o ano de lançamento.

![Imagem da tela principal mostrando a lista completa de jogos](images/telaIInicial.png)

### 2. Filtro Rápido por Estúdio

Logo abaixo do campo de busca, há uma lista horizontal de estúdios. Ao tocar no card de um estúdio, a lista de jogos é imediatamente filtrada para exibir apenas os jogos daquele desenvolvedor.

![Imagem da tela mostrando o filtro rápido ao clicar em um estúdio na lista horizontal](images/telaFiltro.png)

### 3. Limpar Filtro

Sempre que um filtro está ativo (seja por texto ou por clique), um botão de texto "Limpar filtro" aparece na tela. Clicar nele remove todos os filtros aplicados e restaura a lista de jogos ao seu estado original.

![Imagem mostrando o botão "Limpar filtro" visível durante uma busca](images/telaFiltro2.png)

---

## 🛠️ Tecnologias Utilizadas

* **Linguagem:** Kotlin
* **UI Toolkit:** Jetpack Compose
* **Arquitetura:** State Management com `remember { mutableStateOf(...) }`
* **Componentes:** `LazyColumn`, `LazyRow`, `Card`, `OutlinedTextField`
* **Design:** Material 3