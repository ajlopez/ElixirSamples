# Phoenix Framework Samples

Following http://www.phoenixframework.org/v0.13.1/docs/up-and-running

## First installation

```
mix local.hex
mix archive.install https://github.com/phoenixframework/phoenix/releases/download/v0.13.1/phoenix_new-0.13.1.ez
```

These installations are in the mix user folder, not in the current one.

## Hello

Created running from this phoenix folder with:

```
mix phoenix.new hello
cd hello
mix phoenix.server
```

Alternately, you can run the server with the interactive interpreter:

```
iex -S mix phoenix.server
```
