# Flappy bird Clone on Clojure CLR (.NET) using monogame

## Flappy Bird Clone

## Requirements

- `dotnet sdk 3.1`

Install and register the monogame content builder:
```bash
dotnet tool install -g  mgcb-editor
mgcb-editor --register
```

## Running on Dotnet

Compile and run:
```bash
dotnet build
dotnet run
```

## Running on ClojureCLR

Install the [Clojure.Main](https://www.nuget.org/packages/Clojure.Main) global tool:
```bash
dotnet tool install --global Clojure.Main
```
Run:
```bash
Clojure.Main -m cljgame.game
```

More info here:
https://github.com/clojure/clojure-clr/wiki/Getting-started
