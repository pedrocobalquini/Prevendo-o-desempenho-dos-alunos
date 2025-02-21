# Prevendo o desempenho dos alunos

## Sobre o projeto
O conjunto de dados fornecido é uma representação sintética do desempenho dos alunos, projetado para imitar cenários do mundo real. Ele leva em consideração diversos fatores como hábitos de estudo, padrões de sono, histórico socioeconômico e frequência às aulas.

O projeto desenvolvido visa prever o desempenho dos alunos com base nos fatores mencionados. O objetivo é construir um modelo de aprendizado de máquina que possa prever as notas dos alunos com base nos dados disponíveis.

Caso queira explorar outros projetos, acesse meu portfólio pessoal, que contém todos os meus projetos: 

https://pedrocobalquini.framer.website/

## Etapas do projeto
1 - Análise Exploratória de Dados (EDA)

2 - Visualização dos dados numéricos

3 - Modelos de Machine Learning

4 - Comparações entre os resultados

## Tecnologias e bibliotecas utilizadas
- Python
- pandas
- matplotlib
- seaborn
- numpy
- scikit-learn

## Melhorias
O principal foco das melhorias está nos modelos de Machine Learning. Seria interessante utilizar outras métricas para avaliar o desempenho geral do modelo.

## Conclusão
Todos os modelos utilizados neste projeto, com seus respectivos resultados.
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
