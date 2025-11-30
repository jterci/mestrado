# Trabalho 01 – Implementação do Backpropagation em Python (MLP)

Notebook: [`trabalho01_mlp_backprop_jtg.ipynb`](trabalho01_mlp_backprop_jtg.ipynb)

Este trabalho implementa e testa um **Multi Layer Perceptron (MLP)** "na mão", em Python/NumPy,
e compara o resultado com o MLP implementado no **Scikit-Learn**.

## Descrição resumida

- Implementação de um MLP genérico, com parâmetros para:
  - quantidade de camadas;
  - número de neurônios em cada camada;
  - função de ativação em cada camada;
- Treinamento em um conjunto de dados sintético (`make_moons`);
- Comparação de desempenho com `MLPClassifier` do Scikit-Learn;
- Visualização:
  - curva de erro ao longo das épocas;
  - fronteira de decisão do MLP implementado e do MLP do Scikit-Learn.

## Como executar

1. Faça o download do notebook ou clone o repositório.
2. Abra o arquivo `trabalho01_mlp_backprop_jtg.ipynb` no Jupyter ou Google Colab.
3. Execute as células na ordem em que aparecem.

## Referência aos notebooks originais do professor

Durante o desenvolvimento deste trabalho, foi utilizado como material de apoio conceitual o
repositório de aulas em:

- https://github.com/fboldt/aulasann

Em particular:

- `aula4a_Single_Hidden_Layer_Backpropagation.ipynb`  
  (link informado, mas o arquivo não estava disponível para acesso no momento da realização do trabalho)

- `aula05b_single_hidden_layer.ipynb`  
  usado para revisar a ideia geral de backpropagation em uma rede com uma camada escondida.

A comparação com o `MLPClassifier` do Scikit-Learn foi implementada pelo autor, seguindo o que foi
visto em aula sobre o uso do MLP da biblioteca como padrão de comparação.
