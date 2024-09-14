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
