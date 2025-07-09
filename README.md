# NLW Agents

Este projeto foi desenvolvido durante o evento NLW da Rocketseat.

## Descrição
API para gerenciamento de salas (rooms), utilizando Node.js, TypeScript e Drizzle ORM.

## Tecnologias e Bibliotecas Utilizadas
- **Node.js**
- **TypeScript**
- **Drizzle ORM** (mapeamento objeto-relacional)
- **SQLite** (banco de dados, configurado via Drizzle)
- **Zod** (validação de dados)
- **Fastify** (servidor HTTP)
- **dotenv** (variáveis de ambiente)

## Padrões de Projeto
- Organização em camadas: `http/routes`, `db/schema`, `db/migrations`
- Separação de responsabilidades para rotas, conexão com banco e schemas
- Uso de variáveis de ambiente para configuração

## Setup e Configuração

1. **Clone o repositório:**
   ```sh
   git clone <url-do-repo>
   cd nlw-agents
   ```
2. **Instale as dependências:**
   ```sh
   npm install
   ```
3. **Configure as variáveis de ambiente:**
   - Crie um arquivo `.env` baseado no exemplo fornecido (se houver).
4. **Execute as migrações do banco:**
   ```sh
   npx drizzle-kit migrate
   ```
5. **Inicie o servidor:**
   ```sh
   npm run dev
   ```

A API estará disponível em `http://localhost:3333`.

---
Projeto desenvolvido durante o evento NLW da Rocketseat.
