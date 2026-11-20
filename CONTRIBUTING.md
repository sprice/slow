# Contributing

To report an issue, suggest an improvement, or suggest a new skill, [open a GitHub issue](https://github.com/sprice/slow/issues/new).

Pull requests are welcome.

For a skill change, edit `skills/<name>/SKILL.md` and any supporting files in the same directory. Keep `disable-model-invocation: true` in the skill frontmatter and `allow_implicit_invocation: false` in `agents/openai.yaml` so the skill runs when called by name.

For a behavior report, include the skill name, the harness, the exact prompt, and what you expected the reply to do. Use an example you can share publicly. Eval cases and generated results live outside the public plugin.
