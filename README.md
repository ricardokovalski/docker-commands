# Docker Commands


### Listando os containers

* Containers em uso

```docker ps```

* Containers que não estão sendo usados

```docker ps -a```

### Listando as imagens

* Imagens instaladas

```docker images```


### Parando containers

* Parar um container pelo ID

```docker stop [ContainerID]```

* Para TODOS os containers que estão em uso

```docker stop $(docker ps -aq)```


### Iniciando containers

* Startando um container pelo ID

```docker start [ContainerID]```


### Apagar containers

* Apagando um container pelo ID

```docker rm [ContainerID]```

* Apagando TODOS os containers

```docker rm $(docker ps -aq)```


### Apagar imagens

* Apagando TODAS as imagens

```docker rmi $(docker images -aq)```
