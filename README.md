# Controle de Vendas de Carros - Power BI Dashboard

Este projeto consiste em um dashboard desenvolvido no Power BI para controlar e visualizar as vendas de carros. O arquivo de origem é uma planilha Excel com dados de fabricantes, categorias, preços e vendas. O Power BI foi utilizado para criar visualizações personalizadas, incluindo um cálculo de "Resultado de Vendas", que não está presente no arquivo Excel original.

## Estrutura do Arquivo Excel

O arquivo Excel utilizado para a base de dados contém várias colunas, sendo as mais importantes:

- **Fabricante**: O nome da montadora responsável pelo carro (ex.: Ford, Chevrolet, Toyota, etc.)
- **Descrição**: Informações sobre a descrição do carro, se é gol, fiesta, etc.
- **Categoria**: O tipo de carro (ex.: SUV, Sedan, Hatchback).
- **Preço**: O valor de venda do carro.
- **Vendas**: O número de unidades vendidas.

## Visualizações no Power BI

Foram criados dois gráficos principais para visualização e análise:

1. **Vendas por Fabricante**: Um gráfico de barras ou pizza que mostra o total de vendas agrupadas por fabricante. Esta visualização permite identificar quais marcas têm o maior volume de vendas.

2. **Fabricante X Resultado de Vendas**: O "Resultado de Vendas" foi calculado diretamente no Power BI e consiste em uma métrica derivada da combinação de preços e volumes de vendas para cada fabricante. Este gráfico mostra a performance de vendas de cada fabricante, levando em consideração o impacto financeiro total.

## Cálculo do Resultado de Vendas

No Power BI, o **Resultado de Vendas** foi calculado referente a uma categoria vendida por determinado fabricante, usando  a seguinte fórmula DAX:
= [Vendas] * [Preço]

## instalação

por serem dados fictícios, o arquivo do excel pode ser baixado para visualização de dados junto com o arquivo pdf que mostra os gráficos criados no power BI.

