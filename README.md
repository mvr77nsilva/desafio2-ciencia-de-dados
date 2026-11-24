# desafio2-ciencia-de-dados
# Desafio 02 — Análise de Pedidos de Delivery

**Integrante:** Natã Sampaio Silva
*(Trabalho realizado individualmente)*

## Perguntas Investigadas
1. Quais dias da semana concentram o maior volume de pedidos?
2. Qual categoria de comida gera o maior faturamento e qual tem o maior valor médio por pedido?
3. O tempo de entrega é significativamente maior em dias de chuva do que em dias sem chuva?

## Principais Conclusões
- **Volume por dia:** O maior movimento ocorre no **Sábado** (98 pedidos), concentrando a demanda no fim de semana.
- **Desempenho por categoria:** **Pizzas** lidera o faturamento total (**R$ 8.360,66**), enquanto **Comida Japonesa** tem o maior ticket médio (**R$ 95,57**).
- **Efeito da chuva (Teste de Hipótese):** Em dias de chuva, o tempo médio de entrega sobe de **32,13 min** para **46,18 min**. O teste t de Welch resultou em **valor-p = 7,19 × 10⁻⁵⁴** (< 0,05), confirmando estatisticamente que a chuva aumenta o tempo de entrega.

## Estrutura do Repositório
- `dados/base.csv`: Base de dados original, sem alterações.
- `dados/base_tratada.csv`: Base de dados após a limpeza (remoção de duplicatas e nulos).
- `analise.ipynb`: Notebook Python com análise exploratória, gráficos e teste de hipótese.
- `requirements.txt`: Bibliotecas necessárias para executar o notebook.
