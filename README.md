# Linxue Cantonese Comedy Skill

![Lin Xue](./assets/LengShit.png)

> A Codex skill for fictional Hong Kong movie side-character comedy: rough Cantonese rhythm, practical advice, controlled vulgarity, and clear safety boundaries.

![Codex Skill](https://img.shields.io/badge/Codex-Skill-111827?style=for-the-badge)
![Language](https://img.shields.io/badge/Language-ZH%20%2B%20Cantonese-b91c1c?style=for-the-badge)
![Persona](https://img.shields.io/badge/Persona-Fictional%20Comedy-f59e0b?style=for-the-badge)
![Safety](https://img.shields.io/badge/Safety-Boundary%20Aware-059669?style=for-the-badge)

## What It Does

This skill turns ordinary advice, roasts, rewrites, and life commentary into a fictionalized Hong Kong comedy voice inspired by public screen-persona patterns:

- blunt Cantonese openers
- Mandarin explanations with Cantonese punchlines
- street-level metaphors from film sets, traffic, tea restaurants, and office chaos
- profanity used as comic timing, not random noise
- practical advice that still lands after the joke

It is built for prompts like:

```text
用林雪的方式点评一下我朋友，最近工作压力很大。
```

```text
低俗港片味一点，帮我改写这段吐槽。
```

```text
爆粗但别太恶毒，喷一下这个离谱需求。
```

## Design Principles

**Funny first, useful always.**

The skill is not just a profanity generator. It follows a simple pattern:

1. open with a sharp reaction
2. diagnose the real problem
3. explain it with a cinematic or street-level metaphor
4. give one concrete next step
5. close with a punchline

## Safety Boundaries

This is a fictional style skill. It must not:

- claim to be, speak for, or impersonate the real actor Lin Xue
- invent private facts or real quotes
- reproduce long movie dialogue
- generate harassment, doxxing, threats, discriminatory abuse, sexual exploitation, or illegal instructions
- use profanity against protected identities or private personal traits

When roasting a real person, the skill targets behavior and choices, not identity or personal harm.

## Repository Layout

```text
.
├── SKILL.md
├── agents/
│   └── openai.yaml
└── references/
    ├── phrasebook.md
    ├── research-notes.md
    └── style-guide.md
```

## Installation

Copy this directory into your Codex skills folder, then restart or reload your Codex session:

```bash
cp -R Linxue-skills ~/.agents/skills/linxue-cantonese-comedy-perspective
```

The skill can then be invoked with trigger phrases such as:

- `林雪`
- `林雪视角`
- `用林雪的方式`
- `港片粗口喜剧风`
- `低俗喜剧味`
- `爆粗`
- `再脏一点`

## Example Output Shape

```text
对唔嗨住，大佬，呢件事唔复杂。

[blunt diagnosis]

[practical explanation with Cantonese punchline]

你而家做一件事：[specific next step]。

[short closing joke]
```

## Notes

This project is a prompt-engineering and agent-behavior experiment. It explores how a skill can control tone, intensity, refusal behavior, and output shape without losing practical usefulness.
