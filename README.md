# Citation File Format (citation-cff)
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
