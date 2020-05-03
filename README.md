# Modelos de Heterocedasticidade Condicional

O repositório contém o código em R e um PDF da aplicação de alguns modelos de heterocedasticidade condicional. Com base nos fatos estilizados foi investigado a presença de variância condicional na série do retorno da empresa VALE.SA. Foi utilizado o modelo SARIMA para modelar o retorno da empresa e foram utilizados outros sete modelos de heterocedasticidade condicional. Os modelos utilizados foram: GARCH (onde as inovações se distribuem como uma normal, uma t e uma t com skew), IGARCH, GARCHM, EGARCH e TGARCH. Os scripts dos últimos quatro modelos foram obtidos no endereço eletrônico do Prof. Ruey Tsay.

A conclusão do trabalho foi que o modelo que melhor se ajustou, e que foi possível medir, foi o modelo GARCH com distribuição t para as inovações.


Fontes: 
Tsay, Ruey. An introduction to Analysis of Financial Data with R.
Tsay, Ruey. Analysis of Financial Time Series.
Nicolau, João. Modelação De Séries Temporais Financeiras.
