# Sistema de Recomendação de Imagens Semelhantes

Este projeto é um **sistema de recomendação** que permite ao usuário fazer upload de uma imagem (como uma bicicleta) e, a partir da imagem carregada, busca imagens semelhantes na internet utilizando a **API do Pexels**.

## Funcionalidades

- **Upload de Imagem**: Os usuários podem carregar uma imagem do seu dispositivo.
- **Busca de Imagens Semelhantes**: Utiliza a API do Pexels para buscar e exibir imagens relacionadas à consulta, com base na imagem carregada.
- **Visualização**: Exibe a imagem carregada ao lado das imagens semelhantes obtidas da Pexels, facilitando a comparação visual.

## Tecnologias Utilizadas

- **Python**: Linguagem de programação utilizada para o desenvolvimento do projeto.
- **TensorFlow**: Framework utilizado para carregar o modelo e potencializar a análise de imagens (pode ser adaptado se necessário).
- **API do Pexels**: Utilizada para buscar imagens na internet.
- **Matplotlib**: Biblioteca para visualização das imagens.

## Como Usar

### Pré-requisitos

1. Instale [Python](https://www.python.org/downloads/) (versão 3.6 ou superior).
2. Instale as dependências necessárias. Você pode usar `pip` para instalar as bibliotecas:

   bash

   pip install requests matplotlib

Configuração da API

Registre-se em Pexels e obtenha sua chave de API.

Substitua a chave de API no código:

PEXELS_API_KEY = 'YOUR_PEXELS_API_KEY'  # Substitua pela sua chave da Pexels

Execução do Projeto

Clone o repositório para o seu ambiente local:

git clone https://github.com/Cris-noscore/Sistema-de-recomendacao-por-imagens.git

cd Sistema-de-recomendacao-por-imagens

Inicie o script em Python:

python seu_script.py

Carregue uma imagem quando solicitado. O sistema buscará imagens semelhantes e as exibirá.

Exemplo de Uso

Após carregar a imagem, o sistema pode buscar por imagens semelhantes e você verá a imagem carregada junto com as imagens recomendadas da API do Pexels.
   
