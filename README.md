# Olimpiadas 2024: Medalhas vs. PIB
Este projeto explora a relação entre o número de medalhas olímpicas conquistadas por países e seus indicadores econômicos, como PIB e população, usando dados das Olimpíadas de 2024. A análise busca identificar correlações entre o desempenho olímpico e a economia dos países, além de avaliar o impacto do tamanho da população nos resultados. O projeto inclui etapas de limpeza de dados, análise exploratória e construção de modelos preditivos, fornecendo insights sobre os fatores socioeconômicos que influenciam o sucesso olímpico.

## Metodologia Aplicada
A metodologia aplicada na análise dos dados segue uma abordagem estruturada, composta por várias etapas, com o objetivo de extrair informações relevantes e identificar padrões significativos relacionados ao desempenho olímpico dos países. A seguir, descrevemos as principais fases do processo analítico:

- **Coleta e Preparação dos Dados:** A preparação dos dados envolveu a limpeza, com a correção de valores faltantes ou inconsistentes e a padronização dos formatos de dados, garantindo a integridade e a qualidade da base.
- **Análise Exploratória:** foi realizada uma análise preliminar para entender a distribuição dos dados e as principais características do conjunto.
- **Análise Comparativa e Correlacional:** A análise exploratória foi complementada com comparações entre os países, levando em consideração as regiões geográficas, PIB e a quantidade de medalhas conquistadas. O objetivo foi observar se havia alguma correlação entre o desempenho olímpico e fatores como o nível de riqueza (representado pelo PIB) e o tamanho da população. Ferramentas de análise estatística, como correlação de Pearson, foram aplicadas para identificar relações significativas entre as variáveis.
- **Modelagem e Previsões:** A fase de modelagem envolveu a utilização de técnicas de regressão para prever a quantidade de medalhas que um país poderia conquistar, levando em conta variáveis como o PIB e a população.
- **Visualização e Interpretação dos Resultados:** A visualização final dos dados foi crucial para comunicar as conclusões da análise. Gráficos de barras, dispersão e mapas foram utilizados para ilustrar as correlações e comparações entre os países.

## Apresentação dos Dados
Este conjunto de dados contém informações sobre o desempenho olímpico de diversos países, com as seguintes colunas:

*country:* Nome do país participante das Olimpíadas.

*country_code:* Código do país, utilizado para identificá-lo de forma única.

*region:* A região geográfica à qual o país pertence.

*gold:* O número de medalhas de ouro conquistadas pelo país.

*silver:* O número de medalhas de prata conquistadas.

*bronze:* O número de medalhas de bronze conquistadas.

*total:* O número total de medalhas conquistadas (ouro, prata e bronze).

*gdp:* O Produto Interno Bruto (PIB) do país no ano dos Jogos.

*gdp_year:* O ano em que o PIB foi registrado, correspondente ao ciclo olímpico.

*population:* A população do país no ano correspondente ao PIB.

