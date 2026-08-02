# Bending Spoons

Bending Spoons S.p.A. (Nasdaq: BSP) is a Milan, Italy technology company founded in 2013 that acquires
established digital products and operates them for the long term. Its portfolio spans more than 50
acquisitions — AOL, Brightcove, Eventbrite, Evernote, Harvest, Issuu, komoot, Loomly, Meetup, Remini,
Splice, StreamYard, Tractive, Vimeo and WeTransfer among them — serving over 500 million monthly active
users.

- https://bendingspoons.com/

## No API at the holding-company level

Bending Spoons publishes **no public developer API, API reference, or developer portal** as a corporate
entity. Contract discovery on 2026-08-02 probed `bendingspoons.com`, `www.`, `support.`, `investors.`
and `jobs.` for OpenAPI/Swagger, GraphQL, MCP `tools/list`, AsyncAPI and A2A agent cards, and resolved
`api.`, `developer.`, `developers.`, `docs.`, `status.`, `trust.` and `security.` — none of those
subdomains resolve, and every spec path returned 404. Every API surface in the group belongs to an
individual acquired product, each profiled separately in this network (see `x-portfolio` in `apis.yml`).

## What is captured here

| Artifact | Method |
|---|---|
| `well-known/bending-spoons-security.txt` | searched — RFC 9116, PGP-clearsigned, verbatim |
| `well-known/bending-spoons-well-known.yml` | searched — probe index with statuses |
| `security/bending-spoons-vulnerability-disclosure.yml` | searched — security@bendingspoons.com, OpenPGP key |
| `security/bending-spoons-domain-security.yml` | probed — TLS 1.3, SPF, DMARC p=reject; no HSTS/DNSSEC/CAA |
| `packages/bending-spoons-packages.yml` | searched — first-party open-source Swift frameworks (not API SDKs) |
| `conformance/bending-spoons-conformance.yml` | derived — web/security posture; API standards N/A |
| `llms/bending-spoons-llms.txt` | generated |
