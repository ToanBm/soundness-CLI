## Soundness CLI
A command-line interface tool for interacting with Soundness Layer testnet.
Quick Installation
Install the CLI with a single command:
```
curl -sSL https://raw.githubusercontent.com/soundnesslabs/soundness-layer/main/soundnessup/install | bash
```
After installation, restart your terminal or run:
```
source ~/.bashrc
```
Then you can use the CLI:
```
soundnessup install
```
Generating a Key Pair
To generate a new key pair for signing requests:
```
soundness-cli generate-key --name my-key
```
⚠️ Warning: Keep your mnemonic phrase secure and never share it with anyone. Anyone with your mnemonic can access your key pair.

- Join DC: [Link](https://discord.gg/Xgse4MYD)
- Generate your keys and head to our `testnet-access` channel in Discord and request access using:
```
!access <base64-encoded-public-key>
```
##            Done!
