# Aplicando Transfer Learning em Redes Neurais
## Objetivo - Descrição em English 🇺🇸
O projeto apresenta um estudo de caso focalizado em duas Redes Neurais Convolucionais (CNNs) destinadas à classificação de imagens, abordando diferentes estratégias de construção. Uma das CNNs é desenvolvida integralmente "do zero", enquanto a segunda adota Transfer Learning, aproveitando uma rede pré-treinada. O objetivo é criar modelos eficazes para a classificação de imagens de gatos e cachorros.

## Visão Geral
### 1° abordagem 

Na abordagem "do zero", a primeira CNN é construída com camadas convolucionais, de pooling e densas, sendo treinada especificamente para discernir entre imagens de gatos e cachorros. Este processo envolve a definição detalhada de arquitetura e parâmetros, buscando extrair características discriminativas.

### 2° abordagem
Por outro lado, a segunda CNN adota Transfer Learning, uma estratégia que capitaliza o conhecimento previamente adquirido por uma rede pré-treinada. Nessa abordagem, partes da rede são congeladas, enquanto as camadas finais são ajustadas para a tarefa específica de classificar imagens de gatos e cachorros. A técnica visa otimizar o aproveitamento de representações úteis já aprendidas pela rede pré-existente.

### Avaliação
Ambos os modelos são avaliados em sua capacidade de distinguir eficientemente entre as duas classes de animais. A análise inclui métricas de desempenho como acurácia e perda, buscando comparar os resultados obtidos pelas diferentes abordagens.

### Execução do Projeto
Para executar este projeto, basta instalar as bibliotecas presentes no arquivo 'requirements.txt' ou fazer o upload do arquivo transfer_learning.ipynb no Goggle Colab.

### Contribuições
Contribuições são bem-vindas! Se você identificar melhorias, problemas ou tiver sugestões, sinta-se à vontade para contribuir para este projeto.

# Applying Transfer Learning to Neural Networks
## Objective - Description in Portuguese 🇧🇷
The project presents a case study focused on two Convolutional Neural Networks (CNNs) intended for image classification, addressing different construction strategies. One of the CNNs is developed entirely "from scratch", while the second adopts Transfer Learning, taking advantage of a pre-trained network. The goal is to create effective models for classifying images of cats and dogs.

##Overview
### 1st approach

In the "from scratch" approach, the first CNN is built with convolutional, pooling and dense layers, being specifically trained to discriminate between images of cats and dogs. This process involves a specific definition of architecture and parameters, seeking to extract discriminative characteristics.

### 2nd approach
On the other hand, the second CNN adopts Transfer Learning, a strategy that capitalizes on knowledge previously acquired by a pre-trained network. In this approach, parts of the network are frozen, while the final layers are tuned for the specific task of cat and dog image classification. The technique aims to optimize the use of useful representations already learned by the pre-existing network.

### Assessment
Both models are evaluated on their ability to efficiently distinguish between the two classes of animals. The analysis includes performance analyzes such as accuracy and loss, seeking to compare the results obtained by different approaches.

### Project Execution
To run this project, simply install the libraries present in the 'requirements.txt' file or upload the transfer_learning.ipynb file to Goggle Colab.

### Contributions
Contributions are welcome! If you identify improvements, problems or suggestions, please feel free to contribute to this project.
