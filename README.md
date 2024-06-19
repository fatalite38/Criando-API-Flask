# Aplicação Flask com Túnel Ngrok

Este projeto demonstra como criar uma aplicação simples em Flask e expô-la na internet usando ngrok. A aplicação serve um conjunto de dados de exemplo em formato JSON via um endpoint HTTP.

## Pré-requisitos

Antes de executar a aplicação, certifique-se de ter os seguintes requisitos instalados:

- Python 3.x
- Flask
- pyngrok

## Instalação

Para instalar os pacotes necessários, execute:

pip install flask
pip install pyngrok

## Autenticação do Ngrok
Adicione seu token de autenticação do ngrok para configurar o ngrok:
ngrok config add-authtoken 'SEU_TOKEN_DE_AUTENTICAÇÃO_NGROK'

## Notas:
- Certifique-se de que seu token de autenticação do ngrok seja válido.
- Os dados de exemplo fornecidos em dados são retornados em formato JSON ao acessar a rota inicial.
- Ajuste os dados e rotas conforme necessário para os requisitos da sua aplicação.
