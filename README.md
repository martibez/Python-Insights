# Python-Insights

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
