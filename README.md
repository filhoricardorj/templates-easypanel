# Templates EasyPanel

Repositório de templates para EasyPanel.

## N8N

### Base (`base.json`)
- **Versão**: N8N Stable, Postgres 17 (pgvector), Redis 7
- **Contém**:
  - Postgres (com pgvector)
  - Redis
  - N8N Editor
  - N8N Webhooks
  - N8N Worker
- **Descrição**: Setup completo e escalável do N8N com serviços separados para editor, webhooks e workers.

### Word Extract Server (`word-extract-server.json`)
- **Versão**: Python 3.11
- **Contém**: API FastAPI customizada
- **Descrição**: Servidor para extração de texto de arquivos Word (.doc e .docx), utilizando `antiword` e `python-docx`.

## Links
- [Diretório N8N](https://github.com/filhoricardorj/templates-easypanel/tree/main/n8n)