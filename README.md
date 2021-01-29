# OrganizaJsApi
BackEnd da Aplicação ( Api ) 

# Instalação
npm install -g json-server

# Criando o arquivo de banco de dados
Crie um arquivo de nome db.json em qualquer pasta do seu computador.

# Iniciando o servidor
Agora é só rodar o comando abaixo e seu servidor estará iniciado. Lembrando que por padrão a API vai funcionar no enderço: http://localhost:3000

json-server --watch db.json

# Rotas
As rotas definem como você vai acessar a API.
As rotas são:
GET , POST , PUT , DELETE , PATCH

As rotas vão ser compostas pelo endereço base (localhost:3000) mais o recurso que você quer acessar com por exemplo “produtos”.
Para executar os requests de exemplo abaixo você pode usar a ferramenta Postman (https://www.getpostman.com/) ou alguma outra de sua preferencia.
Para ver os resultados na pratica assista o vídeo acima ou execute os exemplos no seu computador.

# Exemplos:

# Exemplo 1: Buscar todos os produtos

Dados de envio

GET http://localhost:3000/produtos/
Content-Type: application/json

# Exemplo 2: Buscar apenas um produtos

Dados de envio

GET http://localhost:3000/produtos/1
Content-Type: application/json

# Exemplo 3: Salvar um produto

Dados de envio

POST http://localhost:3000/produtos/
Content-Type: application/json


# Exemplo 4: Alterar um produto

Dados de envio

PUT http://localhost:3000/produtos/1
Content-Type: application/json

# Exemplo 6: Excluir um produto

Dados de envio

DELETE http://localhost:3000/produtos/1
Content-Type: application/json
Retorno

Status: 200 OK
