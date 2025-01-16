# Dockerfiles

## Build

You can build your images with `docker build` command. for example for build Dockerfiles/ you can run below command

```bash
docker build . \
  --platform linux/amd64 \
  -t your_org/inotify-tools:latest \
  -t your_org/inotify-tools:1.0.0 \
  -f Dockerfiles/Dockerfile.inotify-tools \
  --build-arg BUILD_IMG=debian:bookworm-20250113-slim
```
