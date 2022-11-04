# Lego Rock

Distroless OCI image for [lego](https://go-acme.github.io/lego/) built with [rockcraft](https://github.com/canonical/rockcraft).

## Example usage

```bash
docker pull ghcr.io/gruyaume/lego:4.9.0
docker run ghcr.io/gruyaume/lego:4.9.0 lego -d <your domain> -m <your email> --dns=<your dns provider> --accept-tos=true run
```
