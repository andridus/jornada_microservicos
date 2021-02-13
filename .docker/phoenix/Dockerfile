FROM elixir:latest

RUN mkdir /app
COPY ../src /app
WORKDIR /app

RUN mix local.hex --force
RUN mix do compile