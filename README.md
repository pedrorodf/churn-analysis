# Análise de cancelamento de clientes

Projeto de análise exploratória de dados com Python para investigar o cancelamento de clientes (*churn*) e visualizar características associadas a esse comportamento.

## Conteúdo

- `analysis.ipynb`: notebook com a leitura, preparação e análise dos dados, incluindo gráficos interativos.
- `cancelamentos.csv`: arquivo de entrada esperado pelo notebook; não é incluído no repositório por conter identificadores e registros em nível de cliente.

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

4. Obtenha uma cópia autorizada e adequadamente anonimizada da base, salve-a como `cancelamentos.csv` na mesma pasta do notebook e execute as células.

## Estrutura dos dados

A base esperada contém informações como idade, sexo, tempo como cliente, frequência de uso, ligações ao call center, dias de atraso, tipo de assinatura, duração do contrato, gasto total, tempo desde a última interação e indicador de cancelamento.

## Privacidade dos dados

O CSV original contém a coluna `CustomerID` e registros em nível de cliente. Por isso, `cancelamentos.csv` e `.venv` são excluídos do versionamento. Não publique a base em outro local sem confirmar que você tem autorização para compartilhá-la e que os dados foram adequadamente anonimizados. O notebook remove o identificador em uma etapa da análise, mas isso não remove os identificadores do arquivo CSV original.
