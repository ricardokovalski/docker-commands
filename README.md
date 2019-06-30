# Docker Commands

### Listando imagens instaladas localmente

```
docker images
```

### Buscando imagens

```
docker search [ImageName]
```

### Baixando imagens

```
docker pull [ImageName]
```

### Apagar imagens

* Apagando uma imagem pelo ID

```
docker rmi [ImageID]
```

* Apagando uma imagem pelo Nome

```
docker rmi [ImageName]
```

* Apagando **TODAS** as imagens

```
docker rmi $(docker images -aq)
```

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
