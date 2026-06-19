# Documentation project instructions

## About this project

- This is the Mintlify documentation site for the Archive Order API.
- Pages are MDX files with YAML frontmatter.
- Configuration lives in `docs.json`.
- Public documentation content lives under `docs/`.
- The OpenAPI source lives at `docs/reference/archive-order-openapi.yaml`.

## Terminology

- Use "order" for an archival document retrieval request.
- Use "researcher" for the person or provider fulfilling an order.
- Use "offer" for a researcher bid or fixed fulfillment proposal.
- Use "API client" for an integration using bearer API keys.
- Use "document" for a delivered file or scan.

## Style preferences

- Use active voice and second person.
- Keep sentences concise.
- Use sentence case for headings.
- Code format endpoint paths, parameters, header names, commands, and field names.
- Prefer concrete request and response examples over conceptual prose.
- Do not document internal Firebase callable APIs as public API features.

## Content boundaries

- Document the public REST API, OpenAPI contract, webhook delivery, authentication, errors, and workflows.
- Do not document internal admin tooling, private Firestore collections, or staff-only fulfillment operations unless they affect public API behavior.
- If a feature is not production-ready, state the limitation clearly.
