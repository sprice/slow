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

| skill     | use it when                                                                                           |
|-----------|-------------------------------------------------------------------------------------------------------|
| `cogsec`  | you have a hunch and want to test it against the evidence and the strongest alternative explanations. |

### Examples

```
explore a topic:  Use cogsec to help me understand [topic].
```

Dedicated to the public domain under [CC0 1.0 Universal](LICENSE.md).

A project by [Shawn Price](https://shawnprice.com)
