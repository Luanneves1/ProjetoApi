# Projeto API

Este é um projeto Node.js que utiliza Prisma para gerenciamento de banco de dados. O objetivo deste projeto é estudar e praticar a criação de APIs.

## Ferramentas Utilizadas

- **Node.js**: Plataforma de desenvolvimento que permite a execução de código JavaScript no lado do servidor.
- **Prisma**: ORM (Object-Relational Mapping) que facilita o gerenciamento de banco de dados.
- **MongoDB**: Banco de dados NoSQL utilizado para armazenar os dados da aplicação.

## Estrutura do Projeto

- **.env**: Arquivo de configuração de variáveis de ambiente.
- **.gitignore**: Arquivo que especifica quais arquivos e diretórios devem ser ignorados pelo Git.
- **package.json**: Arquivo de configuração do npm que lista as dependências do projeto e scripts.
- **prisma/**: Diretório que contém o esquema do Prisma.
  - **schema.prisma**: Arquivo de definição do esquema do banco de dados Prisma.
- **server.js**: Arquivo principal do servidor Node.js.

## Instalação

1. Clone o repositório:
    ```sh
    git clone <URL_DO_REPOSITORIO>
    cd <NOME_DO_REPOSITORIO>
    ```

2. Instale as dependências:
    ```sh
    npm install
    ```

3. Configure as variáveis de ambiente no arquivo `.env`.

## Uso

Para iniciar o servidor, execute:
```sh
npm start

Prisma
Para rodar as migrações do Prisma, use:

Para abrir o Prisma Studio, use:

Scripts
npm start: Inicia o servidor.
npx prisma migrate dev: Executa as migrações do banco de dados.
npx prisma studio: Abre o Prisma Studio para gerenciar os dados.
Contribuição
Faça um fork do projeto.
Crie uma nova branch (git checkout -b feature/nova-feature).
Faça commit das suas alterações (git commit -am 'Adiciona nova feature').
Faça push para a branch (git push origin feature/nova-feature).
Abra um Pull Request.

Licença

Este projeto está licenciado sob a licença Publica haha. Veja o arquivo LICENSE para mais detalhes.

Certifique-se de substituir `<URL_DO_REPOSITORIO>` e `<NOME_DO_REPOSITORIO>` pelos valores apropriados.
