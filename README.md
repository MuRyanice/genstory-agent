# genstory-agent

English | [中文](./README.zh.md)

Genstory public skill repository.

This repository currently publishes the `genstory-story-generator` skill for connecting external workflows to Genstory story generation.

## Install

### Register marketplace

```bash
/plugin marketplace add MuRyanice/genstory-agent
```

### Install from marketplace

```bash
/plugin install genstory-agent@genstory-agent
```

### Or copy the skill directly

```bash
curl -fsSL https://www.genstory.app/api/skills/genstory-story-generator/skill-md
```

Once installed, read the `SKILL.md` file in the installed directory and follow its instructions to complete the task.

## Included skill

- `skills/genstory-story-generator`
  - Submit story tasks to Genstory with `GENSTORY_API_KEY`
  - Poll task status from Genstory
  - Return the hosted story URL and cover image

## API key

Users should create their API key in Genstory user center:

- `https://www.genstory.app/my-api-keys`
