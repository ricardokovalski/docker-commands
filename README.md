# Docker Commands

### Lista os containers em uso

```docker ps```

### Lista os containers que não estão sendo usados

```docker ps -a```

### Parando um container

```docker stop [containerID]```

### Parando TODOS os containers que estão em uso

```docker stop $(docker ps -aq)```

### Startando um container

```docker start [containerID]```

### Apagando um container

```docker rm [containerID]```

### Apagando TODOS os containers

```docker rm $(docker ps -aq)```
