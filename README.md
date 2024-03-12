# Projeto-6-Análise-de-Vendas


O Objetivo desse projeto é identificar numa base de Vendas, quais produtos mais venderam em quantidade, quais mais faturaram e qual foi a loja que mais obteve faturamento dentre todas as cidades que possuem tal loja.

Descrição do Projeto:

- Após a importação dos pacotes utilizados nesse projeto, usei o método do pacote "os" para verificar todos os arquivos que haviam na pasta. Método "listdir()".
- Logo depois é criado o dataframe chamado "total_tabela".
- O laço " for ", é criado para que seja trazido para a análise, somente os arquivos de Vendas, visto que existe na pasta, arquivos que não são de vendas.
- Dessa forma foi possivel fazer no fim dele uma adição de todas as tabelas de ventas (que eram separadas) a uma unica tabela, formando um super tabelão com todos os dados de vendas de todas as cidades.

            Partindo para as análises:
- Busquei inicialmente saber qual foi o produto mais foi vendido em quantidade. Ordenando de forma decrescente por meio do recurso "ascending= False";
- Depois foi verificado o produto que mais obteve faturamento. Nessa etapa, foi criada uma nova coluna chamada "Faturamento";
- No processo seguinte, é construido a análise de qual foi a cidade que mais teve faturamento nas vendas. Foi feito a consulta da soma dos Faturamentos  agrupando por Lojas;
- E por fim, com essa informação de faturamento das lojas foi plotado um gráfico com dados de Loja x Faturamento para enxergar visualmente o comportamento das rendas por cidade.
