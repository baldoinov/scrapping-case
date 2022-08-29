# Case de Web Scrapping e Análise de Dados

Esse repositório foi criado para guardar um case realizado em agosto/2022. O case contém as seguintes partes:

## Programação:

1. Web-Scrapping

> Colete o preço médio (ou seja, de múltiplos produtos de marcas diferentes, por exemplo) de uma televisão de 55 polegadas para cada Estado Brasileiro assim como o respectivo custo do frete para apenas um CEP aleatório situado em uma capital para cada Estado.

Considere apresentar:

- Uma tabela com as estatísticas descritivas do preço médio da televisão assim como o custo de frete para as capitais.
- Um gráfico interativo em ``Plotly`` relacionando a dispersão de preços (eixo Y) e fretes (eixo X).
- Qual insight você poderia extrair sobre o que encontrou?

2. Econometria

> Colete séries do Google Trends (usando a biblioteca ``pytrends``) para os termos "Stocks", "Risk", "Recession", "Inflation" e "Unemployment". Utilize dados mensais de 2010 até 2022.

Apresente:

- Um gráfico interativo em ``Plotly`` apresentando a relação da ["Curva de Phillips"](https://www.economist.com/graphic-detail/2017/11/01/the-phillips-curve-may-be-broken-for-good): Inflação (eixo Y) e Desemprego (eixo X) no mesmo gráfico (``scatter plot``) e uma reta de ajuste relacionando as duas séries (i.e. regrida Inflação contra Desemprego utilizando OLS e plote a reta oriunda da equação ajustada à regressão $Y = bX + u$).
- Um gráfico interativo usando a biblioteca ``Plotly`` plotando a evolução dos termos (i.e. coloque todos os termos no mesmo gráfico usando a métrica de comparação absoluta (e não relativa) para os seguintes países: Estados Unidos, México, Colômbia, Vietnam, Singapura e África do Sul.
  - Nesse gráfico, inclua um botão para mudar o país e mostrar a diferente evolução das séries.
- Insights extraídos desse exercício.

## Insights

> Explique como você coletaria as informações do site que contém o histórico do número de vôos deste aeroporto disponível no site:
> https://flightaware.com/live/airport/ZSPD
> 
> *Não precisa fazer código, apenas explicar!*

Responda:

- Como você utilizaria esses dados no Mercado Financeiro? 
- Para que ele seria interessante? 
- Como você apresentaria os dados que coletaria desses gráficos de maneira intuitiva e aplicável ao seu problema?

## Questão Bônus

> Escolha dois modelos estatísticos abaixo e explique como implementá-los e quais suas limitações para a projeção de séries temporais:
> 
> *ARIMA, SARIMA, VAR, LASSO, RIDGE, Random Forest, Neural Networks*
> 
> *Não precisa fazer código, apenas explicar!*

***