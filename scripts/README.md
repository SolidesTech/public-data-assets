# Scripts

Este diretório contém scripts para coleta, limpeza e transformação dos conjuntos de dados.

## Organização

```
scripts/
└── <nome-do-dataset>/
    ├── download.py    # Script para baixar dados da fonte original
    ├── process.py     # Script para limpar e transformar os dados brutos
    └── README.md      # Instruções de uso dos scripts
```

## Requisitos

Para executar os scripts, instale as dependências necessárias:

```bash
pip install -r requirements.txt
```

> **Nota:** Um arquivo `requirements.txt` será adicionado conforme os scripts forem incluídos.

## Como Executar

```bash
# Baixar dados brutos
python scripts/<nome-do-dataset>/download.py

# Processar dados
python scripts/<nome-do-dataset>/process.py
```
