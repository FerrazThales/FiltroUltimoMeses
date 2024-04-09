# Filtrando os Últimos N Meses no Power BI

<p align="center"><img src="https://github.com/FerrazThales/FiltroUltimoMeses/blob/main/media/analisar_ultimos_meses.gif"></p>

## Introdução
O artigo aborda como filtrar dinamicamente os últimos N meses no Power BI, com base em uma data escolhida. A necessidade surge em situações onde é preciso analisar um número específico de meses anteriores de forma dinâmica.

## Desenvolvimento

### Preparação dos Calendários:
Utiliza-se duas tabelas dCalendario: uma principal e outra secundária.
Os códigos M utilizados para criar as tabelas são fornecidos, considerando as datas iniciais e finais da base de dados, e gerando listas de datas entre esses períodos.
### Modelagem de Dados no Power BI:
Relacionamento tradicional entre dCalendario e a tabela fato de vendas (1 para muitos).
A tabela secundária é utilizada apenas no eixo visual e deve ter seu relacionamento desativado.
### Criação de Parâmetros:
Adiciona-se um parâmetro numérico no relatório através da guia de modelagem.
### Medida de Vendas dos Últimos Meses:
A medida é criada para calcular as vendas dos últimos N meses, considerando a seleção do usuário e o contexto da data escolhida.
## Conclusão
Para alcançar uma filtragem dinâmica dos últimos N meses no Power BI, são necessárias técnicas avançadas, incluindo a criação de medidas DAX e o uso de parâmetros para permitir ao usuário especificar os valores desejados.
