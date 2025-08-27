# Enem_Microdados_Python
Análise de Microdados do Enem utilizando Python. Esse repositório tem fins didáticos.
Análise dos Microdados do ENEM – Região Nordeste

*Este repositório contém análises exploratórias realizadas como parte de uma atividade do curso de Pós-graduação em Ciência de Dados e Inteligência Artificial.*

**Objetivo**
Explorar os microdados do ENEM (Exame Nacional do Ensino Médio) para a região Nordeste, avaliando distribuição de notas, médias por estado e variabilidade entre áreas de conhecimento.

*Etapas da Análise*

**Leitura e Preparação dos Dados**
Importação do dataset com pandas.
Exclusão das colunas do questionário socioeconômico (Q001–Q025).
Configuração de exibição de colunas e dimensões do DataFrame.

**Estatísticas Descritivas e Agrupamentos**
Cálculo de médias das notas por estado (NU_NOTA_CN, NU_NOTA_CH, NU_NOTA_LC, NU_NOTA_MT, NU_NOTA_REDACAO)
Identificação dos estados com maior e menor desempenho em cada área.
Ranking das médias em Matemática, com geração de tabela ordenada.
Cálculo do desvio padrão por estado, destacando a área de maior variação em cada UF.
Medianas da redação por estado.

**Visualizações**
Boxplot das notas de redação por estado.
Histogramas para distribuição padronizada das notas de Matemática em três faixas: Baixa, Média e Alta.
Gráficos de barras para o ranking das médias de Matemática.

**Análises Específicas**
Identificação de estados com maior nível de outliers em redação (RN e BA).
Classificação das notas de Matemática com pd.cut e numpy.where.
Ajuste de escalas e personalização de rótulos em gráficos com Matplotlib.

**Tecnologias Utilizadas**
Python
Pandas, NumPy, Matplotlib, Seaborn

**Conclusões**
CE, SE e PB apresentaram as maiores medianas em redação.
RN e BA tiveram maior concentração de outliers negativos (notas muito baixas).
Ranking de Matemática evidenciou diferenças entre estados, com ordenação clara via tabela e gráficos.
A padronização em categorias (Baixa, Média, Alta) facilitou a visualização e comparação das notas de Matemática.
