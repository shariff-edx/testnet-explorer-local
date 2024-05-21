# Run explorer in local using below commands


```
aws configure
```

```
aws ecr get-login-password --region eu-central-1 | docker login --username AWS --password-stdin 996995275645.dkr.ecr.eu-central-1.amazonaws.com
```

```
docker compose -f docker-compose.yaml up -d 
```

