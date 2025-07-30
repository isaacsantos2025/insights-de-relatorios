# Projeto da DIO - insights-de-relatórios

Foi consolidada todas as bases de dados em um único arquivo

Os produtos mais vendidos de cada país foram os seguintes:

Australia: O produto mais vendido foi o ANBERNIC RG353M, com 22 unidades.

Canadá: O produto mais vendido foi o ANBERNIC RG40XXV, com 41 unidades.

França: O produto mais vendido foi o ANBERNIC RG35XX, com 22 unidades.

Alemanha: O produto mais vendido foi o ANBERNIC RG35XX, com 17 unidades.

Japão: O produto mais vendido foi o ANBERNIC RG40XXV, com 21 unidades.

Reino Unido (UK): O produto mais vendido foi o ANBERNIC RG40XXV, com 37 unidades.

EUA (USA): O produto mais vendido foi o ANBERNIC RG353M, com 12 unidades.

Ótimo. Conforme solicitado, analisei a fundo os padrões de vendas nos seus dados para criarmos uma previsão de demanda inicial. Esta previsão é a base para todas as otimizações de estoque e logística que discutimos.

### 1. Padrão Geral de Vendas

Primeiro, vamos olhar o quadro geral. A quantidade total de unidades vendidas por mês em 2024 foi a seguinte:

| Mês (2024) | Quantidade Total Vendida |
| :--- | :--- |
| 2024-05 | 31 |
| 2024-06 | 49 |
| 2024-07 | 79 |
| 2024-08 | 104 |
| 2024-09 | 59 |
| 2024-10 | 82 |
| 2024-11 | 13 |

**Observações:**
* Houve um **crescimento consistente nas vendas de maio a agosto**, atingindo um pico de 104 unidades.
* Ocorreu uma queda em setembro, seguida por uma forte recuperação em outubro.
* O número de novembro é baixo porque os dados que você forneceu só vão até o início do mês.

### 2. Padrão de Vendas por Produto (Top 5)

Agora, vamos detalhar a performance dos seus 5 produtos mais importantes. Entender a demanda individual de cada um é crucial para a gestão de estoque.

| Mês (2024) | RG28XX | RG353M | RG35XX | RG40XXV | RGCubeXX |
| :--- | :--- | :--- | :--- | :--- | :--- |
| 2024-05 | 10 | 6 | 0 | 8 | 7 |
| 2024-06 | 3 | 1 | 11 | **26** | 8 |
| 2024-07 | 9 | 16 | **33** | 11 | 10 |
| 2024-08 | 15 | **29** | 25 | 24 | 11 |
| 2024-09 | 8 | 14 | 7 | **25** | 5 |
| 2024-10 | 23 | 14 | 19 | 17 | 9 |

**Observações:**
* **ANBERNIC RG40XXV:** É seu produto mais consistente e um dos mais vendidos, com picos de venda em junho e setembro. Este é claramente um produto do seu "Grupo A".
* **ANBERNIC RG35XX e RG353M:** Apresentam uma demanda forte, mas mais volátil. O RG35XX teve um pico enorme em julho, e o RG353M em agosto. Também são produtos do "Grupo A".
* **ANBERNIC RG28XX e RGCubeXX:** Possuem uma demanda mais estável, porém em um volume menor.

### 3. Previsão de Demanda Inicial

Para transformar essa análise em uma previsão prática, calculei a **média de vendas mensais** para cada um desses produtos, utilizando os dados dos **últimos três meses completos (Agosto, Setembro e Outubro)**. Isso nos dá uma linha de base sólida e recente para o planejamento.

Aqui está sua previsão de demanda inicial:

| Produto | Previsão de Demanda Mensal (Unidades) |
| :--- | :--- |
| **ANBERNIC RG40XXV** | **22** |
| **ANBERNIC RG353M** | **19** |
| **ANBERNIC RG35XX**| **17** |
| ANBERNIC RG28XX | 15 |
| ANBERNIC RGCubeXX | 8 |

Isto significa que, para os próximos meses, uma estimativa de demanda segura seria:
* Você provavelmente venderá cerca de **22 unidades do RG40XXV por mês**.
* A demanda para o **RG353M** deve ficar em torno de **19 unidades por mês**.
* Para o **RG35XX**, a previsão é de **17 unidades por mês**.

### Próximos Passos e Recomendações

Esta previsão é um ponto de partida. Lembre-se de ajustá-la com base em:
* **Ações de Marketing:** Se você planeja uma grande promoção ou campanha de cupons, a demanda pode aumentar.
* **Sazonalidade:** Aproxime-se de datas como a Black Friday e o Natal, e a demanda por esses produtos tende a crescer significativamente. Você deve planejar um estoque maior para esses períodos.

