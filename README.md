# energypass

Este projeto foi desenvolvido para o NAVI Tech Journey e apresenta um modelo de negócio que incentiva a modernização do setor energético brasileiro.
O projeto tem como fundamento a eliminação das barreiras de crescimento no setor de geração de energia distribuída e compartilhada. Os dois tópicos
centrais do trabalho cosistem em diminuir a desconfiança no setor e o risco de inadimplência.

A abordagem tecnológica do projeto é feita por meio de duas áreas: a digitalização da contratação do serviço e do controle do consumo energético através
de um site e a aplicação de ciência de dados na mensuração de índices de sustentabilidade, de previsões de eficiência energética dos sistemas de geração
de energia solar e de inserção do cliente no mercado livre de energia.

Com base no histórico de consumo mensal dos clientes, estabelecemos um valor médio para calcular o numero mais adequado de placas para arrendamento, tendo como objetivo um saldo anual de energia excedente igual a 0, isto é, o modelo ideal visa que o cliente produza tudo e apenas aquilo que consome (em energia).

O repositório do projeto conta com códigos em Python para análise do perfil de consumo e do cálculo de arrendamento de energia para o cliente, além de
códigos em R para análise de séries temporais da geração de energia em células fotovoltaicas no estado de São Paulo, visando prever a eficiência das
geradores por meio de modelos estatísticos. Há também a estrutura do site em HTML e CSS, o qual visa trazer uma interação simplificada e minimalista 
ao cliente por meio da facilidade de contratação do serviço.

A série temporal da produção de energia visa a previsão de quanto é produzido em função da época do ano. Um modelo complexo envolveria o estudo meteorológico diário para previsão, visando obter a energia produzida como função de parâmetros como umidade e movimentação de massas de ar recentes.

Vale dizer que utilizamos uma base de dados real do histórico de consumo de energia de uma residência e dos valores de produção energética das geradoras
solares de SP.
