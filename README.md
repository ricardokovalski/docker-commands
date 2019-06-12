# Docker Commands

* [Comandos de imagens](/images.md)


### Criando containers

```
docker run [ImageName]
```

### Criando e acessando um container

```
docker run -it [ContainerName] /bin/bash
```

### Criando um container com apelido

```
docker run --name [Nickname] [Containername]
```


### Listando os containers

* Todos que estiverem em uso

```
docker ps
```

* Todos os containers criados incluindo os que estiverem inativos

```
docker ps -a
```


### Parando containers

* Parar um container pelo ID

```
docker stop [ContainerID]
```

* Para **TODOS** os containers que estão em uso

```
docker stop $(docker ps -aq)
```


### Iniciando containers

* Startando um container pelo ID

```
docker start [ContainerID]
```


### Apagar containers

* Apagando um container pelo ID

```
docker rm [ContainerID]
```

* Apagando **TODOS** os containers

```
docker rm $(docker ps -aq)
```

### Informações úteis

* Uso de hardware do container

```
docker stats [ContainerID]
```
