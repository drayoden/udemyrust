### rust - udemy :: rust fundamentals by Lyubomir Gavadinov
- memory safe with no garbage collection
- no nulls
- no exceptions
- modern package manager -> cargo like npm
- 'if it compiles; no data races'

### 05-cargo
- cargo new \<projname>
- cargo init -- create the project with the name of the parent folder with the init files in the current folder
- /cargo.toml -- like package.json - dependencies, config.
  - install crates: goto crates.io, grab the cargo.toml dependency text, copy it to cargo.toml and the run `cargo build` -- like 'npm install'
  - install crate via cargo: `cargo install <crate name>` -- installed 'cargo-expand' 
  - install the 'nightly' rust toolchain:
    - the command `cargo expand` will fail because it only uses the 'nightly' compiler
    - get the toolchain list: `rustup toolchain list` -- copy the 'stable' line
    - install the nightly toolchain: `rustup toolchain install nightly-x86_64-unknown-linux-gnu`
    - check the toolchain again: `rustup toolchain list` -- you should now see 'nightly' available



