# Aprendizado-de-Maquina-PROVIR

Aqui destaco a prática que desenvolvi durante o curso de aprendizado de máquina onde fui bolsista do Programa de Capacitação e Desenvolvimento em Visão Computacional, Robótica e Aprendizado de Máquina - PROVIR.

Considerando a base de dados Fires disponível em http://archive.ics.uci.edu/ml/datasets/Forest+Fires , que apresenta dados meteorológicos para
previsão de incêndios florestais em um parque, e que é composta por 517 objetos e 13 atributos. Foram utilizados cinco atributos, sendo dois categóricos (Mês e Dia) e três numéricos (DMC, DC e ISI).

Com esses parâmetros aplicamos técnicas como Distribuições de frequência, Visualização de dados como: (i) histogramas das frequências relativas e absolutas; (ii) gráfico de polígonos; (iii) gráfico de setores; (iv) gráfico de Pareto; (v) gráfico de dispersão entre cada dois atributos, ou seja, DMC x Dia, DMC x Mês, DMC x DC, DMC x ISI, DC x Dia, DC x Mês, DC x ISI, ISI x Dia, ISI x Mês, Dia x Mês.
 
Também aplicamos Medidas Resumo com tendência central (média, moda (quando fosse o caso), ponto médio e mediana), dispersão (amplitude, desvio padrão, variância,
coeficiente de variação) e forma (assimetria e curtose), para cada um dos cinco atributos (Dia, Mês, DMC, DC e ISI).
 
Também aplicamos Diagrama de Caixa (box plot) e Medidas de Associação.

Link dos códigos no Google Colab: https://colab.research.google.com/drive/1iwA49R9_Uvhi--GBXXkOPWBKEnoYesh-?usp=sharing
