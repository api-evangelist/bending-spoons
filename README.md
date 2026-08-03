# Bending Spoons

<!-- API-EVANGELIST-PROVENANCE:BEGIN -->
> ### About this repository
>
> **This is not our API.** This repository is an independent, third-party profile of a company's
> **publicly available** API surface, maintained by [API Evangelist](https://apievangelist.com).
> API Evangelist does not operate, host, resell, or support this company's APIs, and is not
> affiliated with or endorsed by the company unless stated on the profile.
>
> **Where the information came from.** Everything here is assembled from material a member of the
> public can reach with a browser and no credentials — the company's own website, developer portal
> and documentation, the specifications it publishes for public use (OpenAPI, AsyncAPI, JSON Schema,
> `apis.json`, `llms.txt` and similar), its public repositories, and its public status, pricing and
> changelog pages. **Nothing here is obtained by breaching a system, defeating an access control, or
> using credentials of any kind.**
>
> **The rating is an independent assessment.** The Kin Score and Agent Readiness rating are
> independently calculated scores of a company's *public* API artifacts, produced by API Evangelist
> against a published rubric. They are not certifications, endorsements, security assessments, or
> audits, and they score published artifacts — not the quality, safety, or security of the software.
>
> **Corrections, re-scores, and removal are free.** No partnership, contract, or purchase is
> required, and you do not need to justify the request.
>
> - **Something wrong?** Open an issue on this repository, or email
>   [info@apievangelist.com](mailto:info@apievangelist.com).
> - **Published something new?** Ask for a re-score and we will re-run the rating.
> - **Want the listing taken down?** Say so and we will honor it. The profile is reduced to your
>   company name, a factual description, and a link to your own site, and the company is recorded as
>   **unrated** — never scored zero for having asked.
>
> **Response times.** Acknowledgement within **one business day**; removal or restriction within
> **two business days**; corrections and re-scores within **five business days**.
>
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

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
