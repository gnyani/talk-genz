# talk-genz

An [Agent Skill](https://agentskills.io) that makes coding agents speak in dense Gen Z slang. Technical nouns stay exact. The talk around them should take a second to decode.

Works with Cursor, Claude Code, and any client that supports Agent Skills.

## Install

```bash
npx skills add gnyani/talk-genz        # this project
npx skills add gnyani/talk-genz -g     # all projects
```

## Use

In chat:

```
talk gen z
```

Also works: `talk-genz`, `gen z mode`, `use talk-genz`, `/talk-genz`.

Intensity (default is `full`):

```
/talk-genz lite
/talk-genz full
/talk-genz extra
```

Stop:

```
stop talk-genz
```

Also works: `normal mode`, `talk normal`.

## What it does

- Stays off until you ask
- Stays on for the rest of the chat
- Keeps code, commits, PR text, and quoted errors professional
- Drops the voice for security warnings and irreversible-action confirmations

## License

MIT
