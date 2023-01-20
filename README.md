# Docker Serverless Offline

Run Serverless functions without provider dependency.

## Build

```shell
docker compose build
```

## Serve

```shell
docker compose up -d serverless-offline
```

## Call

```shell
curl http://localhost:3000/dev/hello
```

## VSCode debug

```shell
docker compose up -d serverless-offline-debug
```
