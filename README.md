# AF-16630 QA test repo

Created for AF-16630 spec-first Git reconnect testing on app.apifox.com.

## Contents

- openapi.yaml - professional OpenAPI 3.0.3 petstore spec (CRUD + pagination + error models)

Keep until test closed.


## Specification index

Professional OpenAPI 3.0.3 specifications for the Tars Commerce platform (QA fixtures for AF-16630 spec-first Git testing):

| File | Domain | Version |
| --- | --- | --- |
| [`specs/users.yaml`](specs/users.yaml) | User & Authentication Service — registration, login, token rotation, address book | 1.2.0 |
| [`specs/catalog.yaml`](specs/catalog.yaml) | Catalog Service — product search, SKU/price model, categories, inventory | 2.0.1 |
| [`specs/orders.yaml`](specs/orders.yaml) | Order & Payment Service — idempotent checkout, order state machine, captures/refunds | 1.5.0 |
| [`openapi.yaml`](openapi.yaml) | Petstore API — legacy sample kept as the initial connection fixture | 1.0.0 |

All specs share a common RFC 7807 problem-details error model and minor-unit `Money` representation. Each file is self-contained (no cross-file `$ref`).
