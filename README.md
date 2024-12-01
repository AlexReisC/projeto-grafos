# Gerenciamento de Coleta de Lixo e Controle de Animais em Lagoa Cheia

Este projeto simula um sistema de gerenciamento de coleta de lixo e controle de animais em um bairro fictício, chamado Lagoa Cheia, representado como um grafo. Ele calcula o número mínimo de caminhões e funcionários necessários para realizar a coleta em até 8 horas, além de gerenciar a movimentação de animais utilizando carrocinhas do centro de zoonoses.

## Pré-requisitos

1. **Python 3.8 ou superior**  
Certifique-se de ter o Python instalado no seu sistema. [Download Python](https://www.python.org/downloads/)

2. **Bibliotecas Necessárias**  
Este projeto utiliza a biblioteca `networkx` e bibliotecas padrão do Python. Para instalar, execute:
   ```bash
   pip install networkx
   ```
3. IDE de sua preferênia ou VS Code.

## Como Executar
1. **Clone o repositório ou faça download**
   ```bash
   git clone https://github.com/AlexReisC/projeto-grafos.git
   cd projeto-grafos
   ```
2. **Configure o arquivo de entrada** `grafo.txt`
3. **Execute o Programa**
   
   Pelo terminal:
   ```bash
   python main.py
   ```
   **Ou simplesmente execute o arquivo `main.py` na sua IDE.**

## Como Funciona
O programa lê o arquivo de entrada para criar um grafo que representa o bairro.

Caminhões de lixo percorrem os pontos coletando o lixo e, se necessário, compactando ou descarregando no aterro sanitário.

Carrocinhas do centro de zoonoses são enviadas para recolher animais detectados nos pontos de coleta.

O programa calcula e exibe o número mínimo de caminhões e funcionários necessários.

## Licença
Este projeto é livre para uso e modificação conforme necessário. 😊