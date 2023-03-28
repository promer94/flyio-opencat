# Flyio-OpenCat

## Deploy OpenCat Team to Fly.io

1. Install the Fly CLI

2. crate a new app

```sh
fly launch --now
```

3. cerate a new presist volume

```sh
fly volumes create opencat --region hkg --size 1
```

4. deploy

```sh
fly deploy --image bayedev/opencatd:latest
```
