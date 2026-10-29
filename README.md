# Cask

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
> **Not from the company, and here with a question?** You are welcome here — we would rather be the
> front line and point you the right way than have a good report go nowhere. What this repository
> can answer is narrow, though, so it is worth knowing who you are actually looking for:
>
> - **A question about how the API works, an account, billing, or a bug in the service** — that is
>   the company's own support, not us. We profile this API; we do not operate it and cannot see
>   your account.
> - **A bug in an open-source project we only catalog** — file it on that project's own repository.
>   This has happened with a real and correct bug report that reached us instead of the people who
>   could fix it, which helped nobody.
> - **Anything about this listing itself** — the description, the tags, the rating, a missing or
>   wrong artifact — is ours. Open an issue here.
> - **Not sure, or something general about API Evangelist or APIs.io** — open an issue on the
>   [APIs.io Inbox](https://github.com/api-search/inbox) and we will route it.
>
> **This repository contains no software, and we will never ask you to download anything.** There is
> no build, release, installer, or binary here — only text and machine-readable API descriptions, so
> there is nothing here that can be "corrupt" or need "repairing". Any issue, comment, or email
> claiming otherwise and offering a download link is not from us and is hostile. Do not follow the
> link; it is a lure. Report it to GitHub and, if you like, tell us at
> [info@apievangelist.com](mailto:info@apievangelist.com) so we can take it down.
>
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

> **Acquired or rebranded.** This company was acquired, merged or renamed. Its API, if it still exists, is offered under another name. This profile is kept as a historical record and is not maintained or rated.

Cask Data, Inc. was the enterprise big-data startup, backed by Andreessen Horowitz, that built and open-sourced CDAP — the Cask Data Application Platform — a framework for building and running data analytic applications and data pipelines on Hadoop, Spark, Kubernetes, and the cloud. Cask was acquired by Google Cloud; CDAP continues as an Apache-2.0 open source project under the github.com/cdapio organization and powers Google Cloud Data Fusion. CDAP's programmatic surface is its HTTP RESTful "Microservices" API — 21 documented service families (Lifecycle, Artifact, Metadata, Metrics, Logging, Namespace, Pipeline, Preferences, Profile, Provisioners, Replication, Reports, Security, Service, Workflow, Monitor, Dashboard, Configuration, Transaction Service, System Workers) served under a /v3 path prefix from a self-hosted CDAP router, with Bearer access tokens issued by the CDAP authentication server. The company's own cask.co domain and developer portal are gone; the surviving surfaces are cdap.io, the CDAP documentation wiki, the cdapio GitHub organization, and the io.cdap.cdap / co.cask.cdap artifact groups on Maven Central.

**Areas:** Company · Big Data · Data Analytics · Data Pipeline · Data Integration · ETL · Hadoop · Spark · Open Source · CDAP · Metadata · Data Governance

## Cask on APIs.io (historical record)

Everything profiled for Cask is published on APIs.io rather than in this repository. Start at the provider page — **[apis.io/providers/cask/](https://apis.io/providers/cask/)** — or go straight to one of the APIs or properties below.

### APIs (12)

- [CDAP Microservices API](https://apis.io/apis/cask/cdap-microservices/) — The CDAP HTTP RESTful API, documented as "Microservices". All endpoints sit under a /v3 path prefix on a self-hosted CDAP router (default port 11015, or…
- [CDAP Lifecycle Microservices](https://apis.io/apis/cask/cdap-lifecycle/) — Deploy, start, stop, and manage the lifecycle of CDAP applications and the programs they contain within a namespace.
- [CDAP Artifact Microservices](https://apis.io/apis/cask/cdap-artifact/) — Manage CDAP artifacts — the packaged application and plugin JARs that applications are created from — including deployment, versioning, and plugin inspection.
- [CDAP Metadata Microservices](https://apis.io/apis/cask/cdap-metadata/) — Search, annotate, and retrieve business and technical metadata and lineage for CDAP entities such as applications, datasets, programs, and fields.
- [CDAP Metrics Microservices](https://apis.io/apis/cask/cdap-metrics/) — Query the metrics CDAP collects for system and user programs, including time-series queries across metric contexts and tags.
- [CDAP Logging Microservices](https://apis.io/apis/cask/cdap-logging/) — Retrieve and download logs emitted by CDAP system services and by user applications and programs, with filtering by time range and log level.
- [CDAP Namespace Microservices](https://apis.io/apis/cask/cdap-namespace/) — Create, list, and delete CDAP namespaces — the multi-tenancy boundary that isolates applications, datasets, and metadata. The cdap, default, and system…
- [CDAP Pipeline Microservices](https://apis.io/apis/cask/cdap-pipeline/) — Programmatically create, deploy, run, and inspect CDAP data pipelines (the Hydrator / Data Fusion pipeline application type) and their plugin configurations.
- [CDAP Replication Microservices](https://apis.io/apis/cask/cdap-replication/) — Manage CDAP replication (change data capture) jobs that stream changes from source databases into analytic targets such as BigQuery.
- [CDAP Security Microservices](https://apis.io/apis/cask/cdap-security/) — Manage CDAP secure store keys and authorization privileges, roles, and policies for principals operating against a security-enabled CDAP cluster.
- [CDAP Workflow Microservices](https://apis.io/apis/cask/cdap-workflow/) — Inspect and control CDAP workflows — multi-node program orchestration — including run records, node states, local datasets, and workflow tokens.
- [CDAP Preferences Microservices](https://apis.io/apis/cask/cdap-preferences/) — Read and write preferences — the hierarchical configuration key/value pairs resolved across the instance, namespace, application, and program scopes.

### Published properties

Each property below is a page on APIs.io carrying the machine-readable artifact and what it says.

#### Security (2)

Authentication, trust centre, and vulnerability disclosure.

- [Cask Authentication](https://apis.io/security/cask/cask-authentication/)
- [Cask Domain Security](https://apis.io/security/cask/cask-domain-security/)

## Where to find this API

Links to the company's own pages. This repository publishes no copy of their specifications — the canonical document is theirs and lives at the URLs below.

- [Documentation](https://cdap.atlassian.net/wiki/spaces/DOCS/overview)
- [Getting started](https://cdap.io/get-started/)
- [API reference](https://cdap.atlassian.net/wiki/spaces/DOCS/pages/477593807/CDAP+Microservices+Guide)
- [Support](https://cdap.io/community/)
- [Blog](https://medium.com/cdapio)
- [Terms of service](https://policies.google.com/terms)
- [Privacy policy](https://policies.google.com/privacy)
- [GitHub](https://github.com/cdapio)

## API Evangelist rating

**Not rated** — this company is recorded as acquired or rebranded, so no score is published. If it is in fact operating, say so on this repository and it will be re-profiled.

## How this profile is made

API Evangelist profiles a company's public API surface the way a developer would find it: the website, developer portal and documentation, the specifications it publishes, its public repositories, and its pricing, status and changelog pages. From that it derives the properties above — contracts split per API, workflows, schemas, collections, governance rules, plans and rate limits — and scores them against the published [Kin Score rubric](https://github.com/api-evangelist/kin-score).

The artifacts are published on [APIs.io](https://apis.io), not in this repository. This repository is the public record for Cask: the place to say something is wrong, missing or out of date, and to ask for a re-score or a removal.

## Open an issue

- **Something about this listing** — a wrong description, a missing API, a stale artifact or a question about the rating: [open an issue on this repository](https://github.com/api-evangelist/cask/issues/new).
- **A new API, or one that is not in the catalog yet** — [submit it on APIs.io](https://apis.io/add/).
- **Anything else** — [the APIs.io inbox](https://github.com/api-search/inbox/issues/new) or [info@apievangelist.com](mailto:info@apievangelist.com).
