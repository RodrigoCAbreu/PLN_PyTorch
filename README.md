# PLN_PyTorch
Neste Projeto será desenvolvido um modelo de deep learning para prever se um determinado tweet é sobre um desastre real ou não. Se for desastre a previsão deve ser 1. Caso contrário, 0.  

Cada amostra no conjunto de treino e teste tem as seguintes informações:  
- O texto de um tweet. 
- Uma palavra-chave desse tweet (embora isso possa estar em branco). 
- O local de onde o tweet foi enviado (também pode estar em branco). 

O pipeline desse projeto é composto por:  
* Limpeza e Pré-Processamento 
* Engenharia de Atributos 
* Modelo Embeddings de Palavras Pré-Treinado 
* Modelo de Deep Learning - Rede Neural Recorrente BiLSTM
