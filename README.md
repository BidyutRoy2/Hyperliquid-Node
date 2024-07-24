## Project's Social Media

- [Twitter](https://x.com/HyperliquidX)
- [Discord](https://discord.gg/hyperliquid)

## System Requirements

|                |      Minimum                  | Recommended                  |
|----------------|--------------------------|------------------------------|
| **RAM**        | 8 GB RAM                 | 16 GB+ RAM                   |
| **CPU Cores**  | 2 CPU cores              | 4+ CPU cores                 |
| **Disk Space** | 20 GB free disk space    | 50 GB+ free disk space (SSD) |
| **Architecture** | amd64 CPU Architecture | amd64 CPU Architecture       |
| **Operating System** | Ubuntu 22.04       | Ubuntu 22.04                 |


## Installation

- Use these commands one by one
```bash
sudo adduser hlnode
```
```bash
sudo usermod -aG sudo hlnode
```
```bash
su - hlnode
```
```bash
curl https://binaries.hyperliquid.xyz/Testnet/initial_peers.json > ~/initial_peers.json
```
```bash
echo '{"chain": "Testnet"}' > ~/visor.json
```
```bash
curl https://binaries.hyperliquid.xyz/Testnet/non_validator_config.json > ~/non_validator_config.json
```
```bash
curl https://binaries.hyperliquid.xyz/Testnet/hl-visor > ~/hl-visor
```
```bash
chmod a+x ~/hl-visor
```
```bash
sudo apt update
sudo apt install screen
```
```bash
screen -S hlnode
```
```bash
~/hl-visor
```
- Now detach from screen session using `Ctrl + A + D`

## Verify your node is running or not

- Use this command as non-root user
```bash
du -hs hl
```
- It shows hl node data storage, it will keep increasing with time

![pawelzmarlak-2024-07-18T15_29_35 358Z](https://github.com/user-attachments/assets/21348888-a2f9-45f4-9976-b7d5ecdfec4d)

- Also if you can use this command
```bash
cd ~/hl/data && ls
```
- It will show these type of files

![pawelzmarlak-2024-07-18T15_32_15 927Z](https://github.com/user-attachments/assets/e649f996-6b32-49ac-b603-00fe4edaabd3)

## Exit from nonroot user

- Write `exit` or `logout` if you want to exit from non-root user
- Done for now
## Enter as nonroot user (Optional)

- If you want to again enter as non root user, you can use `su - hlnode`

### - Get Latest Airdrops & Updates

### - Join Telegram: [HiddenGemNews](https://t.me/hiddengemnews)
