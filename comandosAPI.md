# ENDPOINT 
O  endpoint é o URL onde o servidor REST está à escuta de solicitações.

# MÉTODO
O REST implementa diversos "métodos" para os diferentes tipos de solicitação, sendo os métodos abaixo os mais conhecidos:

- GET: obter (em inglês, get) recursos de um servidor.
- POST: criar (ou "publicar" - em inglês, post) recursos em um servidor.
- PATCH ou PUT: atualizar o recurso existente em um servidor.
- DELETE: excluir (em inglês, delete) um recurso de um servidor.

# CABEÇALHOS
Os detalhes adicionais fornecidos para a comunicação entre client e servidor (lembre-se, o REST é stateless). Alguns dos cabeçalhos comuns são:

## Solicitação:
- host: o IP do client (ou de onde veio a solicitação)
- accept-language: linguagem compreensível pelo client
- user-agent: dados sobre o client, sistema operacional e fornecedor

## Resposta:
- status: o status da solicitação ou código HTTP.
- content-type: tipo de recurso enviado pelo servidor.
- set-cookie: definição dos cookies pelo servidor.

# DADOS
Também chamados de corpo - body - ou de mensagem - message, contêm as informações que você quer enviar ao servidor.