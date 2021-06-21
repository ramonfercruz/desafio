#<b>1º Desafio</b> <br>
O gerenciamento do relacionamento com os clientes tem como um dos seus objetivos 
centrais aumentar o número de clientes ativos da empresa - e a retenção desses clientes é crítica 
para seu sucesso. Sendo assim, um time foi mobilizado para garantir o desenvolvimento da 
estratégia de retenção de clientes e, sabendo do seu potencial analítico, você foi convocado para 
esse desafio. 
<p>Em busca de uma maior compreensão das particularidades do negócio e de melhor 
entendimento do cenário do churn, vocês optaram por realizar uma análise exploratória dos 
dados. Em um primeiro momento algumas hipóteses foram levantadas visando direcionar esse 
desenvolvimento inicial e, considerando a base de dados disponibilizada e um período de churn
de 1 ano, foi requisitado a você a validação da seguinte hipótese: 
<p><b>"O churn de novos clientes é maior do que o churn de clientes ativos”</b>
 <br><br>
 ##O que é churn?
<p><i>"O churn é uma métrica que indica a taxa de cancelamento de clientes em um determinado período. Para calculá-lo, você deve levar em consideração dois fatores: o número de cancelamentos e o total de clientes ativos no início do período que você quer analisar. Saiba mais!"</i>
<p><b>Fonte:</b> https://conteudo.movidesk.com/o-que-e-churn-por-que-ele-e-importante/
<br><br>
 ##Definição de conceitos:

Após a análise dos dados defini os seguintes conceitos:

<b>Cliente Novo:</b> Cliente será considerado novo no ano do seu primeiro contratos.

<b>Cliente Ativo:</b> Todo cliente na base que é diferente de novo.

<b>Churn Cliente Novo:</b> Cliente novo que realizou apenas uma compra no ano corrente e não realizou compra no ano seguinte.

<b>Churn Cliente Ativo:</b> Cliente ativo que não realizou compra no ano corrente.
  
![image](https://user-images.githubusercontent.com/54825092/122709089-f32e6080-d233-11eb-9e8e-adebbfdda041.png)
  
<b>Conclusão:</b> Com um nível de confiança de 95% rejeitamos a hipótese nula (H0) que as amostras são iguais. Logo podemos concluir que o churn de novos clientes é maior que dos Ativos.
