# DevOps pair session

## Setup AWS infrastructure simulator

```bash
docker compose up
```

## Test with aws-cli
aws --endpoint-url=http://localhost:4566 s3 ls
