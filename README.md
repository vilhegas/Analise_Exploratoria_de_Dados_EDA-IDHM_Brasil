# 📊 Análise Exploratória de Dados (EDA) — IDHM Brasil

## 📌 Sobre o projeto

Este projeto apresenta uma **Análise Exploratória de Dados (EDA)** do Índice de Desenvolvimento Humano Municipal (IDHM) brasileiro, utilizando Python e bibliotecas especializadas em manipulação, análise estatística e visualização de dados.

A análise utiliza dados disponibilizados pelo **Instituto de Pesquisa Econômica Aplicada (IPEA)**, referentes ao ano de 2010, com o objetivo de compreender e comparar o desenvolvimento humano dos municípios, estados e regiões brasileiras.

O estudo considera três dimensões fundamentais do desenvolvimento humano:

- **Educação:** indicadores relacionados à escolaridade e ao acesso à educação.
- **Longevidade:** indicadores associados à expectativa de vida e às condições de saúde.
- **Renda:** indicadores relacionados às condições econômicas da população.

A partir desses dados, são realizadas análises estatísticas, comparações regionais e visualizações gráficas para identificar padrões e desigualdades socioeconômicas no Brasil.

## 🎯 Objetivo

Investigar os indicadores de desenvolvimento humano no Brasil, identificando diferenças socioeconômicas entre municípios, estados e regiões.

A análise busca responder à seguinte pergunta norteadora:

**Quais estados brasileiros apresentam melhores indicadores de desenvolvimento humano e podem representar oportunidades para a oferta de produtos?**

Além disso, o projeto procura compreender:

- Quais estados apresentam as maiores médias municipais de IDHM?
- Quais regiões brasileiras apresentam os melhores indicadores?
- Como educação, renda e longevidade se relacionam?
- Quais municípios apresentam os maiores e menores índices de desenvolvimento humano?
- Como os indicadores se distribuem entre diferentes regiões brasileiras?

## 🛠️ Tecnologias utilizadas

- **Python:** linguagem principal do projeto.
- **Pandas:** manipulação, organização e análise de dados.
- **NumPy:** suporte a operações numéricas.
- **Matplotlib:** construção e personalização de gráficos.
- **Seaborn:** visualizações estatísticas, distribuições e correlações.
- **Plotly Express:** desenvolvimento de gráficos interativos.
- **Jupyter Notebook / Google Colab:** ambientes para desenvolvimento e execução das análises.

## 📂 Etapas da análise

### 1. Importação e exploração dos dados

- Leitura da base de dados do IDHM de 2010.
- Identificação da quantidade de linhas e colunas do dataset.
- Verificação dos tipos de dados.
- Identificação de valores ausentes.
- Análise de valores únicos e estrutura das variáveis.

### 2. Preparação e organização dos dados

- Seleção das variáveis relevantes para a análise.
- Padronização dos nomes das colunas.
- Organização dos indicadores de IDHM, educação, longevidade e renda.
- Criação de categorias de desenvolvimento humano.
- Mapeamento dos estados para suas respectivas regiões brasileiras.
- Agrupamento de dados municipais para análises estaduais e regionais.

### 3. Análise estatística

- Cálculo de estatísticas descritivas.
- Análise de médias, valores mínimos, máximos e dispersão.
- Classificação dos municípios conforme o IDHM.
- Cálculo de médias municipais agrupadas por estado.
- Comparação dos indicadores entre as regiões brasileiras.
- Investigação das relações entre renda, educação e longevidade.

### 4. Visualização e exploração dos dados

Foram desenvolvidas diferentes visualizações para facilitar a interpretação dos indicadores socioeconômicos.

**Gráficos de barras**
- Comparação do IDHM médio municipal entre estados.
- Ordenação dos estados por desempenho.
- Comparação dos indicadores de educação, longevidade e renda.
- Visualização do IDHM médio por região brasileira.

**Gráficos interativos com Plotly**
- Comparação dos indicadores estaduais.
- Representação visual das classificações de desenvolvimento humano.

**Pairplots**
- Exploração das relações entre os indicadores.
- Comparação visual das dimensões de desenvolvimento humano.
- Identificação de possíveis padrões e associações.

**Heatmaps de correlação**
- Construção de matrizes de correlação entre educação, renda e longevidade.
- Comparação das correlações nos níveis municipal e estadual.

**Boxplots**
- Análise da dispersão do IDHM entre municípios.
- Comparação das distribuições por estado.
- Identificação de diferenças na distribuição do IDHM entre regiões.

**Gráficos de dispersão**
- Investigação da relação entre IDHM Educação e IDHM Renda.
- Inclusão de linha de tendência para facilitar a interpretação.

## 📈 Classificação do IDHM

O IDHM varia de 0 a 1. Quanto mais próximo de 1, maior o nível de desenvolvimento humano.

Para esta análise, foram utilizadas as seguintes faixas de classificação:

| IDHM | Classificação |
|---|---|
| 0 a 0,499 | Baixo Desenvolvimento Humano |
| 0,500 a 0,799 | Médio Desenvolvimento Humano |
| 0,800 a 1,000 | Alto Desenvolvimento Humano |

Essas faixas representam a classificação simplificada implementada neste projeto.

## 🔍 Principais análises

### 1. Comparação do IDHM por estado

Agrupamento dos municípios por Unidade da Federação (UF), utilizando a média simples dos valores municipais de IDHM.

A análise permite comparar os estados brasileiros, identificar diferenças entre os valores médios calculados e visualizar rankings estaduais.

**Observação:** essas médias não correspondem necessariamente aos indicadores oficiais de IDHM ou IDH estadual, pois representam médias aritméticas dos municípios.

### 2. Análise regional do desenvolvimento humano

Organização dos estados nas cinco regiões brasileiras:

- Norte
- Nordeste
- Centro-Oeste
- Sudeste
- Sul

Cálculo e comparação das médias municipais de IDHM agrupadas por região, utilizando gráficos de barras e boxplots para explorar diferenças regionais.

### 3. Análise das dimensões do IDHM

Comparação dos indicadores de:

- **IDHM Educação:** avaliação das diferenças educacionais entre estados.
- **IDHM Longevidade:** comparação dos indicadores associados à expectativa de vida.
- **IDHM Renda:** investigação das diferenças econômicas entre estados.

Os resultados são apresentados em gráficos comparativos, incluindo rankings ordenados.

### 4. Análise de correlação

Utilização de matrizes de correlação e gráficos de dispersão para investigar associações entre as dimensões do IDHM.

Destaque para a análise da relação entre **educação e renda**, buscando compreender como esses indicadores variam conjuntamente nos municípios brasileiros.

### 5. Ranking dos municípios

Identificação dos:

- 10 municípios com os maiores valores de IDHM.
- 10 municípios com os menores valores de IDHM.

A análise considera os valores municipais da base de 2010, permitindo identificar os extremos da distribuição.

## 🚀 Como executar

### 1. Clonar o repositório

```bash
git clone https://github.com/vilhegas/Analise_Exploratoria_de_Dados_EDA-IDHM_Brasil.git
```

### 2. Acessar a pasta do projeto

```bash
cd Analise_Exploratoria_de_Dados_EDA-IDHM_Brasil
```

### 3. Instalar as dependências

```bash
pip install pandas numpy matplotlib seaborn plotly xlrd nbformat ipython
```

### 4. Preparar a base de dados

Utilize a base `IDH_2010.xls` disponibilizada pelo IPEA.

O código utiliza o seguinte caminho relativo:

```python
idhm = pd.read_excel("data/IDH_2010.xls")
```

Portanto, o arquivo deve estar localizado na pasta `data` do projeto.

### 5. Executar a análise

Abra o notebook no Jupyter Notebook ou no VS Code e execute as células na sequência.

Também é possível utilizar o Google Colab, ajustando o caminho do arquivo de dados quando necessário.

## 📚 Fontes dos dados

- [PNUD Brasil — O que é o IDHM?](https://www.undp.org/pt/brazil/o-que-%C3%A9-o-idhm)
- [IPEA — Base de dados IDH 2010](https://www.ipea.gov.br/ipeageo/arquivos/bases/IDH_2010.xls)

## 📌 Considerações finais

Este projeto demonstra a aplicação prática de técnicas de **Análise Exploratória de Dados (EDA)**, abrangendo desde a importação e preparação das informações até a construção de análises estatísticas e visualizações gráficas.

A utilização de Python e bibliotecas como Pandas, Matplotlib, Seaborn e Plotly permite explorar diferentes dimensões do desenvolvimento humano brasileiro, identificar padrões e analisar desigualdades entre municípios, estados e regiões.

Além de contribuir para o estudo de indicadores socioeconômicos, o projeto exemplifica como a análise de dados pode apoiar a investigação de mercados e a identificação inicial de oportunidades, considerando as limitações dos indicadores utilizados.

**Observação:** os dados utilizados são referentes a 2010. Portanto, as análises possuem caráter histórico e exploratório, não representando necessariamente a situação socioeconômica atual do Brasil.

---

**Desenvolvido com Python | Data Analytics | Data Science | Exploratory Data Analysis (EDA)**