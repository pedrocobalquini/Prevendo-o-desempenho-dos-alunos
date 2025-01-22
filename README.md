# Sobre o Projeto:

O conjunto de dados fornecido é uma representação sintética do desempenho dos alunos, projetado para imitar cenários do mundo real. Ele leva em consideração diversos fatores como hábitos de estudo, padrões de sono, histórico socioeconômico e frequência às aulas.

O projeto desenvolvido visa prever o desempenho dos alunos com base nos fatores mencionados. O objetivo é construir um modelo de aprendizado de máquina que possa prever as notas dos alunos com base nos dados disponíveis. 

# Etapas do projeto

1 - Análise Exploratória de Dados (EDA)

2 - Visualização dos dados numéricos

3 - Modelos de Machine Learning

4 - Comparações entre os resultados

# 1 - Análise Exploratória de Dados (EDA)

Nesta primeira etapa foram visualizados os dados para ter uma noção dos valores de cada variável, sabendo quais poderiam ter valores nulos, porém não precisou ser feito nada para alterar os dados.

# 2 - Visualização dos dados numéricos

Nesta etapa foram os dados numéricos do conjunto para observar por um histograma como estão divididos. Em sequência para visualizar possíveis outliers.

# 3 - Modelos de Machine Learning

## 3.1 - Linear Regression

O primeiro dos quatro modelos utilizados no projeto. Como resultado, o Coeficiente de determinação foi de 74.52% e o Mean Squared Error (MSE) foi de 19.91%.

## 3.2 - MLP Regressor

O segundo dos quatro modelos utilizados no projeto. O valor do max_iter foi alterado para 2500 para conseguir o melhor resultado deste modelo. Como resultado, o Coeficiente de determinação foi de 97.27% e o Mean Squared Error (MSE) foi de 2.14%.

## 3.3 - Random Forest Regressor

O terceiro dos quatro modelos utilizados no projeto. O valor do max_depth foi alterado para 10 para conseguir o melhor resultado deste modelo. Como resultado, o Coeficiente de determinação foi de 97.98% e o Mean Squared Error (MSE) foi de 1.58%.

## 3.4 - KNeighbors Regressor

O último dos quatro modelos utilizados no projeto. O valor do n_neighbors foi alterado para 6 para conseguir o melhor resultado deste modelo. Como resultado, o Coeficiente de determinação foi de 97.98% e o Mean Squared Error (MSE) foi de 5.53%.

# 4 - Conclusão
<body>
    <table>
        <tr>
            <th>Modelos</th>
            <th>Regressão Linear</th>
            <th>MLPRegressor</th>
            <th>Random Forest</th>
            <th>KNN</th>
        </tr>
        <tr>
            <td>Coeficiente de determinação</td>
            <td>74.52%</td>
            <td>97.27%</td>
            <td>97.98%</td>
            <td>97.98%</td>
        </tr>
        <tr>
            <td>Mean Squared Error (MSE)</td>
            <td>19.91%</td>
            <td>2.14%</td>
            <td>1.58%</td>
            <td>5.53%</td>
        </tr>
    </table>
</body>





















