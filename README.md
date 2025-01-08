# Example with ESP32-C6-DevKitC-1

# Install a stable toolchain
rustup toolchain install stable --component rust-src

# Add the toolchain
rustup target add riscv32imac-unknown-none-elf # For ESP32-C6 and ESP32-H2

# This is used to create a new project for ESP32
cargo install esp-generate
esp-generate --chip=esp32c6 your-project
