# 📚 Estudos de Ciência de Dados com Python

Notebooks dos meus estudos de Python para análise de dados. O principal é a **Imersão Dados com Python (Alura, 2026)**, em que analisei uma base de **133.349 salários** da área de dados, passando por exploração, limpeza e visualização.

## 💼 Imersão Dados com Python: salários na área de dados

**Notebook:** [`Imersão_dados_com_Python_Alura2026.ipynb`](Imers%C3%A3o_dados_com_Python_Alura2026.ipynb) · [abrir no Colab](https://colab.research.google.com/github/taniamiguel/Data-Science/blob/main/Imers%C3%A3o_dados_com_Python_Alura2026.ipynb)

### Perguntas
- Quanto ganha um profissional de dados em cada nível de senioridade?
- Qual é a proporção de trabalho presencial, remoto e híbrido?
- Como os salários se distribuem e onde estão os valores fora do padrão?

### Principais resultados

| Senioridade | Salário médio anual (USD) |
|---|---:|
| Júnior | 99.035 |
| Pleno | 143.045 |
| Sênior | 172.851 |
| Executivo | 202.028 |

- O salário médio **dobra** do nível júnior para o executivo.
- **79%** das vagas são presenciais, **21%** remotas e só **0,2%** híbridas.
- **99,4%** dos contratos são em tempo integral.

### O que foi feito

| Etapa | Técnicas |
|---|---|
| **1. Exploração** | `head`, `info`, `describe`, `shape` e `value_counts` para entender a base |
| **2. Padronização** | Renomeação das colunas para português e tradução de códigos (`SE` → Sênior, `FT` → integral, `100` → remoto) com `replace` e dicionários |
| **3. Limpeza** | Identificação de valores nulos (`isnull().sum()`), comparação de estratégias de preenchimento (média, mediana, `ffill`, `bfill`, `fillna`), remoção das 10 linhas sem ano com `dropna` e conversão de tipo com `astype('Int64')` |
| **4. Visualização** | Gráficos de barras, histograma e boxplot com **Matplotlib** e **Seaborn**, e gráficos interativos (barras, pizza e mapa) com **Plotly** |
| **5. Enriquecimento** | Conversão do código do país de ISO-2 para ISO-3 com **pycountry**, para montar o mapa de salários por país |

### Ferramentas
Python · Pandas · NumPy · Matplotlib · Seaborn · Plotly · pycountry · Google Colab

**Dados:** [salaries.csv](https://raw.githubusercontent.com/guilhermeonrails/data-jobs/refs/heads/main/salaries.csv), base pública usada na Imersão.

## 🧩 Outros arquivos

| Arquivo | Conteúdo |
|---|---|
| [`Python_primeirospassos.ipynb`](Python_primeirospassos.ipynb) | Lógica de programação em Python: variáveis, funções, parâmetros, condicionais e conversão de tipos |
| [`Plototipagem de Dados com Python.py`](Plototipagem%20de%20Dados%20com%20Python.py) | Primeiro gráfico de linha com Matplotlib |

---
Projetos aplicados a problemas reais: veja o [meu perfil](https://github.com/taniamiguel) · [LinkedIn](https://www.linkedin.com/in/taniamiguel)
