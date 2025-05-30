# eagle
system:Rust Operating System

### Add Target Triple to rustup
rustup target add thumbv7em-none-eabihf

### Build freestanding executable for the target
cargo build --target thumbv7em-none-eabihf
