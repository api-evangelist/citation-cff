# Citation File Format (citation-cff)

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

The Citation File Format (CFF) is a human- and machine-readable YAML schema for providing citation metadata for software and datasets in source code repositories. A CITATION.cff file at the root of a repository declares authors, version, DOI, release date, and reference metadata, enabling consistent academic attribution across publishing and discovery platforms.

**URL:** [Visit APIs.json URL](https://raw.githubusercontent.com/api-evangelist/citation-cff/refs/heads/main/apis.yml)

## Scope

- **Type:** Standard
- **Position:** Standard
- **Access:** Open

## Tags:

 - Academic, Citation, Metadata, Open Standard, Repository, Research, Software, YAML

## Timestamps

- **Created:** 2025-01-01
- **Modified:** 2026-04-23

## Standard

CFF is governed as an open community standard with a published JSON Schema, a guide, and a maintained schema repository on GitHub. The current schema version is **1.2.0**. CFF is maintained by community maintainers Stephan Druskat and Jurriaan H. Spaaks, with development support from the German Aerospace Center, the Netherlands eScience Center, and the Software Sustainability Institute.

## Components

### Citation File Format Schema
The CFF schema defines the structure of a CITATION.cff file in YAML, including required `cff-version`, `message`, and `authors` fields plus optional `version`, `doi`, `license`, `repository-code`, `preferred-citation`, and `references` blocks.

- [Schema (JSON Schema)](https://github.com/citation-file-format/citation-file-format/blob/main/schema.json)
- [Schema Guide](https://github.com/citation-file-format/citation-file-format/blob/main/schema-guide.md)
- [Documentation](https://github.com/citation-file-format/citation-file-format)
- [Local schema profile](json-schema/citation-cff-schema.json)

### cffinit
A web-based form that walks software authors through creating a syntactically and semantically valid CITATION.cff file.

- [Web Application](https://citation-file-format.github.io/cff-initializer-javascript/)

### cffconvert
A Python command-line tool and library that converts CITATION.cff files to APA, BibTeX, CodeMeta, EndNote, RIS, schema.org JSON-LD, and Zenodo deposition JSON.

- [Source](https://github.com/citation-file-format/cffconvert)
- [Package](https://pypi.org/project/cffconvert/)

### cff-validator GitHub Action
A GitHub Action that runs schema validation on a repository's CITATION.cff during continuous integration.

- [Source](https://github.com/dieghernan/cff-validator)
- [Marketplace](https://github.com/marketplace/actions/cff-validator)

## Integrations

- **GitHub** natively reads CITATION.cff files and renders a *Cite this repository* button.
- **Zenodo** uses CFF metadata when publishing a release through the GitHub-Zenodo integration.
- **Zotero** can import CFF references via a browser plugin.

## Common Properties

- [Website](https://citation-file-format.github.io/)
- [Documentation](https://github.com/citation-file-format/citation-file-format)
- [Schema Guide](https://github.com/citation-file-format/citation-file-format/blob/main/schema-guide.md)
- [Schema](https://github.com/citation-file-format/citation-file-format/blob/main/schema.json)
- [GitHub](https://github.com/citation-file-format)
- [Governance](https://github.com/citation-file-format/governance)
- [Issues](https://github.com/citation-file-format/citation-file-format/issues)
- [License](https://github.com/citation-file-format/citation-file-format/blob/main/LICENSE)
- [JSON-LD Context](json-ld/citation-cff-context.jsonld)
- [JSON Schema](json-schema/citation-cff-schema.json)
- [Spectral Ruleset](rules/citation-cff-rules.yml)

## Maintainers

**FN:** Kin Lane

**Email:** kin@apievangelist.com
