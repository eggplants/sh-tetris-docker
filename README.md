# sh-tetris-docker

- [ContentsViewer/sh-tetris](https://github.com/ContentsViewer/sh-tetris) on Docker
- `sh-tetris` is licensed by [MIT License](https://github.com/ContentsViewer/sh-tetris/blob/master/LICENSE)

## Usage

### From local Dockerfile

```bash
wget https://raw.githubusercontent.com/eggplants/sh-tetris-docker/master/Dockerfile
docker build -t sh-tetris:2.1.0 .
docker run -it sh-tetris:2.1.0 .
```

### From DockerHub

```bash
docker run --rm -it eggplanter/sh-tetris:2.1.0
```

## License

MIT
