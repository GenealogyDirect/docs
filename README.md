# ArchiveOrder API docs

Mintlify documentation for the ArchiveOrder API.

## Development

Install the Mintlify CLI:

```bash
npm i -g mint
```

Preview the site:

```bash
mint dev
```

The CLI prints the preview URL when the server starts.

## Source of truth

The API contract is based on `docs/reference/archive-order-openapi.yaml`.

When API behavior changes, update the OpenAPI document first and then update the guide and reference pages that explain the workflow.

## Publishing

Mintlify deploys this site from the connected GitHub repository after changes are pushed to the default branch.
