FROM betrybe/puppetter:1.0 AS tests

WORKDIR /app/tests

ENV FRONT_HOST=localhost

ENV FRONT_PORT=3000

ADD ./node_modules.tar.gz .

COPY . .

RUN npm install

ENTRYPOINT [ "npm" ]

CMD [ "test" ]
