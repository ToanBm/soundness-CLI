## Soundness CLI
A command-line interface tool for interacting with Soundness Layer testnet.
### 1. Install Rust & Cargo
```
curl --proto '=https' --tlsv1.2 -sSf https://sh.rustup.rs | sh -s -- -y
```
```
source $HOME/.cargo/env
```
- Check version
```
rustc --version
cargo --version
```

### 2. Install the CLI with a single command
```
curl -sSL https://raw.githubusercontent.com/soundnesslabs/soundness-layer/main/soundnessup/install | bash
```
### 3.After installation, restart your terminal or run:
```
source ~/.bashrc
```
### 4. Then you can use the CLI:
```
soundnessup install
```
### 5. Generating a Key Pair
To generate a new key pair for signing requests:
```
soundness-cli generate-key --name my-key
```
## ⚠️ Warning: Keep your mnemonic phrase secure and never share it with anyone. Anyone with your mnemonic can access your key pair.
### 6. Request your access
- Join DC: [Link](https://discord.gg/Xgse4MYD)
- Generate your keys and head to our `testnet-access` channel in Discord and request access using:

`!access <base64-encoded-public-key>`

##            Done!
