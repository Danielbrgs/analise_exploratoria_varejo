# biblioteca_pandas

#O dataset de varejo que analizamos é composto por informações de vendas de uma loja virtual que atua em todo o território nacional, vendendo produtos de diferentes departamentos. Além disso, a loja atua em diferentes canais de venda, como marketplace, loja própria, entre outros.

Premissas do negócio:
Ao analisar os dados, é importante ter em mente que existem algumas premissar a serem consideradas. A primeira delas é que, devido a um erro no banco de dados, algumas compras não possuem informações de UF (Unidade Federativa). Para solucionar esse problema, foi deficido que essas comprar serão consideradas como pertencentes ao Mato Grosso do Sul (MS). A segunda premissa é que o preço final de um produto não pode ser maior que o seu preço com frete.
Assim foram eliminados as vendas cujo preço do produto era maior que seu preço com frete. Também existiam alguns produtos sem preço, neste caso, o preço com frete foi considerado igual ao preço do produto.
Outra adequação feita, foi eliminar o departamento 'TV_e_Video'. Este departamento constava com poucas vendas e foi incorporado ao departamento 'TVs_e_Acessorios'.
Quantos aos canais de vendas o mesmo procedimento foi feito à categoria 'APP', que foi eliminada e fundida à categoria 'Aplicativo'.

Métricas:
Com base nesse contexto e nas premissas de negócio estabelecidas, podemos avaliar as seguintes métricas:

1. Departamentos mais vendidos: Analisando os dados de vendas, podemos identificar quais são os departamentos mais populares entre os clientes. Essa informação pode ser útil para entender quais são os produtos mais procuradps pelos clientes e ajustar a estratégia de venda da loja em conformidade.
2. Média de preço com frete por nome de Departamento: Para entender o comportamento de preço por departamento, podemos calcular a média de preço com frete por nome de departamento. Essa métrica pode ajudar a identificar quais são os departamentos mais rentáveis e ajustar a precificação de produtos de acordo com a margem de lucro desejada.
   3. Quantidade de vendas por Mês: Analisando a quantidade de vendas realizadas em cada mês, podemos identificar sazonalidades no comportamento de compra dos clientes e planejar campanhas de marketing específicas para cada período.
   4. Média de renda para cada tipo de canal de venda: Identificar a média de renda dos clientes em diferentes canais de venda pode ajudar a loja a adaptar a estratégia de marketing e vendas para cada público-alvo.
   5. Média de idade de clientes por bandeira: Saber a faixa etária dos clientes por bandeira pode ajudar a identificar pergis de consumidores e ajustar a estratégia de venda para atender melhor cada público.
