## Regressão Linear Simples

### O que é?
- A regressão linear simples é uma técnica estatística usada para modelar a relação entre duas variáveis, onde uma é considerada a variável independente (X) e a outra é considerada a variável dependente (Y).

### Como funciona?
- A regressão linear simples é uma técnica estatística usada para modelar a relação entre duas variáveis, onde uma é considerada a variável independente (X) e a outra é considerada a variável dependente (Y).


### Fórmula
A regressão linear simples é representada pela seguinte equação:

Y = β₀ + β₁X + ε

Onde:
- Y é a variável dependente
- X é a variável independente
- β₀ é o intercepto (valor de Y quando X = 0)
- β₁ é o coeficiente de inclinação (mudança em Y para cada unidade de mudança em X)
- ε é o termo de erro (representa a variabilidade não explicada pelo modelo)

<p align="center">
  <img src="https://latex.codecogs.com/png.latex?\dpi{150}&space;\bg_white&space;Y&space;=&space;\beta_0&space;&plus;&space;\beta_1X&space;&plus;&space;\varepsilon" alt="Fórmula da Regressão Linear Simples">
</p>

Esta fórmula descreve uma linha reta que melhor se ajusta aos dados, minimizando a soma dos quadrados dos resíduos (diferenças entre os valores observados e previstos).


### Fórmula do Coeficiente Angular (β₁)

O coeficiente angular β₁ na regressão linear simples pode ser calculado usando a seguinte fórmula:

<p align="center">
  <img src="https://www.alura.com.br/artigos/assets/desvendando-a-regressao-linear/imagem6.png?\dpi{150}&space;\bg_white&space;\beta_1&space;=&space;\frac{\sum_{i=1}^{n}(x_i&space;-&space;\bar{x})(y_i&space;-&space;\bar{y})}{\sum_{i=1}^{n}(x_i&space;-&space;\bar{x})^2}" alt="Fórmula do Coeficiente Angular">
</p>

Onde:
- β₁ é o coeficiente angular
- x_i são os valores individuais da variável independente
- y_i são os valores individuais da variável dependente
- x̄ é a média dos valores de x
- ȳ é a média dos valores de y
- n é o número total de observações

Esta fórmula calcula a inclinação da linha de regressão, representando a mudança em Y para cada unidade de mudança em X.

### Fórmula do Coeficiente Linear (β₀)

O coeficiente linear β₀ na regressão linear simples pode ser calculado usando a seguinte fórmula:

<p align="center">
  <img src="https://latex.codecogs.com/png.latex?\dpi{150}&space;\bg_white&space;\beta_0&space;=&space;\bar{y}&space;-&space;\beta_1\bar{x}" alt="Fórmula do Coeficiente Linear">
</p>

Onde:
- β₀ é o coeficiente linear
- ȳ é a média dos valores de y
- β₁ é o coeficiente angular
- x̄ é a média dos valores de x

Esta fórmula calcula o intercepto da linha de regressão, representando o valor de Y quando X é igual a zero.
