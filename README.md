# undergrad-thesis-workflow-skill

A reusable Codex skill for practical undergraduate thesis work, especially Chinese questionnaire-based thesis projects.

Repository:

`https://github.com/fangfang0303/undergrad-thesis-workflow-skill`

License:

MIT

This skill helps guide a student through:

1. topic narrowing with advisor constraints
2. proposal / opening report drafting
3. questionnaire design
4. variable definition and coding
5. questionnaire data cleaning
6. result tables and chart preparation
7. discussion and conclusion drafting
8. plagiarism-response revision
9. AIGC-risk reduction revision

By default, the initialized thesis workspace should use Chinese main directory names for user-facing folders, such as `00-管理信息`, `01-选题`, `02-文献`, `03-结构`, `04-写作`, `05-审查`, and `06-提交`.

## Best Fit

This skill is a strong fit when:

1. the user is an undergraduate student
2. the advisor wants a concrete population and feasible method
3. the paper uses a questionnaire or small-scale survey
4. the user needs end-to-end workflow help rather than a one-off answer

## Repository Structure

```text
undergrad-thesis-workflow/
  SKILL.md
  references/
    workflow-map.md
    share-guide.md
README.md
.gitignore
```

## Install

Copy the `undergrad-thesis-workflow` folder into the target machine's Codex skills directory.

Typical Windows path:

```text
C:\Users\<username>\.codex\skills\
```

After copying:

1. restart the Codex app, or
2. open a new thread

## How To Use

In a new Codex thread, say:

```text
请帮我使用 undergrad-thesis-workflow 这个 skill，按本科论文问卷研究流程推进。
```

Or:

```text
请帮我用 undergrad-thesis-workflow skill，从选题收窄、问卷设计、数据清洗到论文写作完整推进。
```

## Notes

This skill is designed to keep advisor constraints central, avoid overly broad thesis topics, and keep cross-sectional questionnaire conclusions appropriately conservative.

## Sharing

You can share this repository directly, or zip the `undergrad-thesis-workflow` folder for manual distribution.
