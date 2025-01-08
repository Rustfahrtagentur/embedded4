# Example with ESP32-C6-DevKitC-1

cargo install esp-generate

cargo install espup

rustup toolchain install stable --component rust-src

rustup target add riscv32imac-unknown-none-elf # For ESP32-C6 and ESP32-H2

esp-generate --chip=esp32c6 your-project
