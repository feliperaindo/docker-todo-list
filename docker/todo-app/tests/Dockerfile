FROM betrybe/puppetter:1.0 AS tests

WORKDIR /app/tests

ADD ./node_modules.tar.gz .

COPY . .

ENTRYPOINT [ "npm" ]

CMD [ "test" ]
