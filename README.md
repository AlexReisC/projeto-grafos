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

## Explicação em vídeo
Explicação do projeto feita pelos membros da equipe em partes:
- [Alex - Classe Bairro e funcionamento geral](https://drive.google.com/file/d/1MfvVR18gPjKfx1hAGKHcehvQFsUs-BDC/view?usp=drive_link)
- Stéfani - Classes PontoDeColeta() e CarroDoLixo()
   - [PARTE 1](https://drive.google.com/file/d/1YGIOB8JDWMjEmzCBDZPYDL4m9WVKzhEX/view?usp=drivesdk)
   - [PARTE 2](https://drive.google.com/file/d/1YQ4CHIWqybFBfKlEHNlMXtIHo65NiPUm/view?usp=drivesdk)
- [Henrique - Classe CentroDeZoonozes](https://drive.google.com/file/d/1K-zh-2A2WL8mF4riqPPUy3T-YrU1zO-_/view?usp=sharing)

## Licença
Este projeto é livre para uso e modificação conforme necessário. 😊