



## Registro de API - Google

https://console.developers.google.com

## Mongo as a service host

mlab.com

## Mongo Express

http://localhost:8081/

## mongo setup

sudo docker exec mongo bash -c "mongo emaily_db_dev ./mongodb-setup.js"


## Up

```
docker-compose up -d
```

## Shutdown

```
docker-compose stop #stop but do not remote
docker-compose down #stop AND remove
docker-compose down #stop AND remove AND delete volumes
```


## Heroku
{"web":{"client_id":"272385407959-olrlor5nmfgnej8q4ong4qof46dpb80s.apps.googleusercontent.com","project_id":"emaily-220202","auth_uri":"https://accounts.google.com/o/oauth2/auth","token_uri":"https://www.googleapis.com/oauth2/v3/token","auth_provider_x509_cert_url":"https://www.googleapis.com/oauth2/v1/certs","client_secret":"cZ0yTlohJXwrE9kdHPaU9vxz","redirect_uris":["https://rsouza01-emaily.herokuapp.com/auth/google/callback"],"javascript_origins":["https://rsouza01-emaily.herokuapp.com"]}}

### Pipeline with github

https://medium.freecodecamp.org/how-to-deploy-a-nodejs-app-to-heroku-from-github-without-installing-heroku-on-your-machine-433bec770efe