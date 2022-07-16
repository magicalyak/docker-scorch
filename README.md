# docker-scorch

Docker image of simcity running on js-dos

run the following to build
`docker build -t docker-scorch --build-arg GAME_URL=https://archive.org/download/msdos_festival_SCORCH15/SCORCH15.ZIP --build-arg GAME_ARGS=\"SCORCH.EXE\" .`

once you have built the image, run with

`docker run -d -p 8000:8000 docker-scorch`
