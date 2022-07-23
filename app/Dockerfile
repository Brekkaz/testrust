# 1. This tells docker to use the Rust official image
FROM rust:1.62.1

# 2. Copy the files in your machine to the Docker image
#COPY ./ ./

# Build your program for release
#RUN cargo build --release

# Run the binary
#CMD ["cargo watch -x run"]

#RUN cargo install diesel_cli --no-default-features --features postgres

RUN cargo install cargo-watch

WORKDIR /usr/src/app

#EXPOSE 3001

VOLUME ["/usr/local/cargo"]