# OpenAQ Sri Lanka

> Unofficial live-probed API documentation.
> **Not affiliated** with the upstream operator.

**Tier:** A · **Category:** weather

Staging path: `api-docs/packages/openaq-lk-docs/` → extract to `Cookie-Cat21/openaq-lk-docs`.

## Source research

- `docs/WEATHER_DISASTER_APIS_RESEARCH.md`
- `docs/EXISTING_APIS_UNUSED_ENDPOINTS.md`

## Quick start

```bash
pip install -r requirements.txt
python scripts/probe.py
python scripts/build_site.py
```

## Clients

- Python: [`python/`](./python/) — `openaq-lk-docs-unofficial` (`pip install -e .`)
- TypeScript: [`typescript/`](./typescript/) — `@cookie-cat21/openaq-lk-docs-client`
- JavaScript (ESM, no build): [`javascript/`](./javascript/) — `client.mjs`

## Research

Research staged in [ArdenoStudio/lankawa](https://github.com/ArdenoStudio/lankawa) `api-docs/packages/openaq-lk-docs/`. Source docs:

- `docs/WEATHER_DISASTER_APIS_RESEARCH.md`
- `docs/EXISTING_APIS_UNUSED_ENDPOINTS.md`
