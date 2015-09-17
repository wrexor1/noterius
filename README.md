# Noterius - emulator for Pirate King Online

Next-gen version with new architecture.

Version: 0.1.2

This emulator based on:
- PostgreSQL
- Docker
- fswatch

### Installation from latest sources

- Download project
```
$ go get -u github.com/Nyarum/noterius
```

- Go to directory
```
$ cd $GOPATH/src/github.com/Nyarum/noterius
```

- Run build docker image
```
$ docker build -t nyarum/noterius .
```

- Start project in docker
```
$ docker run -d -p 1973:1973 nyarum/noterius
```

### Installation from stable release

- Pull docker image
```
$ docker pull nyarum/noterius
```

- Start project in docker
```
$ docker run -d -p 1973:1973 nyarum/noterius
```

### Trailer for game

[![Cool trailer for TOP ;)](http://img.youtube.com/vi/0l1TWRR5KuI/0.jpg)](http://www.youtube.com/watch?v=0l1TWRR5KuI)