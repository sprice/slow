# Slow

<p align="center">
  <img src="assets/slow.png" alt="Slow logo: a pixel-art snail with a brain-shaped shell" width="160">
</p>

Agent skills for exploring ideas while maintaining critical thinking, logic, and cognitive security.

## Installation

### ChatGPT

1. Open **Settings → Plugins → Skills → Add → Add a marketplace** in the desktop app.
2. Enter `https://github.com/sprice/slow` in **Source**. Leave **Git ref** and **Sparse paths** blank.
3. Select **Add marketplace**, choose **Slow** in the plugin directory, and install the `slow` plugin.

### Claude

In a new Claude chat:

> Install this plugin https://github.com/sprice/slow

### From the CLI

```bash
npx skills add sprice/slow --skill cogsec
```

## Skills

Each skill runs only when you call it by name. The same question can go to any of them, so pick the kind of answer you want.

| skill    | what you get                                                                                          |
|----------|-------------------------------------------------------------------------------------------------------|
| `cogsec` | your idea tested against the evidence and the strongest alternative explanations, with a bottom line. |
| `level`  | a direct answer or recommendation and the fact that decides it, usually in a paragraph.               |
| `sift`   | what something rests on, how solid each part is, and the ideas that explain it.                       |

### Calling a skill

- **Claude Code:** `/level your question` for a standalone skill, or `/slow:level your question` for the plugin.
- **Codex:** `$level your question`, or pick it from `/skills`.
- **ChatGPT:** type `@` and choose the skill.

```
/cogsec My childhood summers felt longer. Is that because I did more things for the first time, or is there a better explanation?
/level If I remember a conversation vividly, is that a good reason to trust my memory of the exact words?
/sift How can two people leave the same conversation with different memories of what was said?
```

## Contributing

See the [contributing guide](CONTRIBUTING.md) to report an issue or suggest a change.

## LICENSE

Markdown and skill content are CC0. Code and other project files are MIT licensed. See [License](LICENSE.md) for details.

A project by [Shawn Price](https://shawnprice.com)
