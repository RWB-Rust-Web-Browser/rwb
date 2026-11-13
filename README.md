### RWB - Rust Web Browser
It's a new browser _based_ on **Rust Programming Language** & _made_ with much **efforts** ;3

### Dependencies
cargo

### Installation
1. Clone the repo 
```git clone https://github.com/RWB-Rust-Web-Browser/rwb.git ```

2. Build it 
```cargo build --manifest-path rwb/Cargo.toml --release ```

3. Copy to your bins
    - default distro ```cp rwb/target/release/rwb /usr/bin```
    - NixOS ```cp rwb/target/release/rwb /run/current-system/sw/bin```
