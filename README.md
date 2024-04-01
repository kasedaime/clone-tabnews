# Clone-tabnews

Implementação educacional do tabnews.com.br

## Instalação Test Runner

Runner usado: `Jest`

Outras opções:

- Mocha, AVA, PlayWright

Instalação: `npm install --save-dev jest@29.6.2`

How to run: `npm run test` or `npm test`

### Usar o curl para obter informações sobre os nossos endpoints

Command example: `curl http://localhost:3000/api/status --verbose`

## Database Configuration

- Postgres
- pg (node-postgres) para query

## Docker Configuration

File `compose.yaml` in the root, is the docker configuration file.

#### Commands

- docker compose up (levanta contexto do docker configurado)
- docker ps -a (lista o estado de todos os containers)
- docker compose --detach / -d (run in background)
- docker compose up -d --force-recreate (reinicia para actualizar)

Instalar o cliente postgresql (psql)

`sudo apt install postgresql-client`

passar as credenciais psql pela linha de comando:  
 `psql --host=localhost --username=postgres --port=5432`
