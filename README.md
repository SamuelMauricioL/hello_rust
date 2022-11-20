# HELLO_RUST

Project to test `wasmer` & `wasmtime` on Rust langague.

## What is Wasmer?

Wasmer is a WebAssembly runtime that enables super lightweight containers to run anywhere from Desktop to the Cloud, Edge and IoT devices. Wasmer provides a CLI in order to easily execute wasm files in the command line. More info [HERE](https://cutt.ly/1ML9qE3).

## What is Wastime?

Wasmtime is a Bytecode Alliance project that is a standalone wasm-only optimizing runtime for WebAssembly and WASI. It runs WebAssembly code outside of the Web, and can be used both as a command-line utility or as a library embedded in a larger application. More info [HERE](https://cutt.ly/8ML9gxV)

#

# Keywords - dictionary

## What is WebAssembly?

WebAssembly is a `binary instruction format` and `virtual machine` that brings near-native performance to `web browser applications`, and allows developers to build high-speed web apps in the language of their choice. More info [HERE](https://cutt.ly/BML3Pfi)

## What is .wasm file ?

WebAssembly (abbreviated Wasm) is a binary instruction format for a stack-based virtual machine. Wasm is designed as a portable compilation target for programming languages, enabling deployment on the web for client and server applications. More info [HERE](https://webassembly.org/)

## What is WASI?

The WASI target is a proposal to define a standardized set of syscalls that WebAssembly files can interoperate with.

WASI is a modular system interface for WebAssembly. As described in the initial announcement, it's focused on `security` and `portability`. WASI is being standardized in a subgroup of the WebAssembly CG. Discussions happen in GitHub issues, pull requests, and bi-weekly Zoom meetings. More info [HERE](https://wasi.dev/)

#

the comands are the follow:

```
rustup target add wasm32-wasi
rustc src/main.rs --target wasm32-wasi
wasmtime main.wasm
```
