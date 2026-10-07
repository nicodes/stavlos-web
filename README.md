# Stavlos website

Static Astro landing page for the local-first coding-agent harness.

Primary destination: [Stavlos](https://github.com/nicodes/stavlos#readme).

Describes persistent agent teams and the terminal, loopback web, and Discord clients. Web questions and permissions are answered through the terminal or Discord.

## Development

Use the Bun version in `.mise.toml`.

```sh
bun install --frozen-lockfile
bun run dev
bun run build
bun run preview
```

The site is static and ships no client-side JavaScript. CI checks the build output and rejects JavaScript assets.

## Standard developer commands

Use `mise install` for the pinned toolchain. `mise exec -- make check` installs frozen dependencies, builds the static site and runs every existing output assertion. `make test` checks an existing build. No source lint or type-check gate is configured, so that profile capability is explicitly unsupported. `make dev` runs in the foreground; stop with Ctrl-C. `make clean` removes generated output.
