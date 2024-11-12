# Projeto de Análise de Dados - COVID-19

Este projeto visa analisar e visualizar dados da pandemia de COVID-19, incluindo tendências de casos confirmados, buscando entender o impacto da pandemia em diferentes locais e identificar padrões significativos.

## Objetivos do Projeto

1. **Explorar e limpar os dados:** Preparar os dados para garantir que sejam confiáveis e estejam prontos para análise.
2. **Análise exploratória de dados (EDA):** Identificar padrões e insights iniciais sobre a evolução da pandemia em diferentes regiões.
3. **Visualizações:** Criar gráficos para representar a progressão dos casos, mortes e recuperações ao longo do tempo.
4. **Análise de correlação:** Avaliar se existem correlações entre variáveis, como a taxa de mortalidade e fatores como população ou densidade populacional.
5. **Clusterização dos dados** Utilização do modelo de machine learning para agrupamentos de dados correlatos.

## Fontes de Dados

Os dados utilizados neste projeto foram coletados a partir da seguinte fonte:

- [PNAD COVID-19](https://covid19.ibge.gov.br/pnad-covid/)

## Ferramentas e Bibliotecas Utilizadas

- **Python**: Linguagem de programação principal para análise e visualização.
- **Pandas**: Para manipulação e limpeza de dados.
- **Matplotlib & Seaborn**: Para visualizações.
- **NumPy**: Para cálculos e manipulações numéricas.
- **Plotly**: Para visualizações interativas.
- **SKLearn**: para criação do modelo de clusterização

## Estrutura do Projeto

```
├── datasets/                                # Dados brutos e processados
├── clustering_positivados.ipynb             # Notebook Jupyter para análise e visualização
├── README.md                                # Documentação do projeto
```

## Exemplos de Visualizações

- **Tendência de de fatores culturais e socioeconômico e **: Gráficos contendo informações sobre a demografía dos casos positivos.
- **Análise de correlação**: Um heatmap destacando a correlação entre variáveis relevantes.
- **Análise de Sintomas**: Gráficos de barra destacando os sintomas mais comuns dentre os casos positivos.

## Conclusões e Insights

- Este projeto fornece insights sobre o impacto em diferentes grupos.
- Possíveis correlações entre densidade populacional, fatores sociais e econômicos.
