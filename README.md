# Relatórios de Análise de Dados

Pequeno projeto de análise exploratória de dados feito em **Jupyter Notebook**, usando **Python**, **pandas** e **seaborn**. Cada relatório lê uma base de dados em CSV, mostra sua estrutura e gera gráficos simples para entender melhor as informações.

## Estrutura do projeto

| Notebook | Base de dados | O que analisa |
|---|---|---|
| `relatorio-eletronicos.ipynb` | `vendas_eletronicos.csv` | Vendas de produtos eletrônicos (categoria, preço, quantidade, região, canal de venda e avaliação) |
| `relatorio-maquinas.ipynb` | `monitoramento_maquinas.csv` | Monitoramento de máquinas industriais (temperatura, consumo de energia, peças produzidas e defeituosas, tempo de parada) |
| `relatorio-estudantes.ipynb` | `student_habits_performance.csv` | Hábitos de estudantes e sua relação com a nota em exames |

## O que cada relatório faz

### Eletrônicos
- Exibe os primeiros e últimos registros, além de estatísticas gerais (`head`, `tail`, `describe`, `info`).
- Gráfico de barras com as **categorias mais vendidas**.
- Boxplot do **preço unitário por categoria**.

### Máquinas
- Exibe os primeiros e últimos registros, além de estatísticas gerais.
- Histograma dos **registros de temperatura** (°C).

### Estudantes
- Mostra as informações gerais da tabela (`info`).
- Mapa de calor com a **correlação** entre idade, horas de estudo, redes sociais, Netflix, frequência, sono, exercícios, saúde mental e nota final.

## Como executar

1. Instale as dependências:
   ```bash
   pip install pandas seaborn jupyter
   ```
2. Mantenha os notebooks e os arquivos `.csv` na **mesma pasta**.
3. Abra o Jupyter:
   ```bash
   jupyter notebook
   ```
4. Execute as células de cada notebook em ordem.

## Tecnologias

- Python
- pandas
- seaborn
- Jupyter Notebook