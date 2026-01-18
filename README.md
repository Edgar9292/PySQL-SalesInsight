# PySQL-SalesInsight: Pipeline de Dados e Analytics 🚀

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-CC2927?style=for-the-badge&logo=postgresql&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white)

## Sobre o Projeto
O **PySQL-SalesInsight** é um projeto de Engenharia e Análise de Dados que demonstra a integração entre **Python** e **SQL**. O objetivo é simular um cenário real de negócios onde dados brutos de vendas são extraídos, tratados e carregados em um banco de dados relacional para a geração de métricas estratégicas.

##  Tecnologias Utilizadas
- **Python**: Motor de ETL (Extract, Transform, Load).
- **Pandas**: Manipulação e limpeza de dados.
- **SQLAlchemy**: Interface de conexão entre Python e Banco de Dados.
- **SQLite/PostgreSQL**: Armazenamento e consultas analíticas.
- **SQL Avançado**: Uso de Window Functions e CTEs para relatórios.

##  Fluxo de Trabalho (Pipeline)
1. **Extração**: Leitura de fontes de dados (CSV/JSON) simulando transações de vendas.
2. **Transformação**: Limpeza de dados nulos, padronização de datas e cálculo de valores brutos via Python.
3. **Carga**: Exportação dos dados estruturados para tabelas SQL otimizadas.
4. **Análise**: Execução de queries complexas para extrair insights como Ranking de Clientes e Média Móvel de Faturamento.

##  Estrutura do Repositório
- `/scripts`: Scripts Python para automação do pipeline.
- `/queries`: Arquivos `.sql` com as análises de performance.
- `/database`: Local onde o banco de dados é gerado.

## Insights Gerados
Através das queries SQL desenvolvidas, o projeto entrega:
- **Ranking de Clientes (RFM)**: Identificação dos compradores mais valiosos.
- **Participação de Mercado**: Percentual de faturamento por categoria de produto.
- **Sazonalidade**: Análise de tendências de vendas ao longo do tempo.

---
##  Como Executar
1. Clone o repositório:
   ```bash
   git clone [https://github.com/seu-usuario/PySQL-SalesInsight.git](https://github.com/seu-usuario/PySQL-SalesInsight.git)
