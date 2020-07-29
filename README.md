# rocket_science-Inc_predict-_maintence
Rocket_Science Inc_predict _maintence


## Problema Description
### Link business Problem
https://sejaumdatascientist.com/o-projeto-de-machine-learning-para-o-seu-portfolio/

# Característica do Conjunto de Dados

O arquivo “train_FD001.txt” possui 26 colunas Cada linha desse conjunto de dados representa 1 ciclo de medições. As medições são feitas por 21 sensores e 3 valores de ajuste, como descrito nas colunas. Cada motor possui um ciclo máximo de medição, após esse ciclo máximo é esperado um número de ciclos até a falha do motor. Esse número de ciclos esperados até a falha é chamado de RUL ( Remaining Useful Life ). Por exemplo, o número máximo de ciclos do motor 01 é 192, como descrito na imagem abaixo. Após o ciclo 192, é esperado 112 ciclos até a falha. O valor 112 é o número de ciclos esperados até a falha ( RUL ). Esse valor pode ser encontrado no arquivo “RUL_FD001”, como na figura abaixo.

A primeira linha mostra um valor de 112 para RUL. Esse valor corresponde ao número de ciclos estimado, até a falha, para o motor 01. A segunda linha mostra um valor de 98 para RUL, que corresponde ao número de ciclos estimado, até falha, para o motor 02. E assim por diante. O seu objetivo como Data Scientist é prever o valor do RUL para os motores do conjunto de dados de teste “RUL_FD001.txt” e responder à essa pergunta.

*Quantos ciclos cada motor ainda possui até a falha?

## Roteiro Sugerido para a Resolução
Esse é o roteiro de resolução do desafio que eu sugiro:

Leia os 3 arquivos em um Jupyter Notebook e renomeia as colunas. Defina o tipo desse problema: Regressão, Classificação ou Clusterização. Faça testes Estatísticos procurando por incoerências nos dados. Crie novas variáveis para modelar melhor o fenômeno, se necessário. Verifique se as variáveis possuem o mesmo peso, em termos de importância, para o modelo. Aplique diferentes algoritmos de Machine Learning. Compare os algoritmos sob a mesma métrica de performance, a mais apropriada. Garanta que seu modelo não possui “Overfit”, ou seja, uma memorização ao invés de aprendizado. Escreva os valores de previsão do RUL e seu intervalo de confiança para cada motor do arquivo de teste. Escreve um breve explicação do raciocínio da sua solução.
