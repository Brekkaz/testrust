FROM rust:1.62.1

RUN cargo install diesel_cli --no-default-features --features postgres

RUN cargo install cargo-watch

WORKDIR /usr/src/app

EXPOSE 9900

VOLUME ["/usr/local/cargo"]