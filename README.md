# Docker Commands

### Lista os containers em uso

```docker ps```

### Lista os containers que não estão sendo usados

```docker ps -a```

### Parando um container pelo ContainerID

```docker stop [ContainerID]```

### Parando TODOS os containers que estão em uso

```docker stop $(docker ps -aq)```

### Startando um container pelo ContainerID

```docker start [ContainerID]```

### Apagando um container pelo ContainerID

```docker rm [ContainerID]```

### Apagando TODOS os containers

```docker rm $(docker ps -aq)```

### Apagando TODAS as imagens

```docker rmi $(docker images -aq)```
