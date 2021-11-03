<div align="center">
  <h1><code>proxy</code></h1>
  <p><strong>AWS Lambda HTTP(S) proxy.</strong></p>
</div>

# Build

  1. Add `x86_64-unknown-linux-gnu` rustup build target

      ```sh
      rustup target add x86_64-unknown-linux-gnu
      ```

  2. Build with Cargo (default target is `x86_64-unknown-linux-gnu` in `.cargo/config.toml`)

      ```sh
      cargo build --release # alias: cargo br
      ```

  3. A binary is produced in the `target/x86_64-unknown-linux-gnu/release` dir
