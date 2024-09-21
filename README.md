### Power BI Analyst
Repositório relacionado à formação de Power BI Analyst.


## Desafio-DIO - NTT DATA DATA ENGINEER BOOT CAMP
Este repositório contém soluções para desafios propostos no boot camp de Data Engineer da NTT Data. Abaixo estão os detalhes dos projetos:


## Analisando Dados de um Dashboard de Vendas no Power BI

**Financial Data Analysis:** Criação da terceira página do relatório com dados de vendas oferecidos na amostra padrão do Power BI.

**Financial Project:** Criação do Financial Report - amostra fornecida pelo próprio aplicativo, com funcionalidades mais interativas, como botões e filtros.
Criando um Dashboard Corporativo com Integração com MySQL e Azure


## Criando um Dashboard corporativo com integração com MySQL e Azure

**Checklist do que foi cumprido no desafio:**

⦁ Criação de uma instância na Azure para MySQL ✅

⦁ Criação do banco de dados com base disponível no GitHub ✅

⦁ Integração do Power BI com MySQL no Azure ✅

⦁ Verificação de problemas na base a fim de realizar a transformação dos dados ✅

**Diretrizes para Transformação dos Dados:**

⦁ Verifique os cabeçalhos e tipos de dados ✅

⦁ Modifique os valores monetários para o tipo double preciso ✅

⦁ Verifique a existência dos nulos e analise a remoção ✅

⦁ Os employees com nulos em Super_ssn podem ser os gerentes. Verifique se há algum colaborador sem gerente ✅

⦁ Verifique se há algum departamento sem gerente ✅

⦁ Se houver departamento sem gerente, suponha que você possui os dados e preencha as lacunas ✅

⦁ Verifique o número de horas dos projetos ✅

⦁ Separe colunas complexas ✅

⦁ Mescle consultas employee e department para criar uma tabela employee com o nome dos departamentos associados aos colaboradores. A mescla terá como base a tabela employee. Fique atento, essa informação influencia no tipo de junção ✅

⦁ Neste processo, elimine as colunas desnecessárias ✅

⦁ Realize a junção dos colaboradores e respectivos nomes dos gerentes. Isso pode ser feito com consulta SQL ou pela mescla de tabelas com Power BI. Caso utilize SQL, especifique no README a query utilizada no processo ✅

⦁ Mescle as colunas de Nome e Sobrenome para ter apenas uma coluna definindo os nomes dos colaboradores ✅

⦁ Mescle os nomes de departamentos e localização. Isso fará com que cada combinação departamento-local seja única, auxiliando na criação do modelo estrela em um módulo futuro ✅

⦁ Explique por que, neste caso supracitado, podemos apenas utilizar o mesclar e não o atribuir.
**Resposta:** Mesclar permite combinar informações de duas tabelas e cria uma única combinação. Atribuir funciona dentro de uma tabela e não combina dados de fontes diferentes ✅

⦁ Agrupe os dados a fim de saber quantos colaboradores existem por gerente ✅

⦁ Elimine as colunas desnecessárias, que não serão usadas no relatório, de cada tabela ✅


## Criando Star Schema com Universidade
Este projeto modela um Data Warehouse focado na análise de dados sobre professores, cursos, disciplinas, departamentos e datas. Foi desenvolvido como parte de um desafio proposto pelo DIO, cujo objetivo é transformar a modelagem inicial em um Star Schema. O modelo permite análises detalhadas da carga horária ministrada, dos cursos e das disciplinas ministradas, além de oferecer uma visão completa das dimensões relacionadas aos professores e suas atividades acadêmicas.

## Modelagem e Transformação de dados com DAX Power BI
O intuito desse projeto era aplicar os princípios da modelagem de dados utilizando a abordagem de Star Schema no Power BI. A base de dados financeiros (Financial Sample) foi convertida em um modelo de dados, com a criação de tabelas fato e dimensão que tornam a análise de vendas e desempenho mais eficiente, organizadas de maneira a aprimorar consultas e visualizações.

- D_Products: Inclui dados agrupados sobre os produtos, como médias e limites de vendas. ✅
- D_Products_Details: Contém dados adicionais sobre os produtos, como faixa de desconto (Discount Band), preço de venda (Sale Price) e custo de produção (Manufacturing Price). ✅
- D_Discounts: Relação que correlaciona o ID do Produto com as informações dos descontos oferecidos. ✅
- D_Calendar: Criada utilizando a função CALENDARAUTO() no DAX, com a finalidade de fornecer informações temporais, como datas, meses e anos. ✅
- F_Sales: A planilha que guarda todas as informações detalhadas sobre as transações realizadas, como volume de vendas, valor de venda, segmento de atuação, localização, lucratividade e data. ✅

**Funções DAX utilizadas**
- CALENDARAUTO()
- CompositeKey_Product_Country_Date_SalePrice_UnitsSold = [Product] & "-" & [Country] & "-" & FORMAT([Date], "YYYYMMDD") & "-" & [Sale Price] & "-" & [Units Sold]

## Criando um Dashboard Gerencial para Tomada de Decisões Com Power BI
Alteração do relatório inicial de financial para uma versão mais funcional e detalhada, com o objetivo de melhorar a experiência do usuário.

**Página 1 - Sales Reports:** Detalhes referente as vendas da empresa, com filtros de datas e possibilidade de verificação por produtos e segmento.

**Página 2 - Profit:** Análise do lucro da empresa, com possibilidades de identificar vários detlahes do lucro, cálculo do lucro bruto, filtro de datas, e diversos tipos de verificações.

**Página 3 - Production Costs:** Valores de manufatura, comparativo com o preço de vendas e destaque para os custos por produto vendido.

## Criando um Relatório Vendas e Lucros com Data Analytics com Power BI
Desafio de projeto final DIO

**Homepage:** Página inicial do report financeiro

**Página Relatório de Vendas:** Relatório de vendas com gráfico de venda por período, produto, localização, com filtro de datas.

**Página Detalhes:** Detalhes das vendas, com gráfico de barras de vendas por mês e gráfico de barras empilhadas de vendas por semestre, tabelas com vendas por trimestre, histograma de unidades vendidas e gráfico de barras de produtos vendidos.

**Página Detalhes de Vendas - TOP:** Detalhes das vendas, com cartão que mostra o máximo de produtos vendidos, indicando o segmento e o máximo de vendas por mês, gráfico de doughnut com os top 3 países com mais vendas, e os top 5 meses de venda e lucro. Também há um gráfico de barras com os top 3 produtos vendidos e os top 3 produtos por país. Por fim, um gráfico de dispersão com a soma de vendas, unidades e soma de lucros por produtos e mês.

