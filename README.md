# slow

Agent skills for exploring ideas while maintaining critical thinking, logic, and cognitive security.

## installation

### ChatGPT

1. Open **Settings → Plugins → Skills → Add → Add a marketplace** in the desktop app.
2. Enter `https://github.com/sprice/slow` in **Source**. Leave **Git ref** and **Sparse paths** blank.
3. Select **Add marketplace**, choose **Slow** in the plugin directory, and install the `slow` plugin.
4. Start a new chat and try “Use cogsec to help me understand [topic].”

### Claude

In a new Claude chat:

> Install this plugin https://github.com/sprice/slow

### From the CLI

```bash
npx skills add sprice/slow --skill cogsec
```

## skills

| skill     | use it when                                                                                           |
|-----------|-------------------------------------------------------------------------------------------------------|
| `cogsec`  | you have a hunch and want to test it against the evidence and the strongest alternative explanations. |

### examples

```
explore a topic:  Use cogsec to help me understand [topic].
```

Dedicated to the public domain under [CC0 1.0 Universal](LICENSE.md).

A project by [Shawn Price](https://shawnprice.com)
