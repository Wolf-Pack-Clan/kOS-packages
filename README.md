# kOS-packages

Contains packages for kazamOS

## How to add

```bash
sudo mkdir -p /etc/apt/keyrings
curl -fsSL https://wolf-pack-clan.github.io/kOS-packages/public-key.gpg \
  | sudo gpg --dearmor -o /etc/apt/keyrings/kazamos-archive-keyring.gpg

curl -fsSL https://wolf-pack-clan.github.io/kOS-packages/kazamos.sources \
  | sudo tee /etc/apt/sources.list.d/kazamos.sources
```

