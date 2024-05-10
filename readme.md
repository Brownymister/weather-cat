# weather-cat

- rust embedded programm for dht22 sensor

## install

Clone the embassy codebase into the paraent directory:

```
git clone git@github.com:embassy-rs/embassy.git
```

```
cargo run --bin wifi_blinky --release
```

For running without a debuggin probe: 
.cargo/cargo.toml
```
runner = "elf2uf2-rs --deploy --serial --verbose"
```
