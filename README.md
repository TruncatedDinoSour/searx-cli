# This repository has been migrated to the self-hosted ari-web Forgejo instance: <https://git.ari.lt/ari/searx-cli>
# Searx-cli

> SearX in the CLI

# Installation

## Manual

```bash
sudo install -Dm0644 doc/sxcl.1 /usr/share/man/man1/sxcl.1
sudo mandb -qf /usr/share/man/man1/sxcl.1
sudo install -Dm755 src/sxcl /usr/local/bin
```

## Packages

- Linux
  - Gentoo linux: [app-misc/searx-cli::dinolay](https://ari-web.xyz/gentooatom/app-misc/searx-cli)

# Configuration

Just edit `~/.config/searx_cli.ini` file, all documentation
in the `man` page.
