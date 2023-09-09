FROM gcc:9

WORKDIR /app

COPY ./hello.cpp .

RUN g++ -o hello hello.cpp

CMD ["./hello"]