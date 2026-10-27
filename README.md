Análise de Dados do PIX com PySpark
---

Este projeto utiliza PySpark para processar e analisar um conjunto de dados públicos sobre transações realizadas via PIX. O objetivo é entender o comportamento das transações, agregando informações por região, ano, mês e por tipo de pessoa (PF/PJ), além de calcular indicadores como valores pagos, recebidos e quantidade de usuários envolvidos.

📊 O que o notebook faz:
---

- Lê arquivos CSV contendo dados das transações PIX.

- Realiza limpeza e transformação das colunas (datas, valores numéricos, formatação).

- Aplica agregações com PySpark, como:

- Soma de valores pagos e recebidos.

- Contagem de pagadores e recebedores PF/PJ.

- Métricas agrupadas por região, ano e mês.

- Exibe os resultados em DataFrames organizados para análise.

🧰 Tecnologias utilizadas
---

- PySpark

- Databricks

✔️ Resultado
---

Ao final, o notebook apresenta tabelas com métricas sumarizadas das transações PIX, permitindo compreender padrões, volumes e comportamentos relevantes do uso do sistema de pagamentos instantâneos no Brasil.
