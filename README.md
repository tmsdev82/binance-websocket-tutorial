# Binance websocket tutorial

This repository is a companion repository to the article on my blog descriping how to connect to the Binance websocket streams API using the Rust programming language.

The program will connect to the following websocket URL:

```bash
wss://stream.binance.com:9443/stream?streams=ethbtc@depth5@100ms/bnbeth@depth5@100ms
```

It will then print the ask prices and sizes to the terminal.

## Running

Simply use the use the `cargo run` command to run the program. There is no additional configuration needed.