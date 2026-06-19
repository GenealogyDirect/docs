# Archive Order API docs

Mintlify documentation for the Archive Order API.

## Development

Install the Mintlify CLI:

```bash
npm i -g mint
```

Preview the site:

```bash
mint dev
```

View your local preview at `http://localhost:3000`.

## Source of truth

The API contract is based on `docs/reference/archive-order-openapi.yaml`, copied from the Archive Order application repository.

When backend behavior changes, update the OpenAPI document first and then update the guide and reference pages that explain the workflow.

## Publishing

Mintlify deploys this site from the connected GitHub repository after changes are pushed to the default branch.
