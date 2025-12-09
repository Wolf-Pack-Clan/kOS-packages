# kOS-packages

Contains packages for kazamOS

## How to add

```bash
sudo mkdir -p /etc/apt/keyrings
curl -fsSL https://wolf-pack-clan.github.io/kOS-packages/public-key.gpg \
  | sudo gpg --dearmor -o /etc/apt/keyrings/kazamos-archive-keyring.gpg

echo "deb [arch=amd64 signed-by=/etc/apt/keyrings/kazamos-archive-keyring.gpg] https://wolf-pack-clan.github.io/kOS-packages/ wired main" | sudo tee /etc/apt/sources.list.d/kazamos.list
```

