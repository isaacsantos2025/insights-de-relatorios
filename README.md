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

* Relatório de Insights para Fabricantes
Análise Estratégica com Base nos Dados de Vendas Globais (Maio a Novembro de 2024)
Este relatório apresenta insights cruciais extraídos dos dados de vendas, com o objetivo de orientar as decisões estratégicas de produção, marketing e distribuição.

1. Resumo Executivo
Os dados revelam uma operação de vendas internacionais saudável e em crescimento, com forte penetração em mercados-chave da Europa e América do Norte. O portfólio de produtos demonstra ter modelos com papéis distintos: um "campeão de vendas" consistente (RG40XXV), dois modelos populares com preferências regionais (RG353M e RG35XX) e produtos de nicho. O perfil do consumidor é bem definido, focando na "geração nostalgia" (30 a 60 anos), o que valida a estratégia de mercado do produto.

As principais oportunidades de otimização estão na padronização da marca, na implementação de uma estratégia de preços mais consistente entre os distribuidores e no aproveitamento das preferências regionais para campanhas de marketing direcionadas.

2. Análise de Mercado e Desempenho Geográfico
Observação: A marca possui uma excelente capilaridade global, com uma base de clientes diversificada em 7 países.

Principais Mercados (por volume):

Canadá e Reino Unido (UK) são os mercados mais fortes, impulsionados principalmente pelo modelo ANBERNIC RG40XXV.

EUA, Austrália, França e Alemanha representam mercados secundários robustos e com alto potencial de crescimento.

Japão é um mercado estratégico, mostrando preferência por modelos de ponta.

Insights para o Fabricante:

Foco Logístico: Concentrar esforços de distribuição e talvez estabelecer centros de fulfillment (ou parceiros 3PL) na Europa e América do Norte pode reduzir custos e prazos de entrega, aumentando a competitividade.

Marketing Regional: A popularidade de certos modelos em países específicos (detalhado abaixo) sugere que campanhas de marketing localizadas podem ter um alto retorno sobre o investimento.

3. Estratégia de Produto e Portfólio
Observação: O portfólio de produtos é bem segmentado, atendendo a diferentes perfis de consumidores.

Campeão de Vendas - O Cavalo de Batalha:

O ANBERNIC RG40XXV é o produto mais importante. Ele não apenas vende em alto volume, mas o faz de forma consistente em múltiplos mercados de alto valor (Canadá, UK, Japão).

Recomendação: Priorizar a produção deste modelo. Garantir que nunca haja ruptura de estoque e destacá-lo como o carro-chefe em materiais de marketing globais.

Especialistas Regionais - A Conquista de Nichos:

O ANBERNIC RG353M tem uma performance excepcional nos EUA e na Austrália.

O ANBERNIC RG35XX é particularmente forte na Alemanha e na França.

Recomendação: Colaborar com os distribuidores locais para criar campanhas específicas para esses modelos nos seus respectivos mercados fortes. Isso pode incluir promoções, conteúdo de influenciadores locais e anúncios direcionados.

Inconsistência de Marca - Um Risco a Ser Mitigado:

Os dados mostram os mesmos produtos sendo listados como "MEGANIUM" e "ANBERNIC". Isso dilui a força da marca e pode confundir os consumidores.

Recomendação: Padronizar URGENTEMENTE toda a comunicação e embalagens sob uma única marca forte (provavelmente ANBERNIC). Isso é vital para construir reconhecimento e confiança a longo prazo.

4. Perfil do Consumidor: A Geração Nostalgia
Observação: A análise das datas de nascimento dos compradores revela um perfil de cliente muito claro.

Faixa Etária Dominante: A grande maioria dos compradores nasceu entre 1965 e 1995, o que os coloca na faixa de 30 a 60 anos atualmente.

Insight Estratégico: Seu público-alvo principal são adultos que cresceram com os videogames clássicos das décadas de 80, 90 e início dos anos 2000. Eles não estão comprando apenas um produto; estão comprando nostalgia e a chance de reviver boas memórias.

Recomendação de Marketing:

As campanhas de marketing devem evocar esse sentimento de nostalgia. Use referências a jogos clássicos, design retrô e mensagens que ressoem com as experiências de infância e adolescência dessa geração.

O poder de compra dessa faixa etária é alto, indicando que eles valorizam a qualidade e a performance, não apenas o preço baixo.

5. Estratégia Comercial e de Preços
Observação: A estratégia de vendas é agressiva, com uso intensivo de cupons, mas a falta de padronização de preços pode ser prejudicial.

Inconsistência de Preços: O mesmo produto (RG35XX) é vendido por 900 e 90 em diferentes moedas/transações. Mesmo considerando a conversão de moeda, a variação é extrema.

Risco: Isso pode criar uma "guerra de preços" entre seus distribuidores, desvalorizando a percepção da marca e corroendo as margens de lucro de todos.

Recomendação: Implementar uma Política de Preço Mínimo Anunciado (MAP - Minimum Advertised Price). Isso garante que, independentemente do canal ou país, o valor do seu produto seja percebido de forma consistente.

Canais de Venda: As vendas estão bem distribuídas entre Etsy, Shopee e AliExpress, indicando uma estratégia multicanal eficaz por parte dos distribuidores.

Recomendação: Incentivar os distribuidores a manterem uma presença forte em todas as plataformas, pois cada uma parece atrair diferentes segmentos de clientes e geografias.

