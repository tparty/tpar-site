# TPAR site content

## Site content

- Audience: global. English is served at `/`; Japanese is served at `/ja/`.
- Publication boundary: decision-support concepts and guidance only; no workflow execution, exercise of authority, or external transmission.

## Local verification

```bash
pnpm install --offline --frozen-lockfile
pnpm validate:content
pnpm typecheck
pnpm test
pnpm build
```

Run `pnpm dev` only as a foreground loopback preview and stop it with Ctrl+C.
