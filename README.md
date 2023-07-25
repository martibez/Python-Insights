# Python-Insights - PT-BR

Python Insights - Analisando Dados com Python

Case - Cancelamento de Clientes

Fomos contratados por uma empresa com mais de 800 mil clientes para um projeto de Dados. Recentemente a empresa percebeu que da sua base total de clientes, a maioria são clientes inativos, ou seja, que já cancelaram o serviço.

Precisando melhorar seus resultados a empresa quer conseguir entender os principais motivos desses cancelamentos e quais as ações mais eficientes para reduzir esse número.

Primeiro foram identificados e removidos os valores vazios na tabela.
Em seguida, levantamos quantas pessoas cancelaram e quantas não cancelaram.

Ao analisar os contratos mensais, descobrimos que a média de cancelamentos é 1, ou seja, praticamente todos os contratos mensais foram cancelados. Diante disso, decidimos retirar essa modalidade de contrato.

Obtivemos um resultado com menos da metade das pessoas cancelando, mas ainda restaram muitos clientes; portanto, a análise segue.

Vimos então que os cancelamentos estão divididos quase de forma igual entre os modelos de assinatura (Basic, Premium e Standard), com cerca de 1/3 para cada modelo, e suas médias são bem parecidas, o que torna difícil tirar alguma conclusão baseada apenas na média.
Assim, criamos um gráfico para melhorar a visibilidade dos números.

Com os gráficos, conseguimos ver que obtiveram cancelamentos em 100% dos casos os clientes:

- Com acima de 20 dias de atraso
- Que receberam acima de 5 ligações de call center

Ao resolver estes problemas, a taxa de cancelamento cai para 18%:

- Forma de contrato mensal
- Necessidade de ligações no call center
- Atraso no pagamento

Reduzir em 100% a taxa de cancelamento seria utópico, pois envolve situações onde o cliente simplesmente deseja cancelar o serviço. No entanto, ao identificar e atacar as principais causas, especialmente relacionadas à forma de contrato mensal, necessidade de ligações no call center e atraso no pagamento, podemos significativamente reduzir o número de cancelamentos e melhorar os resultados da empresa.


# Python Insights - EN-US

Python Insights - Analyzing Data with Python

Case - Customer Churn

We were hired by a company with over 800 thousand customers for a Data project. Recently, the company realized that the majority of its customer base consists of inactive clients, meaning they have already canceled the service.

In need of improving their results, the company aims to understand the main reasons behind these cancellations and identify the most efficient actions to reduce this number.

First, we identified and removed empty values from the table. Next, we gathered data on how many people canceled and how many did not.

Upon analyzing the monthly contracts, we discovered that the average number of cancellations is 1, meaning almost all monthly contracts were canceled. Consequently, we decided to remove this contract option.

We obtained a result where less than half of the people were canceling, but still, many customers remain, so the analysis continues.

We then observed that the cancellations are almost evenly distributed among the subscription models (Basic, Premium, and Standard), with each model comprising approximately 1/3 of the cancellations, and their averages are quite similar. This makes it challenging to draw any conclusion based solely on the average. Therefore, we created a graph to improve the visibility of the numbers.

With the graphs, we were able to observe that 100% of customers with:

Over 20 days of overdue payments
Received more than 5 calls from the call center
ended up canceling.

By addressing these issues, the cancellation rate drops to 18%:

Monthly contract format
Need for call center calls
Payment delays
Reducing the cancellation rate by 100% would be unrealistic, as it involves situations where the customer simply wishes to cancel the service. However, by identifying and tackling the main causes, especially related to the monthly contract format, need for call center calls, and payment delays, we can significantly reduce the number of cancellations and improve the company's results.
