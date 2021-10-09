# Dashboard-Logistica
***
Click na imagem e acesse o Dashboard de logística.
[![Logistica](https://imgur.com/yYHhq21))](https://app.powerbi.com/view?r=eyJrIjoiM2M5NzMwZDEtNWQ5Yy00Y2QxLWE4YjMtMzQwYzM2NTU0NjUwIiwidCI6IjJlMDg2ODMxLTlkNTAtNDA4Zi04MWMzLTM5Zjc0OTZmYzNmNiJ9&pageName=ReportSection96bce97b8cb7d090726d)

## Introdução
***
A Karpalog é uma empresa de logística especializada em segurança e qualidade no transporte de cargas desde 2017. Sua sede fica em Santa Catarina e a operação é concentrada nas regiões Sul e Sudeste através de suas filiais. A empresa possui veículos de ponta e profissionais treinados e especializados para transportar os mais diversos tipos de carga, sempre buscando a qualidade e pontualidade.

## Objetivos
***
Um dos grandes objetivos da gestão logística do transporte de cargas é reduzir custos. Ao controlar todos os gastos envolvidos, é possível aprimorar processos e diminuir custos desnecessários.
Você foi contratado como para ajudar a Karpalog no desenvolvimento de um Dashboard para que os gestores possam acompanhar os principais indicadores da área realacionados a operação principalmente, ter uma melhor visibilidade dos custos para que seja possível identificar pontos de melhoria e viabilizar o aumento da margem operacional.

## Requisitos
***
1. A solução deverá ser desenvolvida utilizando o Power BI Deskop;

2. Utilize no máximo três páginas, sendo a primeira composta pela Capa; 

3. Escolha as cores dos gráficos a partir da paleta disponibilizada pela empresa:
090F4D, EF3964, 4024A6, 1EC4D8, 2572BF e E0962C;

4. Calcule os seguintes indicadores de acordo com as descrições:
- Pedidos entregues: Total de Pedidos que foram entregues;
- Pedidos devolvidos: Total de Pedidos com Ocorrência;
- Custo variável: Soma do Custo Combustível (abastecimento) com o Custo de Manutenção;
- Custo total: Soma do Custo Fixo com o Custo Variável;
- Receita Bruta: Total do Valor Frete;
- Resultado: diferença entre a Receita Bruta e o Custo Total;
- Margem Operacional: razão entre o Resultado e a Receita Bruta;
- Ticket Médio: razão entre a Receita Bruta e a Quantidade de Pedidos;
- Order Cycle Time (OCT): tempo desde a data do pedido até a entrega.
- On Time: percentual de pedidos entregues no prazo previsto;
- In Full: percentual de pedidos entregues sem ocorrência;
- OTIF: produto entre os indicadores de On Time e In Full.

## Dados
***
A primeira versão do Dashboard será entregue utilizando a base de dados em Excel extraída do ERP, mas futuramente, após a validação do mesmo, haverá conexão do Power BI com o Sistema da empresa.
Os detalhes sobre cada tabela estão descritos a seguir:
- BaseDados.xlsx: tabela com os dados do percurso de cada veículo, valores de cada frete e informações da mercadoria entregue.
- CustosMensais.xlsx: consiste dos dados de custos do veículo como custos de manutenção, 
abastecimento e custos fixos.
- MotivosOcorrrencia.xlsx: é a tabela com o cadastro dos motivos de ocorrências de devolução. 

## Análises
***
As análises foram feitas baseadas nas seguintes perguntas:
1. Qual a Receita, Custo, Resultado e % Margem Operacional acumulado em todo o período analisado? 

   Receita = R$ 127,0 Mi
   Custo total = R$ 88,3 Mi
   Resultado = R$ 38,6 Mi
   Margem = 30,4%
2. Em 2021, qual o tipo de veículo possui maior % Margem Operacional numa visão geral? E por filial?

   Truck. Por filial também é o tipo Truck. 

3. Em 2021, o ticket médio aumentou em relação à 2020?
 Sim.

4. Qual a pior e melhor Filial em termos de Resultado?

Biguaçu é a pior e Campinas é a melhor filial em termos de Resultado. 

5. Qual o % On Time em 2021? 

68,9%

6. Qual o % In Full em 2021? 

99,1%

7. Qual o % OTIF em 2021? Descreva com suas palavras o que um aumento nesse valor representa.

68,3%. O OTIF mede a satisfação do cliente em relação a sua experiência com a empresa. Um aumento nesse valor indica que a empresa está entregando mais produtos dentro do prazo e com as especificações corretas.

8. Qual a filial com maior quantidade de pedidos devolvidos em todo o período analisado? Pode-se considerar que essa filial é a pior dentre as demais em termos de mercadorias devolvidas?
Campinas. 

Não, porque essa Filial é a que tem mais pedidos. Para obter a pior filial deve-se analisar o percentual de pedidos devolvidos em relação ao total. Analisando as demais filiais, Contagem é a filiam com maior % Pedidos devolvidos (1,08%).

9. Quais os três principais motivos de devolução de mercadorias em 2021?

Falta de pedido, Preço errado e Estabelecimento fechado.

10. O indicador Order Cycle Time em 2021 melhorou ou piorou se comparado ao total dos anos anteriores?

Para obter a resposta, basta você verificar que ao filtrar 2021, o valor é de 6,05 dias e ao selecionar todos os anos exceto 2021, o valor é de 6,14 dias.