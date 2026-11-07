# AI Automation Workflows

**Repeatable marketing work, with explicit human review.**

Workflow designs for marketing research, content adaptation, and social listening.

这里记录 AI 可以辅助哪些步骤、输入输出是什么，以及人必须检查和决定什么。

## Current stage

Design documentation only. No executable automation, scheduled job, or API integration is implemented in this repository. Any automation used elsewhere is separate and has not been reproduced or validated here.

| Workflow | Intended output | Human review |
| --- | --- | --- |
| [01 · Marketing case intake](workflows/01-case-intake/README.md) | A source-linked research queue | Verify sources and choose cases |
| [02 · One insight, three formats](workflows/02-content-adaptation/README.md) | Three content drafts | Review facts, voice, and platform fit |
| [03 · Weekly social listening](workflows/03-social-listening/README.md) | A topic and sentiment review draft | Check sampling, evidence, and interpretation |

## Implementation standard

Every implemented workflow will document trigger, inputs, outputs, human checkpoints, exclusions, setup, dependencies, an example run, and failure handling. Credentials stay in local configuration. Draft outputs require review before publication.

## Planned evaluation

Compare a manual baseline and an assisted run on the same task. Record time spent, factual errors, source coverage, and human edits. Do not claim time savings or reliability before measurement.

[Marketing Intelligence Lab](https://github.com/SylphiaXu/marketing-intelligence-lab) · [Marketing Case Library](https://github.com/SylphiaXu/marketing-case-library)
