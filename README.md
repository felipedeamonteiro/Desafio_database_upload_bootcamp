# Gofinance - Backend

## Como rodar o projeto

Baixe o projeto na máquina e rode o comando `yarn` para que sejam instaladas suas dependências.

Primeiramente tem que rodar o docker com a imagem do Postgres que é a mesma utilizada no Gobarber, e para subir comece com o seguinte comando:

```
docker start gostack_postgres
```
Com isso o docker já estará rodando o banco de dados. Para acessar o banco de dados de maneira visual é só abrir o `DBeaver` e conectar o banco, lá já teremos o banco disponível da aplicação como `Desafio_6`.

Depois disso é só rodar o servidor local com:
```
yarn dev:server
```

Assim o servidor estará rodando na porta 3333 e a mensagem `Server started on port 3333!` irá aparecer no terminal, indicando que está tudo ok.
