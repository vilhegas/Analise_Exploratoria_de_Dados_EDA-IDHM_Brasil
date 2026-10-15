# 📊 Análise Exploratória de Dados (EDA) — IDHM Brasil

## 📌 Sobre o projeto

Este projeto apresenta uma **Análise Exploratória de Dados (EDA)** do Índice de Desenvolvimento Humano Municipal (IDHM) brasileiro, utilizando Python e bibliotecas de análise e visualização de dados.

A análise utiliza dados disponibilizados pelo Instituto de Pesquisa Econômica Aplicada (IPEA), com o objetivo de compreender o desenvolvimento humano dos municípios e estados brasileiros, considerando três dimensões fundamentais: **educação, longevidade e renda**.

## 🎯 Objetivo

Investigar os indicadores de desenvolvimento humano no Brasil, buscando responder à seguinte pergunta norteadora:

**Quais estados brasileiros apresentam melhores indicadores de desenvolvimento humano e podem representar oportunidades para a oferta de produtos?**

## 🛠️ Tecnologias utilizadas

- **Python:** linguagem principal do projeto.
- **Pandas:** manipulação, tratamento e análise de dados.
- **NumPy:** suporte a operações numéricas.
- **Matplotlib:** criação de gráficos.
- **Seaborn:** visualização estatística dos dados.
- **Plotly Express:** biblioteca importada para visualização de dados.
- **Google Colab:** ambiente utilizado no desenvolvimento.

## 📂 Etapas da análise

### 1. Importação e exploração dos dados
- Leitura da base de dados do IDHM de 2010.
- Identificação das dimensões do dataset.
- Verificação dos tipos de dados.
- Identificação de valores nulos e valores únicos.

### 2. Preparação dos dados
- Seleção das variáveis relevantes.
- Padronização dos nomes das colunas.
- Organização dos indicadores de IDHM, educação, longevidade e renda.

### 3. Análise estatística
- Cálculo de estatísticas descritivas.
- Análise da distribuição dos indicadores.
- Classificação dos municípios por nível de desenvolvimento humano.
- Agrupamento dos dados por estado e cálculo da média do IDHM municipal.

### 4. Visualização dos dados
- Utilização de gráficos Pairplot para investigar relações entre variáveis.
- Análise da relação entre educação e renda.
- Construção de Boxplot para visualizar a distribuição dos valores médios estaduais de IDHM.

## 📈 Classificação do IDHM

O IDHM varia de 0 a 1. Quanto mais próximo de 1, maior o nível de desenvolvimento humano.

Para esta análise, foram utilizadas as seguintes faixas de classificação:

| IDHM | Classificação |
|---|---|
| 0 a 0,499 | Baixo Desenvolvimento Humano |
| 0,500 a 0,799 | Médio Desenvolvimento Humano |
| 0,800 a 1,000 | Alto Desenvolvimento Humano |

## 🔍 Principais análises

O projeto permite explorar:

- A distribuição do IDHM entre os municípios brasileiros.
- A relação entre os indicadores de educação, renda e longevidade.
- As diferenças entre as médias municipais de IDHM dos estados brasileiros.
- A classificação dos estados conforme os valores médios calculados.

## 🚀 Como executar

1. Faça o clone do repositório.
2. Instale as bibliotecas necessárias:

   ```bash
   pip install pandas numpy matplotlib seaborn plotly xlrd
   ```

3. Baixe a base de dados `IDH_2010.xls` disponibilizada pelo IPEA.
4. Coloque o arquivo na pasta de execução do projeto.
5. Execute o script Python ou utilize o Google Colab.

**Observação:** a análise utiliza dados referentes a 2010, portanto não representa necessariamente a situação atual do desenvolvimento humano brasileiro.

## 📚 Fonte dos dados

- [PNUD Brasil — O que é o IDHM?](https://www.undp.org/pt/brazil/o-que-%C3%A9-o-idhm)
- [IPEA — Base de dados IDH 2010](https://www.ipea.gov.br/ipeageo/arquivos/bases/IDH_2010.xls)

## 📌 Considerações finais

Este projeto demonstra a aplicação de técnicas de **Análise Exploratória de Dados**, desde a compreensão e preparação do dataset até a produção de estatísticas e visualizações.

A análise contribui para a identificação de padrões de desenvolvimento humano entre diferentes regiões do Brasil e exemplifica como dados socioeconômicos podem apoiar estudos e análises de mercado.

---

**Desenvolvido com Python | Data Analytics | Data Science | EDA**
