# docker-retracker
Docker container for vvampirius/retracker

## How to run
```bash
docker run -dt --name docker-retracker --restart always  -p 8080:80 docker-retracker -l "0.0.0.0:80" -d
```
