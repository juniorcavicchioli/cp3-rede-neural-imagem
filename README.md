# CP3 - Quem é esse Pokemon???

![](https://t2.tudocdn.net/182957?w=646&h=284)

## Vamos criar uma Pokedex

Neste checkpoint, vocês devem desenvolver um modelo de classificação de imagens utilizando deep learning com Keras e TensorFlow para identificar Pokémon. O modelo deve ser baseado em transfer learning, aproveitando o conhecimento adquirido por uma rede neural pré-treinada para acelerar o processo de aprendizado e melhorar a acurácia.


## Informações do grupo

Este projeto poderá ser feito com o `grupo do challenge`.

| Nome dos Integrantes     | RM             | Turma   |
| :----------------------- | :------------- | :-----: |
| Integrante 1             | RM             |         |
| Integrante 2             | RM             |         |
| Integrante 3             | RM             |         |
| Integrante 4             | RM             |         |
| Integrante 5             | RM             |         |

## Sobre os dados


O conjunto de dados consiste em imagens de diferentes Pokémons, categorizadas por suas respectivas classes. Os dados foram obtidos a partir do ``huggingface``. 

link para o dataset: [https://huggingface.co/datasets/keremberke/pokemon-classification](https://huggingface.co/datasets/keremberke/pokemon-classification)

O desenvolvimento deste projeto envolve os conceitos aprendidos ao longo do semestre. Durante o desenvolvimento se inspire na modelo ``CRISP-DM`` para orientar seu projeto de visão computacional.


## Rubrica 

Os critérios de avaliação do projeto será conforme a rubrica.

- R1: Carregamento e compreensão do dataset (Até 1 ponto) - Familiarize-se com o conjunto de dados, verificando a quantidade de imagens, a resolução das imagens, a distribuição das classes e outras características relevantes.

- R2: Preparação de Dados (Até 1 ponto) - Prepare os dados para o treinamento do modelo, incluindo redimensionamento das imagens para um tamanho padrão, normalização dos valores de pixel, e divisão do conjunto de dados em conjuntos de treino, validação e teste.

- R3: Desenvolvimento do Modelo (Até 1 ponto) - Implemente o modelo de classificação de imagens utilizando Keras e TensorFlow. Aplique transfer learning com uma rede neural pré-treinada(ResNet, InceptionV3, VGG16, MobileNetV2, etc...), faça as adaptações na arquitetura conforme necessário para o problema de classificação de Pokémon. Você pode, se necessário, adicionar camadas adicionais, como Dropout e Dense, para melhorar o desempenho do modelo.

- R4: Treinamento e Teste do Modelo (Até 3 ponto) - Treine o modelo utilizando o conjunto de treino, faça os ajustes dos hiperparâmetros como taxa de aprendizado, número de épocas e tamanho do batch conforme necessário. Monitore o desempenho do modelo no conjunto de validação para ``evitar overfitting``. Após o treinamento, teste o modelo no conjunto de teste e avalie o desempenho em termos de métricas como acurácia, precisão, recall e F1-score. De forma semelhante a realizada nos laboratórios em aula.

- R5: Deploy em ``localhost com Flask`` (Até 4 ponto) - Demonstrar o funcionamento da aplicação rodando em localhost utilizando Flask. Utilize como base, mas não se limite apenas a ele, o repositório [https://github.com/arnaldojr/deploy-modelos-flask](https://github.com/arnaldojr/deploy-modelos-flask). Basicamente deve ser seguido os passos: Salvar o modelo treinado em disco; Criar um aplicativo Flask simples que carregue o modelo e permita fazer inferências a partir de imagens enviadas através de requisições HTTP; Por fim, testar o aplicativo Flask localmente.

- R6: Deploy ``em NUVEM`` (Até 5 pontos *EXTRA) -  Essa rubrica é opcional. Realizar o deploy do modelo em uma aplicação na nuvem. Pode usar o conhecimento adquirido na matéria de cloud (Azure, Docker...) ou fazer o deploy usando uma plataforma como [Railway](https://railway.app/). Para obter pontuação extra.


Nota_final = R1 + R2 + R3 + R4 + R5 + R6
