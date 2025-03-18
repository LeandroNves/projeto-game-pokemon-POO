# Pokémon RPG – Game de Pokémon em Python

## Descrição

Este projeto é um **RPG de Pokémon** desenvolvido em **Python** utilizando **Programação Orientada a Objetos (POO)**. O jogo permite aos jogadores capturar, treinar e batalhar com Pokémons em um mundo virtual, desafiando inimigos e explorando diferentes áreas. Através do uso de classes e herança, o código organiza de forma eficiente os diversos tipos de Pokémon, jogadores e inimigos, proporcionando uma experiência de jogo dinâmica e divertida.

## Conceitos e Tecnologias Utilizadas

- **Programação Orientada a Objetos (POO)**: O jogo é estruturado em classes, representando entidades como **Pokémon**, **Jogador**, **Inimigo**, e suas respectivas interações, como ataques e batalhas. A herança é utilizada para criar diferentes tipos de Pokémon (Elétrico, Fogo, Água), aproveitando o polimorfismo para personalizar seus ataques.
  
- **Classes e Objetos**: A criação de **classes** como `Pokemon`, `PokemonFogo`, `PokemonEletrico`, `PokemonAgua`, `Pessoa` e `Player` possibilita um modelo claro de como as entidades interagem dentro do jogo. Cada Pokémon possui características como **nível**, **ataque**, **vida**, e **nome**.

- **Herança e Polimorfismo**: A herança permite criar subclasses de **Pokemon** (como **PokemonFogo**, **PokemonEletrico**, e **PokemonAgua**), cada uma com ataques personalizados. O polimorfismo é utilizado para sobrescrever métodos de ataque em cada tipo de Pokémon.

- **Aleatoriedade e Funções de Combate**: A mecânica de combate é baseada em **probabilidade**, onde a quantidade de dano causado e a escolha do Pokémon são aleatórios, criando desafios dinâmicos e imprevisíveis para o jogador.

- **Persistência de Dados**: Utiliza o módulo **pickle** para salvar e carregar o progresso do jogador, permitindo que o jogo seja pausado e retomado posteriormente. Isso garante que o estado do jogador, incluindo Pokémon capturados e o dinheiro disponível, seja mantido entre sessões de jogo.

- **Exploração e Captura de Pokémons**: O jogo permite ao jogador explorar o mundo em busca de **Pokémons selvagens**. Quando um Pokémon é encontrado, o jogador tem a oportunidade de capturá-lo, se tiver sorte, aumentando seu time de Pokémon.

- **Batalhas**: As batalhas entre o jogador e inimigos são baseadas em turnos, onde o jogador escolhe um Pokémon e ataca o Pokémon adversário. O primeiro a derrotar o Pokémon inimigo vence a batalha e recebe uma recompensa em dinheiro.

## Funcionalidades

- **Escolher um Pokémon Inicial**: Ao iniciar, o jogador escolhe um Pokémon para começar sua jornada (Pikachu, Charmander ou Squirtle).
  
- **Captura de Pokémons**: Durante a exploração, o jogador pode capturar Pokémons selvagens, que serão adicionados à sua coleção.
  
- **Batalhas**: O jogador pode desafiar inimigos controlados pelo computador (Inimigos) em batalhas Pokémon, onde o objetivo é derrotar o Pokémon adversário.

- **Salvar e Carregar Jogo**: O progresso do jogador é salvo em um arquivo de banco de dados e pode ser carregado posteriormente para continuar a aventura de onde foi interrompida.

- **Dinheiro e Compras**: O jogador ganha dinheiro ao vencer batalhas, que pode ser usado para adquirir itens ou melhorar suas habilidades.

- **Exploração**: O jogador pode explorar diferentes áreas do mundo, onde pode encontrar Pokémons selvagens e outras oportunidades de captura.
