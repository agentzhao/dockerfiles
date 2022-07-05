# summarizer

https://nodejs.org/en/docs/guides/nodejs-docker-webapp/

docker build . -t agentzhao/summarizer:latest

```
docker run \
  -p 8080:8080 \
  -d agentzhao/summarizer \
  -v workspace/gpt3/summarizer:/usr/src/app

```

docker exec -it 38 /bin/sh
