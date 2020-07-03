# Vídeo aula sobre Dockerfiles

Para executar esse exemplo, você vai precisar ter o Docker instalado.

Construir a imagem (alterar o nome da imagem para sua preferência):

`docker build -t <nome-da-imagem> .`

Rodar o container (usar o mesmo nome da imagem criada com o comando acima):

`docker run -d -p 8080:8081 <nome-da-imagem>`

Testar a aplicação:

`curl http://localhost:8080/produtos/1`

Se não tiver o cURL instalado, pode acessar a mesma URL acima através do navegador.
