# Processo ETL

## Fonte dos Dados

Os dados foram disponibilizados em um arquivo XML contendo duas tabelas:

- Vendas
- Localização

## Transformações Realizadas

### Tratamento dos Dados

- Importação dos dados para o Power Query.
- Ajuste dos tipos de dados das colunas.
- Validação dos registros importados.

### Criação de Nova Coluna

Foi criada uma coluna personalizada que concatena o produto adquirido ao valor pago pelo cliente.

Exemplos:

- A-500
- B-1000
- C-1500

O objetivo dessa transformação foi facilitar análises e agrupamentos relacionados ao faturamento por produto.

### Modelagem

As tabelas foram relacionadas para permitir análises de vendas e localização dos clientes.

## Resultado

Após as transformações, os dados foram carregados para o modelo do Power BI para construção dos indicadores e dashboards.