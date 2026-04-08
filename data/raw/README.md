# data/raw

Este diretório contém dados brutos, exatamente como foram obtidos da fonte original, sem nenhum processamento ou transformação.

## Organização

Cada conjunto de dados deve ter seu próprio subdiretório:

```
data/raw/
└── <nome-do-dataset>/
    ├── README.md   # Descrição, fonte e instruções de obtenção
    └── ...         # Arquivos de dados
```

## Notas

- Não modifique os arquivos neste diretório. Mantenha os dados no estado original.
- Se um conjunto de dados for muito grande para o Git, documente as instruções de download no `README.md` do dataset.
