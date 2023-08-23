# Detecção de Fraude em Cartões de Crédito

<p align="center">
  <img width="460" height="300" src="https://github.com/Rafael-Salomao/Deteccao_de_Fraude_em_Cartoes_de_Credito/blob/7d9480d80bf59d42c1ff0578c4cd4f8695cd1f72/imagem1.jpg">
</p>

## 1.0 Introdução

Neste projeto, iremos abordar o problema das fraudes em cartões de crédito, uma das principais preocupações das instituições financeiras como bancos e fintechs. Apenas no Brasil, cerca de 12,1 milhões de pessoas já foram vítimas de algum tipo de fraude financeira no último ano. Traduzindo em valores, de acordo com o Serasa Experian, no ano de 2021 foram registradas 4,1 milhões de movimentações suspeitas de fraudes, no Braisil. Sendo que, esse número mostra um aumento de 16,8% em relação ao acumulado de 2020. 

Dentre essas fraudes, aquelas envolvendo cartões de crédito são de grande relevância, uma vez que a sua não-detecção acaretará em prejuízos consideráveis, tanto para o consumidor quanto para a instituição financeira.

## 2.0 Qual problema foi resolvido

O objetivo do presente projeto foi identificar clientes fraudadores em operações de cartão de crédito.

## 3.0 Como foi resolvido

Foram obtidos informações de uma base de dados de clientes de uma instituição financeira. A partir desses dados, foi desenvolvido um modelo estatístico de classificação para encontrar a probabilidade de um cliente ser um potencial fraudador ou não. Com essas informações, foi possível classificar cada cliente como faudador ou não.

## 4.0 Tecnologias utilizadas

- Imblearn & Under_sampling
- Scikitplot 
- Sklearn
- Pandas
- Numpy 
- Seaborn
- Matplotlib
- Pyplot 


## 5.0 Resultados obtidos

Foi utilizada a métrica AUC ROC, que mostra a relação entre a taxa de verdadeiros positivos e a taxa de falsos positivos. Para o modelo de Regressão Logística desenvolvido, a AUC ROC teve uma eficácia de 94%.

Junto a isso, também foi feito o plot da matriz de confusão, onde pode-se aferir que a quantidade de entradas, classificadas fraudulentes e que o modelo identificou como transação normal - ou seja, valores falso positivos -, foi de 4%. Além disso, 9% das previsões são falso negativos, que correspondem a quantidade de transações "duvidosas" em que o modelo classifica como fraudulenta por engano.

## 6.0 Implementações futuras/ evoluções

O resultado encontrado foi satisfatório com o esperado para a apresentação do modelo de Regressão Logística utilizado. Contudo, é fáctivel a manipulação de diferentes parâmetros no modelo constatado, como também, pode-se implementar outros modelos de classificação a fim de comparar e encontrar uma melhor eficácia nos valores finais.
