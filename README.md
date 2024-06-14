# Conversor de Moedas

## Visão Geral

O **Conversor de Moedas** é uma aplicação Java que permite converter valores entre diferentes moedas com base nas taxas de câmbio atuais obtidas de uma API de terceiros. A aplicação solicita ao usuário as moedas de origem e destino e o valor a ser convertido, então calcula e exibe o valor convertido. Além disso, mantém um histórico das conversões realizadas, que é salvo em um arquivo para futuras consultas.

## Funcionalidades

- Conversão de valores entre diferentes moedas usando taxas de câmbio atualizadas.
- Suporte a múltiplas moedas, incluindo USD, EUR, BRL, ARS, e GBP.
- Histórico das conversões realizadas, com detalhes sobre cada operação.
- Interface de linha de comando interativa para facilitar a entrada de dados pelo usuário.

## Tecnologias Utilizadas

- **Java 11 ou superior**: Linguagem de programação principal do projeto.
- **Gson**: Biblioteca para manipulação de JSON.
- **HttpClient**: Para realizar requisições HTTP à API de taxas de câmbio.
- **API Exchange Rate**: Para obter as taxas de câmbio atuais.

## Requisitos

- Java 11 ou superior instalado em seu sistema.
- Acesso à internet para buscar as taxas de câmbio da API.

## Instalação e Execução

1. **Clone o repositório**:

   ```bash
   git clone https://github.com/seu-usuario/conversor-de-moedas.git
   cd conversor-de-moedas
