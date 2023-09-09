FROM gcc:9

WORKDIR /app

COPY ./hello.c .

RUN gcc -o hello hello.c

CMD ["./hello"]