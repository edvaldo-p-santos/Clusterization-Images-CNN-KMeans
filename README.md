# Images Clusterization with CNN and KMeans Model
Aplicação de um modelo de clusterização de imagens de mangas com K-Means Model fazendo pré-processamento com Convolutional Neural Network.

# Dados
Os dados foram coletas na "força bruta" com busca de imagens de mangas pela internet.

# Ferramentas Usadas
## Modelo VGG(16)
"VGG16 is a convolutional neural network model proposed by K. Simonyan and A. Zisserman from the University of Oxford in the paper “Very Deep Convolutional Networks for Large-Scale Image Recognition”." (https://neurohive.io/en/popular-networks/vgg16/)

Utilizamos esse modelo para pré-processamento das imagens. Com ele retiramos as features para utilizar no modelo KMeans.

## Modelo KMeans
Utilizamos o modelo KMeans para clusterizar as imagens de mangas.

Escolhemos 3 clusters com base nas nossa percepção de que as mangas poderiam ser segmentadas e nos dar melhores insights. Em caso onde não sabemos quantos clusters são o ideal, poderíamos utilizar o método Elbow e Índice de Silhouette.

# Resultados do Modelo e Interpretação
Plotamos 4 imagens de cada cluster para análise.

## Cluster 0
Nesse cluster podemos ver que prevaleceu mangas amarelas e aparentemente maduras.
![image](https://user-images.githubusercontent.com/56306657/121790104-596f0f80-cbb2-11eb-8d71-7d20eb71815f.png)


## Cluster 1
No Cluster 1 ficaram as mangas verdes.
![image](https://user-images.githubusercontent.com/56306657/121790114-6f7cd000-cbb2-11eb-98ca-f0f9e78050df.png)


## Cluster 2
E no Cluster 2 prevaleceu mangas vermelhas que poderíamos chamar de mangas para exportação.
![image](https://user-images.githubusercontent.com/56306657/121790128-989d6080-cbb2-11eb-8675-53ebfb53d8ae.png)


# Pontos Finais
É sempre bom lembrar que o modelo que apresentei a vocês é para simples demonstração da eficácia do modelo. Utilizamos dados pré-selecionados e na vida real a vida do cientista de dados pode ser bem mais difícil.
