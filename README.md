 Ambiente Docker

Este projeto configura um ambiente Docker com PostgreSQL, MongoDB e uma aplicação Node.js.

Estrutura do Projeto
/ ├── postgres/ │   └── Dockerfile ├── mongodb/ │   └── Dockerfile ├── nodejs/ │   └── Dockerfile ├── docker-compose.yml └── README.md

 Como Executar
1. Certifique-se de que o Docker e o Docker Compose estão instalados.
2. Navegue até o diretório do projeto:
   ```bash
   cd C:\Users\vinib\OneDrive\Desktop\aula08-2204

   docker-compose up --build

   Serviços disponíveis:
- PostgreSQL: Porta 5432
- MongoDB: Porta 27017
- Node.js: Porta 3000

Salvar o Arquivo
Depois de escrever o conteúdo, salve o arquivo no mesmo diretório do seu projeto (C:\Users\vinib\OneDrive\Desktop\aula08-2204)
