# Docker Commands

### Lista os containers em uso

```docker ps```

### Lista os containers que não estão sendo usados

```docker ps -a```

### Parando um container

```docker stop id do container```

### Parando TODOS os containers que estão em uso

```docker stop $(docker ps -aq)```

### Startando um container

```docker start id do container```

### Apagando um container

```docker rm id do container```

### Apagando <b>TODOS</b> os containers

```docker rm $(docker ps -aq)```
