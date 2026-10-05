# Análise de cancelamento de clientes

Projeto de análise exploratória de dados com Python para investigar o cancelamento de clientes (*churn*) e visualizar características associadas a esse comportamento.

## Conteúdo

- `analysis.ipynb`: notebook com a leitura, preparação e análise dos dados, incluindo gráficos interativos.
- `cancelamentos.csv`: base fictícia utilizada pelo notebook.

## Análises realizadas

- Leitura e inspeção da base com pandas.
- Remoção do identificador do cliente e tratamento de registros com valores ausentes.
- Contagem e cálculo da proporção de clientes que cancelaram.
- Visualização da distribuição de variáveis em relação ao cancelamento com Plotly.
- Avaliação de filtros relacionados à duração do contrato, ligações ao call center e dias de atraso.

## Requisitos

- Python 3
- pandas
- Plotly
- Jupyter Notebook

Instale as dependências com:

```bash
python -m pip install pandas plotly notebook
```

## Como executar

1. Clone ou baixe este projeto.
2. Na pasta do projeto, instale os requisitos.
3. Inicie o Jupyter:

   ```bash
   jupyter notebook
   ```

4. Execute as células do notebook. O arquivo `cancelamentos.csv` deve permanecer na mesma pasta.

## Estrutura dos dados

A base contém dados fictícios sobre idade, sexo, tempo como cliente, frequência de uso, ligações ao call center, dias de atraso, tipo de assinatura, duração do contrato, gasto total, tempo desde a última interação e indicador de cancelamento.

## Privacidade dos dados

Os dados desta base são fictícios. O notebook remove a coluna `CustomerID` durante a análise. O ambiente virtual `.venv` é excluído do versionamento.
