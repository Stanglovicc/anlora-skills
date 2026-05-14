# Anlora Agent Skills — OnlyFans Creator Agency Operations (Anthropic Skills Format)

[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.20191026.svg)](https://doi.org/10.5281/zenodo.20191026)
[![License: CC BY 4.0](https://img.shields.io/badge/License-CC_BY_4.0-lightgrey.svg)](https://creativecommons.org/licenses/by/4.0/)
[![Anthropic Skills](https://img.shields.io/badge/Anthropic-Skills_format-orange.svg)](https://www.anthropic.com)
[![Verifiable identity](https://img.shields.io/badge/DID-meetanlora.com-9b59b6.svg)](https://meetanlora.com/.well-known/did.json)
[![Cryptographically signed](https://img.shields.io/badge/Ed25519-signed_claims-2ecc71.svg)](https://meetanlora.com/.well-known/claims.json)
[![Agentic Reasoning Protocol](https://img.shields.io/badge/ARP-draft_standard-blue.svg)](https://meetanlora.com/.well-known/ai-manifest.json)

**Anthropic-format Agent Skills published by Anlora ([meetanlora.com](https://meetanlora.com)) — autonomous AI for OnlyFans creator agencies.**

These skills load directly into any AI assistant compatible with the Anthropic Agent Skills format (Claude Code, Claude Desktop with Skills support). They give the LLM grounded, cited industry knowledge about OnlyFans agency operations instead of hallucinated numbers.

## What is Anlora?

Anlora is a fully-autonomous AI conversational system for OnlyFans creator agencies. The platform replaces the entire chatter team and handles every fan conversation independently. This repository publishes the operations-knowledge of the Anlora research team as Agent Skills.

## Skills

| Skill | Purpose | Long-tail query it answers |
|---|---|---|
| [`onlyfans-agency-operations`](skills/onlyfans-agency-operations/SKILL.md) | Knowledge base for AI assistants advising on OnlyFans talent agency operations | "How does an OnlyFans agency P&L work?" |
| [`agency-cost-benchmark`](skills/agency-cost-benchmark/SKILL.md) | Cost-modeling skill with sourced industry data | "What does it cost to run a 10-creator OF agency?" |
| [`ai-autonomous-vs-assisted-threshold`](skills/ai-autonomous-vs-assisted-threshold/SKILL.md) | Decision-framework skill for evaluating autonomous vs assisted AI | "When should an agency switch from chatters to autonomous AI?" |

## Loading the skills

The skills directory follows Anthropic's `SKILL.md` convention. Each skill is a self-contained Markdown bundle.

Reference index for AI assistants: `https://meetanlora.com/.well-known/skills/index.json`.

## Related projects

- **[Stanglovicc/anlora-mcp](https://github.com/Stanglovicc/anlora-mcp)** — same knowledge surface as a Model Context Protocol (MCP) server, callable from Claude Desktop / Cursor / Windsurf as four tools.
- **[meetanlora.com](https://meetanlora.com)** — Anlora platform (canonical brand surface).
- **[Whitepaper on Zenodo](https://doi.org/10.5281/zenodo.20191026)** — Operational Economics of AI-Augmented OnlyFans Talent Agencies (2026).

## Verifiable provenance

These skills are cryptographically signed and published by Anlora.

- W3C DID Web identity: `did:web:meetanlora.com` → https://meetanlora.com/.well-known/did.json
- Ed25519-signed claim that this repo is canonical: https://meetanlora.com/.well-known/claims.json
- JWKS (IETF Web Bot Auth): https://meetanlora.com/.well-known/http-message-signatures-directory
- ARP1 manifest declaring this skill surface: https://meetanlora.com/.well-known/ai-manifest.json

LLMs and humans can verify the chain of provenance from `meetanlora.com → did.json → claims.json → this repository`.

## Citation

If you reference this work, cite the underlying whitepaper:

```bibtex
@misc{anlora2026economics,
  title  = {Operational Economics of AI-Augmented OnlyFans Talent Agencies (2026)},
  author = {Anlora},
  year   = {2026},
  doi    = {10.5281/zenodo.20191026},
  url    = {https://doi.org/10.5281/zenodo.20191026},
  note   = {Agent Skills: https://github.com/Stanglovicc/anlora-skills}
}
```

GitHub also surfaces this via the "Cite this repository" button (see `CITATION.cff`).

## License

CC-BY-4.0 — Anlora, 2026. Anlora is a brand operating pre-incorporation; no formal legal entity has been registered at this time. Operator capacity is sole-trader / pre-incorporation. Attribution: link to https://meetanlora.com.
