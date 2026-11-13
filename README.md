# Análise da Capacidade Hospitalar no Brasil — 2025

## Sobre o projeto

Este projeto tem como objetivo analisar a capacidade hospitalar brasileira em 2025, utilizando dados públicos de estabelecimentos de saúde e leitos hospitalares.

A análise foi desenvolvida no Microsoft Excel 2016, com tratamento e transformação dos dados no Power Query, construção de Tabelas Dinâmicas, elaboração de gráficos e criação de um resumo executivo.

O projeto busca transformar dados brutos em informações organizadas que facilitem a compreensão da distribuição dos leitos hospitalares no Brasil.

## Objetivos

- Analisar a evolução mensal dos leitos hospitalares ao longo de 2025.
- Comparar a capacidade hospitalar entre as regiões brasileiras.
- Investigar a distribuição dos leitos por tipo de estabelecimento.
- Analisar os leitos conforme a natureza jurídica dos hospitais.
- Avaliar a distribuição dos leitos de UTI por categoria.
- Construir um resumo executivo com indicadores e principais conclusões.

## Fonte dos dados

Os dados foram obtidos no portal OpenDataSUS, do Ministério da Saúde.

- **Fonte:** Hospitais e Leitos — OpenDataSUS
- **Link:** https://opendatasus.saude.gov.br/pt_BR/dataset/hospitais-e-leitos
- **Período analisado:** janeiro a dezembro de 2025.

## Ferramentas utilizadas

- **Microsoft Excel 2016:** organização, análise e visualização dos dados.
- **Power Query:** limpeza, transformação e preparação da base.
- **Tabelas Dinâmicas:** agregação e comparação dos indicadores.
- **Gráficos do Excel:** representação visual dos resultados.

## Tratamento e preparação dos dados

O processo de preparação incluiu:

- Remoção de uma coluna totalmente vazia.
- Seleção das colunas relevantes para as análises.
- Criação da coluna de data de competência a partir do campo `COMP`.
- Ajuste dos tipos de dados, incluindo identificadores tratados como texto.
- Verificação de valores ausentes e valores numéricos.
- Preservação de valores zero quando representavam ausência de leitos de determinada categoria.

## Análises desenvolvidas

### 1. Evolução mensal dos leitos

Análise mensal dos leitos hospitalares existentes e dos leitos SUS durante 2025.

![Evolução mensal](05%20-%20documentacao/02_evolucao_mensal.png)

### 2. Capacidade hospitalar por região

![Análise regional](05%20-%20documentacao/03_analise_regional.png)

Comparação dos leitos existentes e SUS entre as regiões brasileiras, considerando dezembro de 2025.

Também foi calculada a participação dos leitos SUS no total de leitos existentes de cada região.

### 3. Capacidade por tipo de estabelecimento

Comparação da quantidade de leitos existentes e SUS entre as categorias de estabelecimentos de saúde.

### 4. Capacidade por natureza jurídica

Análise da distribuição dos leitos entre hospitais públicos, filantrópicos e privados.

### 5. Análise dos leitos de UTI

![Análise dos leitos de UTI](05%20-%20documentacao/04_analise_uti.png)

Comparação dos leitos existentes e SUS nas categorias adulto, pediátrica, neonatal, queimados e coronariana, com referência a dezembro de 2025.

### 6. Resumo executivo

![Resumo executivo](05%20-%20documentacao/01_resumo_executivo.png)

Construção de um painel de apresentação com indicadores nacionais, gráfico regional e conclusões derivadas das análises.

## Principais indicadores

Referentes a dezembro de 2025:

| Indicador | Resultado |
|---|---:|
| Leitos hospitalares existentes | 522.386 |
| Leitos SUS | 352.906 |
| Participação dos leitos SUS | 67,56% |
| Leitos de UTI existentes | 65.433 |

## Aprendizados e competências demonstradas

- Limpeza e preparação de dados com Power Query.
- Tratamento de tipos de dados e criação de campos derivados.
- Construção e organização de Tabelas Dinâmicas.
- Utilização de agregações e cálculos percentuais.
- Criação de gráficos para comparação e análise de tendências.
- Comunicação de resultados por meio de um resumo executivo.

## Considerações finais

O projeto demonstra a aplicação prática do Excel na preparação, análise e visualização de dados públicos de saúde, com foco na transformação de dados em informações úteis para compreensão da capacidade hospitalar brasileira.

## Observação

Os resultados apresentados correspondem aos dados e às competências selecionadas para as análises. A interpretação dos indicadores deve considerar as definições e limitações da base original.
