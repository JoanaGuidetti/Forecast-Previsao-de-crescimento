# Forecast-Previsao-de-crescimento
## Previsão/Projeção de crescimento E-commerce (12 meses)

### Objetivo do projeto
Fazer a previsão crescimento das vendas dos próximos (12 meses).

A projeção de vendas, consiste em fazer o cálculo aproximado das vendas em determinado período no futuro, utilizando a análise de dados dos números das vendas realizadas em meses ou anos anteriores, e com isso fazer a projeção de crescimento do número de vendas no futuro. 
Primeira Etapa, foi entender como funciona o negócio, quais são os canais de aquisição de clientes da empresa.
Os clientes da empresa são obtidos através do tráfego orgânico e do tráfego pago.
No tráfego orgânico, temos clientes dos seguintes canais: site/blog e email.
No tráfego pago, temos clientes dos seguintes canais: Google Search, Google Display e Facebook.

### Para execução desse projeto, segui os seguintes passos:
Análise Exploratória;

Modelagem + Algoritmos;

Interpretação de Resultados obtidos.

### Métodos de previsão utilizados
Exponential Smoothing;

Regressão Linear;

### Métrica de acurácia utilizadas
Bias Forecast (consistent forecast error);

MAPE (Mean Absolute Percentage);

MAE (Mean Absolute Error);

RSME (Root Mean Squared Error);

O modelo de previsão que teve o melhor resultado foi a Regressão Linear.
Para confirmar esse dado, utilizei o Solver, para checar se os valores atribuídos ao alfa para fazer os cálculos do Exponential Smoothing, estavam adequados afim de minimizar os erros, que caso estivessem inadequados, poderiam alterar os resultados obtidos no método fazendo com ele fosse a melhor solução ao invés da Regressão Linear. Confirmamos que os valores atribuídos ao alfa estavam sim adequados, e a Regressão Linear, é a melhor opção para esse projeto.

### Insights obtidos

•	Pode-se concluir, através da análise dos dados que o Google search é o canal com a melhor taxa de obtenção de clientes e continuará crescendo, sendo responsável por mais de 90% dos leads pagos. 

•	No tráfego Orgânico o número de leads provenientes do email, está muito baixo, recomendado utilizar técnicas de SEO (otimização de mecanismos de busca), para alcançar bom posicionamento do site/Blog no Google e em outros buscadores.


•	Oportunidade de desenvolver um funil de captação de leads, dando algum incentivo para que mais pessoas se cadastrem no site para receber a newsletter da empresa, podendo ser o recebimento de um ebook, acesso a uma aula exclusiva (previamente gravada), e após recebimentos dos cadastros, ajustar a comunicação para que os e-mails enviados conduzam os leads no funil de vendas trabalhando os níveis de consciência do produto/serviço, até o fechamento.



KAGGLE. Conjunto de dados. Kaggle, Datasets. São Paulo, 2022 Dispopnível [aqui](https://www.kaggle.com/olistbr/marketing-funnel-olist/home?select=olist_marketing_qualified_leads_dataset.csv). Acesso em Junho - 2022.
