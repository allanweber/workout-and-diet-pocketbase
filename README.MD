# Pocketbase Docker

Current Pocketbase version is 0.22.13

## How to use this image Locally

### Build the Docker image

```bash
docker build -t allanweber/pocketbase .
```

### Start a Pocketbase instance

```bash
docker run --name pocketbase -d -p 8080:8080 allanweber/pocketbase
```
