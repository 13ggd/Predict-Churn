# Desafio
## Gabriel Garcia Deitos

Projeto realizado com o objetivo de prever o churn (abandono de clientes) de um banco de dados fictício de uma instituição financeira. utilizando o primeiro dataset chamado Abandono_clientes composto por 10000 linhas e 13 colunas de informação (features), sendo uma coluna “Exited” composta por dados binários: 1 se o cliente abandonou o banco, 0 se não, para prever o segundo dataset que possui 1000 linhas e 12 colunas e não possui a coluna “Exited”.

# Pré requisitos
* [Pandas](https://pandas.pydata.org/)
* [Numpy](https://numpy.org/)
* [Matplotlib](https://matplotlib.org/)
* [Seaborn](https://seaborn.pydata.org/)
* [Scikit-Learn](https://scikit-learn.org/)

* [Jupyter Notebook](https://jupyter.org/)

Eu recomendo baixar o [Anaconda](https://www.anaconda.com/) (Python distribution), que já tem todas as bibliotecas instaladas e o jupyter notebook. Ou usar o [Google Colab](https://colab.research.google.com/) que é só abrir o arquivo jupyter notebook nele.

# Resumo

Descrevi graficamente alguns dados disponiveis, pois é importante ver com que tipo de cliente está sendo lidado, para que haja meios baseados no perfil majoritario deles para fazer com que os mesmos não saiam da instituição financeira

Previ o churn a partir do algoritmo de regressão logística pelo fato de apresentar menos falsos negativos no problema, o que ao meu ver é mais importante para ter tempo de conter os clientes de alguma forma na empresa

Ao final, gerei um arquivo csv com duas colunas, rowNumber e predictedValues
