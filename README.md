# kOS-packages

Contains packages for kazamOS

## How to add

```bash
curl -fsSL https://kos-packages.pages.dev/public-key.gpg \
  | sudo gpg --dearmor -o /usr/share/keyrings/kazamos-archive-keyring.gpg

echo "deb [arch=amd64 signed-by=/usr/share/keyrings/kazamos-archive-keyring.gpg] https://kos-packages.pages.dev/ wired main" | sudo tee /etc/apt/sources.list.d/kazamos.list
```

## Note

The license of individual packages maybe different.
