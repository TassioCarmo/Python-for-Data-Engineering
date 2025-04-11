# Python para Engenharia de Dados | Python for Data Engineering

Este repositório contém atividades, projetos e exercícios desenvolvidos na disciplina de **Python Aplicado à Engenharia de Dados**, parte da pós-graduação em Engenharia de Dados. O conteúdo aqui apresentado tem como objetivo consolidar o domínio da linguagem Python e de suas principais bibliotecas voltadas para a manipulação, transformação, análise e visualização de dados.

## Sobre a Disciplina | About the Course

Ao longo da disciplina, foram abordados conceitos fundamentais da linguagem, estruturas de dados, orientação a objetos, manipulação de arquivos, integração com APIs, automação de tarefas e, principalmente, uso de bibliotecas amplamente adotadas no ecossistema de dados, como:

- `pandas`: análise e manipulação de dados estruturados
- `numpy`: computação numérica e operações matemáticas avançadas
- `matplotlib` e `seaborn`: visualização de dados e criação de gráficos interativos
- `requests` e `json`: consumo de APIs e processamento de dados em formato JSON
- `sqlalchemy` e `sqlite3`: integração com bancos de dados relacionais
- `openpyxl`: manipulação de arquivos Excel
- `pyspark`: processamento de dados em larga escala
- `airflow`: orquestração de pipelines de dados

Este portfólio serve como uma vitrine prática das competências desenvolvidas com Python na área de dados, com foco em problemas reais, clareza de código, boas práticas e documentação.

## Objetivos da Disciplina | Course Objectives

- Aprender os fundamentos da linguagem Python com foco em aplicações para dados
- Automatizar tarefas rotineiras de processamento de dados
- Realizar limpeza, transformação e análise exploratória de dados
- Gerar relatórios e visualizações para apoiar a tomada de decisão
- Integrar Python a fontes de dados externas (APIs, arquivos, bancos de dados)
- Implementar pipelines de dados escaláveis e robustos
- Aplicar boas práticas de desenvolvimento e documentação de código

## Público-alvo | Target Audience

Profissionais e estudantes da área de tecnologia que desejam atuar em cargos como:

- Engenheiro de Dados
- Cientista de Dados
- Analista de Dados
- Desenvolvedor Python
- Arquiteto de Soluções de Dados
- Especialista em ETL/ELT

## Aplicabilidade no Mercado | Market Relevance

O domínio da linguagem Python é hoje uma das competências mais requisitadas no mercado de dados. Esta disciplina prepara o profissional para atuar em ambientes onde é necessário construir pipelines de dados, realizar análises automatizadas, comunicar resultados de forma visual e integrar sistemas diversos, sempre utilizando a linguagem mais popular do ecossistema de Data Science e Big Data.

Segundo pesquisas recentes, Python continua sendo a linguagem preferida para projetos de dados, com mais de 70% dos profissionais da área utilizando-a como principal ferramenta.

## Estrutura do Repositório | Repository Structure

```
python-para-engenharia-dados/
├── projetos/                      # Projetos completos de engenharia de dados
│   ├── pipeline_etl/              # Pipeline ETL completo
│   ├── api_integration/           # Integração com APIs públicas 
│   └── data_analysis/             # Análise exploratória de dados
│
├── exercicios/                    # Exercícios práticos organizados por tema
│   ├── fundamentos/               # Exercícios sobre fundamentos de Python
│   ├── pandas/                    # Exercícios com a biblioteca pandas
│   ├── visualizacao/              # Exercícios de visualização de dados
│   └── banco_dados/               # Exercícios de integração com bancos de dados
│
├── notebooks/                     # Jupyter notebooks com exemplos e tutoriais
│   ├── introducao_python.ipynb    # Introdução à linguagem Python
│   ├── pandas_tutorial.ipynb      # Tutorial de pandas
│   ├── visualizacao_dados.ipynb   # Visualização de dados com matplotlib/seaborn
│   └── api_requests.ipynb         # Consumo de APIs com Python
│
├── datasets/                      # Conjuntos de dados utilizados nos exercícios
│
├── utils/                         # Funções auxiliares e utilitários
│
├── requirements.txt               # Dependências do projeto
├── setup.py                       # Script de instalação
└── README.md                      # Este arquivo
```

## Projetos Destacados | Featured Projects

### 1. Pipeline ETL para Dados de E-commerce

Implementação de um pipeline completo de extração, transformação e carregamento de dados de e-commerce, incluindo:
- Extração de dados de múltiplas fontes (API, CSV, banco de dados)
- Transformação e limpeza usando pandas
- Carregamento em data warehouse
- Orquestração com Apache Airflow

### 2. Dashboard de Análise de Dados Financeiros

Criação de um dashboard interativo para análise de dados financeiros com:
- Consumo de API de dados financeiros
- Processamento com pandas e numpy
- Visualização com matplotlib, seaborn e plotly
- Geração de relatórios automatizados

### 3. Sistema de Recomendação de Produtos

Desenvolvimento de um sistema básico de recomendação com:
- Análise de comportamento de usuários
- Processamento de dados de transações
- Algoritmos simples de recomendação
- API RESTful para servir as recomendações

## Tópicos Abordados | Topics Covered

1. **Fundamentos de Python**
   - Tipos de dados, estruturas e operações
   - Funções e módulos
   - Orientação a objetos
   - Manipulação de arquivos

2. **Bibliotecas para Engenharia de Dados**
   - pandas: manipulação e análise de dados
   - numpy: computação numérica
   - SQLAlchemy: integração com bancos de dados

3. **Visualização de Dados**
   - matplotlib: gráficos estáticos
   - seaborn: visualizações estatísticas
   - plotly: gráficos interativos

4. **Integração com Fontes de Dados**
   - APIs REST
   - Bancos de dados relacionais
   - Arquivos CSV, JSON, Excel, Parquet

5. **Boas Práticas de Desenvolvimento**
   - Estruturação de projetos
   - Testes unitários com pytest
   - Documentação de código
   - Controle de versão com Git

6. **Introdução a Big Data com Python**
   - PySpark: processamento distribuído
   - Dask: paralelização de tarefas

## Como Utilizar | How to Use

### Pré-requisitos

- Python 3.8 ou superior
- pip (gerenciador de pacotes Python)
- Git para clonar o repositório

### Instalação

1. Clone este repositório:
   ```bash
   git clone https://github.com/seu-usuario/python-para-engenharia-dados.git
   cd python-para-engenharia-dados
   ```

2. Crie e ative um ambiente virtual:
   ```bash
   python -m venv venv
   source venv/bin/activate  # No Windows: venv\Scripts\activate
   ```

3. Instale as dependências:
   ```bash
   pip install -r requirements.txt
   ```

4. Execute os notebooks ou scripts:
   ```bash
   jupyter notebook notebooks/
   # ou
   python projetos/pipeline_etl/main.py
   ```

## Resultados de Aprendizagem | Learning Outcomes

Ao final desta disciplina, os estudantes serão capazes de:

- Desenvolver pipelines de ETL robustos utilizando Python
- Aplicar técnicas de análise exploratória de dados com pandas
- Criar visualizações informativas com matplotlib e seaborn
- Integrar Python com diferentes tipos de bancos de dados
- Consumir e processar dados de APIs externas
- Automatizar tarefas de processamento de dados
- Implementar soluções escaláveis para problemas de engenharia de dados


O projeto final consistiu na implementação de um pipeline de dados completo, desde a extração até a visualização, aplicando os conhecimentos adquiridos durante o curso.

## Recursos Adicionais | Additional Resources

- [Documentação oficial do Python](https://docs.python.org/3/)
- [Documentação do pandas](https://pandas.pydata.org/docs/)
- [Tutorial de PySpark](https://spark.apache.org/docs/latest/api/python/)
- [Cursos online recomendados](https://www.datacamp.com/tracks/data-engineer-with-python)
- [Comunidade Python para Dados - Discord](https://discord.gg/python-data)

