FROM alpine:latest

RUN apk update && apk upgrade --no-cache
RUN apk add --no-cache zlib

CMD ["sh", "-c", "echo 'Hello! v1'"]
