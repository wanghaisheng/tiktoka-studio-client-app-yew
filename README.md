# rust-yew-axum-tauri-desktop template

Rust + Yew + Axum + Tauri + Tailwindcss, full-stack Rust development for Desktop apps, supports restful and
websocket api.

## Crates

- `frontend`: Yew frontend app for desktop client.
- `backend`: Axum backend restful and websocket api for desktop client.
- `server`: Axum server side restful and websocket api.
- `types`: Common types shared by frontend/backend/server.
- `tauri`: Tauri app for desktop client.

## Development

Install

```bash
rustup target add wasm32-unknown-unknown
cargo install trunk
cargo install tauri-cli
```

Run desktop client app

```bash
cargo tauri dev
```

Run server side

```bash
cargo run --bin server
```

Bundle desktop client app

```bash
cargo tauri build
```

## Contribute

Feel free to take a look at the current issues in this repo for anything that currently needs to be worked on.

You are also welcome to open a PR or a new issue if you see something is missing or could be improved upon.

## License

Apache-2.0/MIT
