rustup target add wasm32-wasi
rustc src/main.rs --target wasm32-wasi
wasmtime main.wasm
