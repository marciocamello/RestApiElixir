# RestApiElixir

- Build and R

```shell
mix do deps.get, deps.compile, compile
```

- RUN

```shell
mix run --no-halt OR iex -S mix
```

- Docker

```
docker build . --tag rest-api-elixir

docker run --publish 8000:80 --detach --name rest-api-elixir rest-api-elixir:latest
```