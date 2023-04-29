FROM node:14-alpine AS back-end

WORKDIR /app/back-end

ADD ./node_modules.tar.gz .

COPY . .

EXPOSE 3001

ENTRYPOINT [ "npm" ]

CMD [ "start" ]