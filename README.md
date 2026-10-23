# Aviato CLI

Releases of `aviato`, the command-line tool that runs the [Aviato](https://getaviato.com) connector next to your database, and its development tools (`aviato dev`, `aviato typegen`, ...).

This repository holds release binaries, checksums and install scripts only. Documentation lives at [docs.getaviato.com](https://docs.getaviato.com/integrations/connector).

## Install

```bash
# macOS and Linux
curl -fsSL https://getaviato.com/install.sh | sh

# Homebrew
brew install getaviato/tap/aviato

# Windows (PowerShell)
irm https://getaviato.com/install.ps1 | iex
```

Set `AVIATO_VERSION` (for example `0.5.1`) to install a specific release, and `AVIATO_INSTALL_DIR` to choose the directory. The scripts verify each binary against the release's `checksums.txt`.

The Docker image is published as [`getaviato/connector`](https://hub.docker.com/r/getaviato/connector) on Docker Hub and `ghcr.io/getaviato/connector`.

## Support

Questions and bug reports: open an issue in this repository.
