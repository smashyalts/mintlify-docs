# Atlas documentation

The published documentation for Atlas, spatial world sharding for Paper: one
Minecraft world across several servers, with borders players can walk across.

Live at <https://craftsupport.mintlify.app>. Pushing to `main` deploys.

## Layout

| Path | Contents |
| --- | --- |
| `introduction.mdx`, `quickstart.mdx` | Entry points |
| `concepts/` | How the grid, crossing, ghost band and cross-geo work |
| `deploy/` | Requirements, shared hosting, configuration, security |
| `operate/` | Commands, rollouts, audit, troubleshooting, testing |
| `reference/` | Wire protocol and known limitations |
| `api/` | The plugin API for other developers |
| `docs.json` | Navigation, theme and site config |

## Editing locally

```
npm i -g mint
mint dev
```

Anything here that disagrees with the Atlas source is a bug in this repo, not
in the code.
