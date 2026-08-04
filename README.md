# San Francisco Compute Company (sf-compute)

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

San Francisco Compute Company (SF Compute) operates a market for buying short-duration time on H100 and H200 GPU clusters with no long-term contracts. Customers reserve VM nodes for any quantity, duration, and start time through the sf CLI and the sfcompute.com Orders API, with managed Slurm and bare-metal clusters available by request.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/sf-compute/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/sf-compute/refs/heads/main/apis.yml)

## Scope

- **Type:** Index
- **Position:** Producer
- **Access:** 3rd-Party

## Tags

- AI
- Cloud
- Clusters
- Compute
- GPU
- Machine Learning
- Marketplace
- Training

## Timestamps

- **Created:** 2026-05-23
- **Modified:** 2026-05-23

## APIs

### SF Compute Orders API

The SF Compute Orders API is the REST control plane for placing, listing, and managing orders that reserve GPU node-hours on H100 and H200 clusters. Orders specify node count, duration, and start time. Authentication uses bearer tokens generated via the sf CLI.

- **Human URL:** [https://docs.sfcompute.com](https://docs.sfcompute.com)
- **Base URL:** `https://api.sfcompute.com/v0`

#### Tags

- Clusters
- GPU
- H100
- H200
- Orders
- REST

#### Properties

- [Documentation](https://docs.sfcompute.com)
- [Postman Collection](collections/sf-compute.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/sf-compute.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [Website](https://sfcompute.com)
- [Developer](https://docs.sfcompute.com)
- [Documentation](https://docs.sfcompute.com)
- [Sign Up](https://sfcompute.com/signup)
- [Login](https://sfcompute.com/signin)
- [Pricing](https://sfcompute.com/prices)
- [Blog](https://sfcompute.com/blog)
- [Changelog](https://sfcompute.com/changelog)
- [Support](https://sfcompute.com/contact)
- [GitHub Organization](https://github.com/sfcompute)
- [LinkedIn](https://www.linkedin.com/company/sf-compute)
- [C L I](https://github.com/sfcompute/cli)
- [SDK](https://github.com/sfcompute/nodes-go)
- [SDK](https://github.com/sfcompute/nodes-typescript)
- [SDK](https://github.com/sfcompute/sfc-go)
- [SDK](https://github.com/sfcompute/sfc-sdk-typescript)
- [Features](undefined)
- [G P Us](undefined)
- [Customers](undefined)
- [L L Ms Txt](https://docs.sfcompute.com/llms.txt)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
**URL:** https://apievangelist.com
