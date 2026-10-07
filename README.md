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
