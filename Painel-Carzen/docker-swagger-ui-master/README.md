## Documentação painel-carzen

# Passo a passo


abra o terminal na pasta com dockercompose.yml
(esse comando ira criar uma imagem do docker com a documentação contida no api.yaml)

```shell script
docker-compose up -d
```
Depois de instalar as dependencias e rodar os projetos localmente
(painel-backend carzen-backend e integração-backend)

Abra o docker desktop

--> Images
--> swaggerapi/swagger-ui 
--> RUN

--> Abra [http://localhost:8001/](http://localhost:8001/) e verifique sua pagina swagger-ui.

