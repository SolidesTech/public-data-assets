# Contribuindo com o public-data-assets

Obrigado pelo interesse em contribuir! Este guia explica como colaborar com este repositório de ativos de dados públicos.

## Como Contribuir

### 1. Reportar Problemas

Se encontrar dados incorretos, desatualizados ou ausentes, abra uma _issue_ descrevendo:
- O conjunto de dados afetado
- O problema encontrado
- Sugestão de correção (se houver)

### 2. Adicionar um Novo Conjunto de Dados

1. Faça um _fork_ do repositório e crie um branch descritivo:
   ```bash
   git checkout -b add/<nome-do-dataset>
   ```

2. Coloque os arquivos de dados no local correto:
   - Dados brutos em `data/raw/<nome-do-dataset>/`
   - Dados processados em `data/processed/<nome-do-dataset>/`

3. Adicione documentação em `docs/<nome-do-dataset>.md` contendo:
   - Descrição do conjunto de dados
   - Fonte original e URL
   - Dicionário de variáveis (colunas e seus significados)
   - Frequência de atualização
   - Licença dos dados originais

4. Se aplicável, adicione o script de coleta/processamento em `scripts/`.

5. Atualize a tabela de **Conjuntos de Dados** no `README.md`.

6. Abra um _Pull Request_ com uma descrição clara das alterações.

### 3. Melhorar Scripts Existentes

- Siga as convenções de código já presentes no repositório.
- Adicione comentários explicativos quando necessário.
- Garanta que o script continue funcionando com os dados existentes.

## Padrões de Qualidade

- **Formatos preferidos:** CSV, JSON, Parquet (evite formatos proprietários).
- **Encoding:** UTF-8 para todos os arquivos de texto.
- **Nomes de arquivos:** letras minúsculas, sem espaços, use hífen (`-`) como separador.
- **Dados sensíveis:** nunca inclua dados pessoais ou confidenciais.

## Código de Conduta

Seja respeitoso e construtivo nas interações. Contribuições de todas as origens são bem-vindas.
