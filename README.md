# laravel-setup
### Criar ambiente de desenvolvimento para laravel, com Laradocker
> Status do Projeto: Em desenvolvimento :warning:
<hr>
 Clone os Arquivos
```sh
 git clone git@github.com:Vowkaz/laravel-setup.git
```
 
Vá para pasta [Laradocker](https://laradock.io) e construia o container
```sh
 cd ./laradock
 docker-compose up -d [ nome da imagem ]
```

Para acessar bash 
```sh
 docker exec -it --user=[default= laradocker ] [ CONTAINER ID ] bash
```

Para acessar o laravel 
```sh
 cd ./laravel-docker
```
