<!-- Generated from private documentation source. Do not edit directly. Source SHA256: 99d98a2a2782be1af691b7ed9ee743fb94b73d2ffdb6e9ebcc68486dc9a24d5b -->

# stavlos-web

Static website built with Astro.

Install [mise](https://mise.jdx.dev/) and run `mise install`, then run:

```sh
mise run dev                 # Development server
mise run check               # Complete applicable source, build and output checks
mise run build           # Generate dist/
mise tasks ls            # Inspect tools and available commands
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

An icon-only copy control sits on the right inside each install-command outline and shows a checkmark after copying. If clipboard access is unavailable, the command remains selectable for manual copying.

Prebuilt Linux binaries are available for x86_64 and arm64. A Go compiler is not required. See [stavlos](https://github.com/nicodes/stavlos#readme) for setup and installation options.
