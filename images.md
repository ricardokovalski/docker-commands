# Lista de comandos relacionados as imagens do Docker

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
