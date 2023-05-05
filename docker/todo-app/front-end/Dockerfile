FROM node:16-alpine AS front-end

WORKDIR /app/front-end

ENV REACT_APP_API_HOST=localhost

ENV REACT_APP_API_PORT=3001

ADD ./node_modules.tar.gz .

COPY . .

EXPOSE 3000

RUN npm install

ENTRYPOINT [ "npm" ]

CMD [ "start" ]
