# AuraOne

AuraOne is a human data company for AI teams and a workflow service for enterprises. It supplies expert judgment, speech, physical-world data and checked workflows.

Website: https://auraone.ai · Company facts: https://auraone.ai/company/facts · Open tools: https://auraone.ai/open

## Open tools by workflow

All MIT licensed. Each tool runs locally or in your CI, and each page shows a real run on a bundled example.

| Workflow | Start here | Go deeper |
| --- | --- | --- |
| **LLM evaluation**: score outputs against criterion-level rubrics and gate releases | [EvalKit Playground](https://auraone.ai/open/evalkit-playground) (browser, no install) · [EvalKit CLI](https://auraone.ai/open/evalkit) | [Rubric Studio Open](https://auraone.ai/open/rubric-studio-open) |
| **Agent failure → regression test**: turn a recorded tool-call failure into pytest | [tool-call-replay](https://auraone.ai/open/tool-call-replay) | [Agent Studio Open](https://auraone.ai/open/agent-studio-open) |
| **Robotics dataset QA**: check LeRobot-style datasets before training | [lerobot-quality-gates](https://auraone.ai/open/lerobot-quality-gates) | [Robotics Studio Open](https://auraone.ai/open/robotics-studio) |
| **Review quality**: reviewer agreement and LLM-judge bias | [iaa-kit](https://auraone.ai/open/iaa-kit) | [judge-bench](https://auraone.ai/open/judge-bench) |

Standalone tools: [mcp-risk-linter](https://auraone.ai/open/mcp-risk-linter) (offline MCP server security lint, SARIF), [a2a-contract-test](https://auraone.ai/open/a2a-contract-test) (A2A agent card and lifecycle checks), [contamination-audit](https://auraone.ai/open/contamination-audit) (benchmark contamination signals).

Build on AuraOne: [Python SDK](https://auraone.ai/open/sdk-python), [TypeScript SDK](https://auraone.ai/open/sdk-typescript), [GitHub App](https://auraone.ai/open/github-app) (self-hosted).

## Quick start

```bash
pip install auraone-evalkit tool-call-replay lerobot-quality-gates iaa-kit
```

## Packages

Python, on PyPI: [auraone-evalkit](https://pypi.org/project/auraone-evalkit/), [tool-call-replay](https://pypi.org/project/tool-call-replay/), [lerobot-quality-gates](https://pypi.org/project/lerobot-quality-gates/), [iaa-kit](https://pypi.org/project/iaa-kit/), [judge-bench](https://pypi.org/project/judge-bench/), [mcp-risk-linter](https://pypi.org/project/mcp-risk-linter/), [a2a-contract-test](https://pypi.org/project/a2a-contract-test/), [contamination-audit](https://pypi.org/project/contamination-audit/), [rubric-spec](https://pypi.org/project/rubric-spec/).

JavaScript, on npm under the @auraone scope: [@auraone/sdk](https://www.npmjs.com/package/@auraone/sdk), [@auraone/github-app](https://www.npmjs.com/package/@auraone/github-app), [@auraone/agent-studio](https://www.npmjs.com/package/@auraone/agent-studio).

Datasets, on Hugging Face: [auraone](https://huggingface.co/auraone).

Need expert reviewers, agent trace data, or robotics dataset QA at scale? [Talk to AuraOne](https://auraone.ai/contact).
