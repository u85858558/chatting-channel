FROM redis:3.2-alpine

MAINTAINER bravist <lennisth337@gmail.com>

ENV REDIS_PASSWORD 123123

CMD ["sh", "-c", "exec redis-server --requirepass \"$REDIS_PASSWORD\""]
#CMD ["sh", "-c", "exec redis-server --requirepass \"\""]
