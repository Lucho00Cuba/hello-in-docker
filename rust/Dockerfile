FROM rust:1.55

WORKDIR /app

COPY ./Cargo.toml .
COPY ./hello.rs .

RUN cargo build --release

CMD ["./target/release/hello"]
