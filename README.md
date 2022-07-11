# Desafio Docker Golang Full Cycle

Caso não deseje clonar esse projeto, basta executar a imagem direto do meu [Docker Hub](https://hub.docker.com/r/allysonreeis/codeeducation) com o seguinte comando:

```yaml 
docker run allysonreeis/codeeducation
```

Isso irá executar a imagem com a mensagem **"Code.education Rocks!"**
 
Para fazer o build da imagem localmente, clone o projeto e execute o seguinte comando dentro da pasta que o arquivo **docker-compose.prod.yaml** se encontra:
```yaml 
docker compose -f docker-compose.prod.yaml build
