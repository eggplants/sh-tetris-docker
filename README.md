# shtris-docker

- [ContentsViewer/shtris](https://github.com/ContentsViewer/shtris) on Docker
- `shtris` is licensed by [MIT License](https://github.com/ContentsViewer/shtris/blob/master/LICENSE)

## Usage

```bash
# launch game
docker run --rm -it ghcr.io/eggplants/shtris-docker

# show help
docker run --rm -it ghcr.io/eggplants/shtris-docker -h

# disable ansi color
docker run --rm -it ghcr.io/eggplants/shtris-docker --no-color

# set difficulty (1~15, default: 1)
docker run --rm -it ghcr.io/eggplants/shtris-docker -l 10
```

## Screenshot

![screenshot]


## License

MIT
