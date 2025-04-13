# Sui MEV Bot


## Run 
Start the bot with your private key.

```bash
cargo run -r --bin arb start-bot -- --private-key {}
```

```bash
cargo run -r --bin arb start-bot  --private-key suiprivkey1qzes9r9e8lwlf8k0nt3kn632j0p2mwqh6cwdkxgmyq9v7zy3x5ygcjpt04g --shio-ws-url "wss://rpc.getshio.com/feed"
```

## Supports

- BlueMove
- FlowX
- Aftermath
- Cetus 
- Kriya
- Abex
- Navi
- Turbos
- Deepbook
- Shio

## Relay
If you have a validator, you can let the validator push mempool transactions to your relay, which then send to the bot.

```bash
cargo run -r --bin relay
```