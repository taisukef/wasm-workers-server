# Wasm Workers Server examples

This folder includes different handlers. All of them are based on other projects as we aim to create a server that is compatible with different providers.

## Build

### JavaScript handlers

Wasm Workers Server includes a `QuickJS` interpreter. JavaScript handlers are automatically compatible and you don't need to compile them to WebAssembly, although they will run in it.

### Rust handlers

For Rust handlers, you need to use our `wasm-workers-server-kit` crate. This folder contains several examples of its usage.