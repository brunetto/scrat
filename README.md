# Scrat

Scratch Docker container with mozilla certificates to be network ready.

## Build

```bash
docker build -t brunetto/scrat:latest .
```

## Update certificates

```bash 
rm cacert.pem*
wget --no-check-certificate https://curl.haxx.se/ca/cacert.pem
```