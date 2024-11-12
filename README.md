# Regressão Linear

A Regressão Linear é um método estatístico que tenta modelar a relação entre uma variável dependente (variável-alvo) e uma ou mais variáveis independentes (variáveis explicativas) através de uma linha reta. Esse método é muito utilizado em Machine Learning e análise de dados para fazer previsões com base em dados históricos.

## Introdução

Na Regressão Linear Simples, a relação entre duas variáveis é representada pela fórmula da reta:

\[
y = \beta_0 + \beta_1 x + \varepsilon
\]

onde:
- \( y \) é a variável dependente (o valor que queremos prever).
- \( x \) é a variável independente.
- \( \beta_0 \) é o intercepto (constante).
- \( \beta_1 \) é o coeficiente de inclinação da reta, que indica a mudança em \( y \) para cada unidade de \( x \).
- \( \varepsilon \) é o termo de erro, representando a diferença entre os valores observados e os valores previstos pelo modelo.

## Objetivo

O objetivo da Regressão Linear é encontrar os valores de \( \beta_0 \) e \( \beta_1 \) que minimizem a soma dos quadrados dos erros (diferença entre os valores previstos e os observados). Esse processo é conhecido como **Minimização dos Erros Quadráticos**.

### Erro Quadrático Médio (MSE)

Para medir a qualidade do ajuste do modelo, podemos utilizar o **Erro Quadrático Médio (MSE)**, dado por:

\[
\text{MSE} = \frac{1}{n} \sum_{i=1}^{n} (y_i - \hat{y}_i)^2
\]

onde:
- \( y_i \) é o valor real.
- \( \hat{y}_i \) é o valor previsto pelo modelo.
- \( n \) é o número total de observações.

## Tipos de Regressão Linear

### 1. Regressão Linear Simples
   - A Regressão Linear Simples envolve apenas uma variável independente para prever a variável dependente.
   - Exemplo: prever o preço de uma casa com base na sua área em metros quadrados.

### 2. Regressão Linear Múltipla
   - Na Regressão Linear Múltipla, usamos mais de uma variável independente para prever a variável dependente.
   - Exemplo: prever o preço de uma casa considerando área, localização e número de quartos.

## Assumptions da Regressão Linear

Para que a Regressão Linear funcione corretamente, algumas suposições precisam ser atendidas:
1. **Linearidade**: A relação entre as variáveis independentes e dependente é linear.
2. **Independência dos Erros**: Os resíduos devem ser independentes entre si.
3. **Homoscedasticidade**: A variância dos erros deve ser constante.
4. **Normalidade dos Erros**: Os resíduos devem seguir uma distribuição normal.

## Implementação em Python

Aqui está um exemplo básico de Regressão Linear usando a biblioteca `scikit-learn`


## Contato:
Se precisar de mais informações, entre em contato:

**Email: luciana.sampaio84@gmail.com**

LinkedIn: [Luciana Sampaio ](https://www.linkedin.com/in/luciana-sampaio/)

