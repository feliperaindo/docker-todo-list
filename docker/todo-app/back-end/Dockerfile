FROM node:16-alpine AS back-end

WORKDIR /app/back-end

ADD ./node_modules.tar.gz .

COPY . .

EXPOSE 3001

RUN npm install

ENTRYPOINT [ "npm" ]

CMD [ "start" ]