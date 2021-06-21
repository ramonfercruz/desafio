# <b>1º Desafio</b> <br>
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
<h2> O que é churn?</h2>
<p><i>"O churn é uma métrica que indica a taxa de cancelamento de clientes em um determinado período. Para calculá-lo, você deve levar em consideração dois fatores: o número de cancelamentos e o total de clientes ativos no início do período que você quer analisar. Saiba mais!"</i>
<p><b>Fonte:</b> https://conteudo.movidesk.com/o-que-e-churn-por-que-ele-e-importante/
<br><br>
 <h2>Definição de conceitos:</h2>

Após a análise dos dados defini os seguintes conceitos:

<b>Cliente Novo:</b> Cliente será considerado novo no ano do seu primeiro contrato.

<b>Cliente Ativo:</b> Todo cliente na base que é diferente de novo.

<b>Churn Cliente Novo:</b> Cliente novo que realizou apenas uma compra no ano corrente e não realizou compra no ano seguinte.

<b>Churn Cliente Ativo:</b> Cliente ativo que não realizou compra no ano corrente.
  
![image](https://user-images.githubusercontent.com/54825092/122709089-f32e6080-d233-11eb-9e8e-adebbfdda041.png)
  
<b>Conclusão:</b> Com um nível de confiança de 95% rejeitamos a hipótese nula (H0) que as amostras são iguais. Logo podemos concluir que o churn de novos clientes é maior que dos Ativos.


<h1><b>2º Desafio </b></h1>
<p>Antes de apresentar as análises para a liderança, você decide se reunir com seu colega 
de trabalho para discutirem os resultados e se estruturarem para a apresentação. No entanto, 
para isso, é preciso identificar um horário na agenda que seja factível para ambos.
<p>Dadas as agendas de duas pessoas e seus respectivos horários de trabalho, escreva 
um algoritmo que retorna todos os horários nos quais ambas as pessoas estariam disponíveis 
para uma reunião de t minutos. 
<p>As agendas serão compostas por uma lista de n compromissos previamente marcados. 
Esses compromissos, por sua vez, serão representados por uma lista ou tuple de duas strings, 
no qual o primeiro elemento representa o horário de início do compromisso e o último elemento 
o horário de término. A jornada de trabalho terá o mesmo formato de um compromisso, no qual 
o primeiro elemento representa o horário de início do turno e o último elemento o horário final da 
jornada. O tempo da reunião, em minutos, será um inteiro. Por fim, espera-se que o resultado 
esteja no mesmo formato das agendas, nos quais os “compromissos”, nesse caso, 
correspondem aos horários disponíveis para a reunião. 
<p><b>Exemplo:</b> Considere o seguinte cenário:
<p>1. Agenda da pessoa A: [['9:00', '10:30'], ['12:00', '13:00'], ['16:00', '18:00']]
<p>2. Horário de Trabalho da pessoa A: ['9:00', '20:00']
<p>3. Agenda da pessoa B: [['10:00', '11:30'], ['12:30', '14:30'], ['14:30', '15:00'], ['16:00', 
'17:00']]
<p>4. Horário de Trabalho da pessoa B: ['10:00', '18:30']
<p>Os horários que possibilitam uma reunião de 30 minutos entre a pessoa A e pessoa B são:
[['11:30', '12:00'], ['15:00', '16:00'], ['18:00', '18:30']]
