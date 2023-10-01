# atividade-pond-sem9
## Introdução
Ao utilizar modelos de Machine Learning em diversas aplicações um problema também é gerado. Os dados que anteriorimente alimentavam o modelo com exatidão, podem começar a não corresponder de forma correta ao que realmente está estipulado no atual cotidiano. Geralmente essa desatualização com a realidade resulta no concept drift, que retrata justamente a deteriorização da precisão do sistema resultante da desatualização dos dados.

## Solução
No meu ponto de vista, a solução ideal seria a implementação de uma pipeline ETL, responsável pela coleta, transformação e carregamento dos dados, porém em conjunto a essa, um sistema de verificação da acurácia e confiabilidade desses novos dados. Caso apresente melhora significativa no modelo com os novos dados apurado, seria implementado definitivamente no dataset do modelo em produção. Segue a arquitetura que ilustra a ideia:
