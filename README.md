# Projeto de Análise de Dados em Logística

## Descrição
Este projeto visa analisar dados de logística, focando em Gestão de Estoque, Otimização de Rotas e Performance de Entregas e Devoluções.

## Estrutura do Projeto

projeto_supply_chain_data/
├── data/               # Todos os dados (brutos e processados)
│   ├── supply_chain_data.csv  # Dados originais
├── scripts/            # Scripts Python para processamento, análise de dados e geração de relatórios
│   ├── gerar_dados_sujos.py  # Script para inserir inconsistências
│   ├── processo_etl.py       # Script para o processo de ETL
├── visualizations/     # Visualizações e dashboards
├── env/                # Ambiente virtual
├── README.md           # Descrição do projeto
├── requirements.txt    # Lista de dependências
└── .gitignore          # Arquivo para ignorar arquivos desnecessários no Git


## Configuração do Ambiente

1. Instale o Python 3.11.0.
2. Crie um ambiente virtual e ative-o:
    ```bash
    python -m venv env
    .\env\Scripts\activate
    ```

## Instalação das Dependências

Instale as bibliotecas necessárias:
    ```bash
    pip install -r requirements.txt
    ```

## Execução do Projeto

1. Coloque o arquivo `supply_chain_data.csv` na pasta `data/`.
2. Execute o script `gerar_dados_sujos.py` para inserir inconsistências nos dados:
    ```bash
    python scripts/gerar_dados_sujos.py
    ```
3. Execute o script `processo_etl.py` para realizar o processo de ETL:
    ```bash
    python scripts/processo_etl.py
    ```

## Objetivos do Projeto

- **Gestão de Estoque**: Analisar e otimizar o inventário.
- **Otimização de Rotas**: Melhorar a eficiência das rotas de entrega.
- **Performance de Entregas**: Avaliar e aprimorar o desempenho das entregas.

## Resultados

Os resultados serão apresentados em relatórios e dashboards na pasta `visualizations/`.

## Contribuição

Sinta-se à vontade para contribuir com melhorias e novas análises.
