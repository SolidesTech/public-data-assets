# data/processed

Este diretório contém dados que já passaram por algum processo de limpeza, transformação ou enriquecimento, prontos para uso em análises e modelos.

## Organização

Cada conjunto de dados deve ter seu próprio subdiretório:

```
data/processed/
└── <nome-do-dataset>/
    ├── README.md   # Descrição das transformações aplicadas e dicionário de variáveis
    └── ...         # Arquivos de dados processados
```

## Notas

- Os dados processados devem ser reproduzíveis a partir dos dados brutos usando os scripts em `scripts/`.
- Prefira formatos abertos como CSV, JSON ou Parquet.
