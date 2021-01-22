# counter iced sample

## Usage

- native

  ```shell
  cargo run
  ```

- web

  ```shell
  cargo build --release --target wasm32-unknown-unknown
  wasm-bindgen ./target/wasm32-unknown-unknown/release/counter-iced-sample.wasm --out-dir public --web
  ```

  Finally, we serve ./public directory using an HTTP server and access it with our browser.
