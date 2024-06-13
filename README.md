# A3-IA
Trabalho A3 de Inteligência Artificial pela Anhembi Morumbi Paulista, turno da manhã sexta-feira.

## Objetivo
Tratamento de uma base de dados, análise e criação de modelo de ML.

## Base e ML
A base escolhida foi a base "Car Features and MSRP" do site https://www.kaggle.com/datasets/CooperUnion/cardataset, com a ajuda de um código já feito em Random Forest (RFR), decidimos fazer uma análise mais profunda da base, dividindo-a em duas partes, carros "populares" e carros de luxo/performance/alta-performance e através disso verificamos como se comportava o algoritmo RFR e sua "precisão" de acordo com o score R2. Para comparação entre algoritmos, também optamos por utilizar da Regressão por K-Nearest Neighbors (KNN)

##Resultados
A base depois de tratada contava com mais valores nos carros de luxo.
Os histogramas mostraram que a faixa de preço para carros populares teve uma máxima de 50k dolares, enquanto nos de luxo chegavam em até 100k.
Também observamos com os histogramas que os carros de luxo tem muitas "categorias de mercado" (carro popular, luxo, performance, alta perfomance, combustível normal, hibrido...), onde há carros muito específicos com mais de 3~4 categorias de mercado.
Como esperado a base de dados com Random Forest, tanto para populares quanto de luxo, teve um score mais significativo e melhor que o algoritmo de knn, mesmo com uma quantidade de dados maior na base de luxo.
Concluímos que o KNN tem bons resultados, porém quando a base é muito densa (com grandes quantidades de valores) o RFR se mostrou um algoritmo com uma performance (score/precisão) melhor. Com a base dividida, 
