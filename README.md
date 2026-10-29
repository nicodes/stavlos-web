<!-- Generated from private documentation source. Do not edit directly. Source SHA256: 63176e0ba16dd8a6443424ad88b07ac648244b9fc44f7051e34b03f3a00af3b6 -->

# stavlos-web

Static website built with Astro.

Install the [komizo release](https://github.com/nicodes/komizo#install) matching `komizo.lock`, then run:

```sh
komizo dev                 # Foreground development server
komizo check               # Complete applicable source, build and output checks
komizo run build           # Generate dist/
komizo describe            # Inspect tools and available commands
```

Ctrl-C stops development. This website needs no runtime credentials or credential `.env` file.

## Install the CLI

With curl:

```sh
curl -fsSL https://stavlos.ai/install | sh
```

Or with mise:

```sh
mise use --global github:nicodes/stavlos@latest
```

Each install command has a Copy button with confirmation. If clipboard access is unavailable, the command remains selectable for manual copying.

Prebuilt Linux binaries are available for x86_64 and arm64. A Go compiler is not required. See [stavlos](https://github.com/nicodes/stavlos#readme) for setup and installation options.
