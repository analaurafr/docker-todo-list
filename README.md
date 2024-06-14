# Projeto - Docker Todo-List

## Descrição do Projeto

Este projeto, desenvolvido como parte dos estudos do módulo de *Back-end* da escola de tecnologia [Trybe](https://www.betrybe.com/), consiste na criação de **contêineres Docker** para aplicações de front-end, back-end e testes. 

## Objetivo

O objetivo deste projeto é praticar o uso de Docker para criar e gerenciar contêineres, além de orquestrar múltiplos contêineres que compõem uma aplicação completa. Isso permitirá entender como os serviços podem se comunicar entre si dentro de um ambiente conteinerizado, proporcionando uma visão prática da integração e do desenvolvimento de aplicações distribuídas.

## Estrutura do Projeto

### Contêineres

-   **Front-end Container**: Responsável por servir a aplicação React.
-   **Back-end Container**: Responsável por executar a API Node.js e interagir com o banco de dados.
-   **Test Container**: Responsável por executar os testes automatizados da aplicação.

### Orquestração

-   **Docker Compose**: Arquivo de configuração para definir e orquestrar os serviços dos contêineres, garantindo a comunicação e a dependência entre eles.
