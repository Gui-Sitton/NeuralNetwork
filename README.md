# NeuralNetwork

## Intro
The Boa Semente supermarket chain would like to explore whether Data Science can help them follow alcohol laws, ensuring that they don't sell alcohol to minors. You are asked to carry out this assessment, so as you get to work, keep the following in mind:
Stores are equipped with cameras in the checkout area that are triggered when a person is buying alcohol
Computer vision methods can be used to determine a person's age from a photo
The task is then to build and evaluate a model to verify people's ages
You will have a set of photographs of people with their ages indicated.

### Project instructions
* Perform an exploratory data analysis to get an overall impression of the data set.
* Train and evaluate the model (needs to be done on the GPU platform).
* Combine your code, output and findings (from the previous points) in the final Jupyter notebook.
* Draw conclusions from the model evaluation, add them to the notebook.


## Libraries used

import pandas as pd

import warnings

warnings.filterwarnings("ignore", category=RuntimeWarning)

from tensorflow.keras.preprocessing.image import ImageDataGenerator

import plotly.express as px

import tensorflow as tf

from tensorflow.keras.applications.resnet import ResNet50

from tensorflow.keras.models import Sequential

from tensorflow.keras.layers import GlobalAveragePooling2D, Dense, Dropout, Flatten

from tensorflow.keras.optimizers import Adam

import inspect

## Conclusion

mae: 7.9925: MAE stands for Mean Absolute Error. It is an evaluation metric that indicates the average absolute difference between the model's predictions and the actual values. An MAE value of 7.9925 indicates that, on average, the model's predictions have an absolute error of approximately 7.99 units in relation to the actual values. The aim is to minimize this metric as much as possible

Test MAE: 7.9925: This is the MAE metric calculated on the test set, which represents how well the model generalizes to data that was not used during training. An MAE value of 7.9925 indicates that, on average, the model's predictions on the test set have an absolute error of approximately 7.99 units with respect to the actual values.

The ResNet-50 model is making progress in training, with the loss decreasing over the epochs.

**Model passes, mae below 8**

# Rede Neural

## Introdução
A rede de supermercados Boa Semente gostaria de explorar se a ciência de dados pode ajudá-la a seguir as leis sobre bebidas alcoólicas, garantindo que não vendam bebidas alcoólicas para menores de idade. Você foi solicitado a realizar essa avaliação, portanto, ao começar a trabalhar, tenha em mente o seguinte:
As lojas são equipadas com câmeras na área do caixa que são acionadas quando uma pessoa está comprando álcool
Métodos de visão computacional podem ser usados para determinar a idade de uma pessoa a partir de uma foto
A tarefa é, então, criar e avaliar um modelo para verificar a idade das pessoas
Você terá um conjunto de fotografias de pessoas com suas idades indicadas.

### Instruções do projeto
* Realizar uma análise exploratória de dados para obter uma impressão geral do conjunto de dados.
* Treinar e avaliar o modelo (precisa ser feito na plataforma GPU).
* Combine seu código, resultados e descobertas (dos pontos anteriores) no notebook Jupyter final.
* Tire conclusões da avaliação do modelo e adicione-as ao notebook.


## Bibliotecas usadas

import pandas as pd

importar warnings

warnings.filterwarnings("ignore", category=RuntimeWarning)

from tensorflow.keras.preprocessing.image import ImageDataGenerator

import plotly.express as px

import tensorflow as tf

from tensorflow.keras.applications.resnet import ResNet50

from tensorflow.keras.models import Sequential

from tensorflow.keras.layers import GlobalAveragePooling2D, Dense, Dropout, Flatten

from tensorflow.keras.optimizers import Adam

import inspect

## Conclusão

mae: 7,9925: MAE significa Mean Absolute Error (erro absoluto médio). É uma métrica de avaliação que indica a diferença absoluta média entre as previsões do modelo e os valores reais. Um valor de MAE de 7,9925 indica que, em média, as previsões do modelo têm um erro absoluto de aproximadamente 7,99 unidades em relação aos valores reais. O objetivo é minimizar essa métrica o máximo possível

MAE de teste: 7,9925: Essa é a métrica MAE calculada no conjunto de teste, que representa o grau de generalização do modelo para dados que não foram usados durante o treinamento. Um valor MAE de 7,9925 indica que, em média, as previsões do modelo no conjunto de teste têm um erro absoluto de aproximadamente 7,99 unidades com relação aos valores reais.

O modelo ResNet-50 está progredindo no treinamento, com a perda diminuindo ao longo das épocas.

**O modelo é aprovado, com mae abaixo de 8**

