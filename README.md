# Developer-tool marketing skills

> Behavioral repair candidate: output-quality regressions remain. See [evaluation status](evals/README.md). Hold this branch for validation before release.

25 open-source [Agent Skills](https://agentskills.io/specification) by [Jon Bishop](https://jonbishop.co) for marketing developer tools. Each skill includes a bounded workflow, domain-specific decisions, an evidence standard, a deliverable, and a linked playbook. There are no required paid services or runtime hooks.

## Built for this product type

Engineering adoption runs from a useful local or sandbox task to real-project integration, repeated use, and team ownership. These skills account for supported stacks, packages and SDKs, open-source licensing, deployment policy, maintainers, and platform approval. Downloads and stars are not activation.

This collection has its own skill names, product-specific guidance, and examples. For the other product type, see [Data-product marketing skills](https://github.com/jonbishop1/data-product-marketing-skills).

## Install

Clone this repository and copy the desired `.agents/skills/<name>/` folders into the skill location documented by your Agent Skills-compatible host. Keep each folder's references and assets. Each skill is standalone; shared context is optional. Avoid installing duplicate copies through several discovery paths.

For Codex, copy the desired skill folders with their references/assets into your project's `.agents/skills/`, then invoke `$devtool-copywriting` or another skill by name. See the [Codex evaluation notes](evals/README.md#codex-follow-up) for tested scope and limits.

For Claude Code:

```text
/plugin marketplace add jonbishop1/devtool-marketing-skills
/plugin install devtool-marketing-skills@jon-bishop-devtool
```

The manifest explicitly discovers `./.agents/skills/`. Format and manifest validation do not establish that every host can load or execute every task. Live research and execution depend on your host's tools and your authorization.

## Skills

| Skill | Task |
| --- | --- |
| [`devtool-agent-readiness`](.agents/skills/devtool-agent-readiness/SKILL.md) | Agent readiness |
| [`devtool-community-distribution`](.agents/skills/devtool-community-distribution/SKILL.md) | Community distribution |
| [`devtool-quickstart`](.agents/skills/devtool-quickstart/SKILL.md) | Quickstart |
| [`devtool-readme`](.agents/skills/devtool-readme/SKILL.md) | Readme |
| [`devtool-audience-research`](.agents/skills/devtool-audience-research/SKILL.md) | Audience research |
| [`devtool-competitive-research`](.agents/skills/devtool-competitive-research/SKILL.md) | Competitive research |
| [`devtool-content-production`](.agents/skills/devtool-content-production/SKILL.md) | Content production |
| [`devtool-content-strategy`](.agents/skills/devtool-content-strategy/SKILL.md) | Content strategy |
| [`devtool-copywriting`](.agents/skills/devtool-copywriting/SKILL.md) | Copywriting |
| [`devtool-customer-psychology`](.agents/skills/devtool-customer-psychology/SKILL.md) | Customer psychology |
| [`devtool-data-analysis`](.agents/skills/devtool-data-analysis/SKILL.md) | Data analysis |
| [`devtool-google-ads`](.agents/skills/devtool-google-ads/SKILL.md) | Google ads |
| [`devtool-landing-pages`](.agents/skills/devtool-landing-pages/SKILL.md) | Landing pages |
| [`devtool-marketing-background`](.agents/skills/devtool-marketing-background/SKILL.md) | Marketing background |
| [`devtool-marketing-plan`](.agents/skills/devtool-marketing-plan/SKILL.md) | Marketing plan |
| [`devtool-meta-ads`](.agents/skills/devtool-meta-ads/SKILL.md) | Meta ads |
| [`devtool-onboarding`](.agents/skills/devtool-onboarding/SKILL.md) | Onboarding |
| [`devtool-product-launches`](.agents/skills/devtool-product-launches/SKILL.md) | Product launches |
| [`devtool-seo-audit`](.agents/skills/devtool-seo-audit/SKILL.md) | Seo audit |
| [`devtool-seo-research`](.agents/skills/devtool-seo-research/SKILL.md) | Seo research |
| [`devtool-conference-pipeline`](.agents/skills/devtool-conference-pipeline/SKILL.md) | Conference pipeline |
| [`devtool-integration-marketing`](.agents/skills/devtool-integration-marketing/SKILL.md) | Integration marketing |
| [`devtool-pricing`](.agents/skills/devtool-pricing/SKILL.md) | Pricing |
| [`devtool-proof`](.agents/skills/devtool-proof/SKILL.md) | Proof |
| [`devtool-sales-enablement`](.agents/skills/devtool-sales-enablement/SKILL.md) | Sales enablement |

## Evidence and actions

Facts, observations, hypotheses, and unknowns stay distinct. Examples are fictional unless explicitly described as measured evidence. Sample success does not establish production readiness. Plans and drafts do not authorize publishing, messaging, spending, or production changes; existing user authorization governs execution.

## Validate and contribute

Use Python 3.9 or later for the repository checks, in an isolated environment:

```sh
python -m pip install -r requirements-dev.txt
python scripts/validate.py
python -m unittest discover -s tests
claude plugin validate .claude-plugin/plugin.json
claude plugin validate .claude-plugin/marketplace.json
```

The final two commands require a compatible Claude Code CLI. The [official reference validator](https://github.com/agentskills/agentskills/tree/main/skills-ref) requires Python 3.11 or later and can validate each skill folder. See [CONTRIBUTING.md](CONTRIBUTING.md) and the [evaluation scenarios](evals/scenarios.json). Authored scenarios are not completed model runs.

## Source and license

This is a standalone distribution generated from [shared authored source](https://github.com/jonbishop1/saas-marketing-skills), with domain overlays maintained there. Prefer contributing shared fixes upstream so both collections receive them. No sibling repo is required at runtime.

MIT — see [LICENSE](LICENSE). External documentation, logos, datasets, and customer material retain their own rights and permissions.
