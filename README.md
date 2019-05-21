# Docker Commands


### Listando os containers

* Containers em uso

```dockerfile
docker ps
```

* Containers que não estão sendo usados

```dockerfile
docker ps -a
```

### Listando as imagens

* Imagens instaladas

```dockerfile
docker images
```

### Parando containers

* Parar um container pelo ID

```dockerfile
docker stop [ContainerID]
```

* Para **TODOS** os containers que estão em uso

```dockerfile
docker stop $(docker ps -aq)
```

### Iniciando containers

* Startando um container pelo ID

```dockerfile
docker start [ContainerID]
```

### Apagar containers

* Apagando um container pelo ID

```dockerfile
docker rm [ContainerID]
```

* Apagando **TODOS** os containers

```dockerfile
docker rm $(docker ps -aq)
```

### Apagar imagens

* Apagando uma imagem pelo ID

```dockerfile
docker rm [ImageID]
```

* Apagando **TODAS** as imagens

```dockerfile
docker rmi $(docker images -aq)
```
