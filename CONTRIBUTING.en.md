# Contributing Guide

Thank you for contributing to this repository.

This repository collects Agent Skills centered on "persona distillation", with emphasis on:

- Distilling expressive style, judgment patterns, or interaction habits from people, relationships, conversations, works, or digital traces.
- Turning a personal perspective, relationship experience, or methodology into a reusable skill.
- Keeping a clear thematic boundary so each entry fits an awesome-style list instead of a generic AI tools directory.

## Welcome Contributions

- Add links to skill repositories that fit the theme.
- Fix dead links, repository names, descriptions, or category placement.
- Improve wording in the READMEs so categories and descriptions are more accurate.

## Contributions We Discourage

- Generic AI tools, prompt collections, or resource directories that are only loosely related to persona distillation.
- Projects without a public repository, with inaccessible content, or with too little public material to evaluate.
- Obvious duplicates, thin repackaging, or entries that heavily overlap with existing items without adding value.
- Projects primarily intended for privacy invasion, harassment, impersonation of real people, or consent avoidance.
- Pure advertising copy or submissions that require readers to click through before they can understand the basics.

## Before You Submit

Please try to make sure each entry meets these standards:

- The repository is publicly accessible.
- The project is relevant to this list and fits the chosen category.
- The link text uses the project's commonly used name.
- The description stays within one sentence and explains what is being distilled, from what source, or for what purpose, without promotional wording.
- If the project fits a different category better, submit it directly in the more appropriate section.

## README Entry Format

Follow the existing list format:

```md
- [Project Name](https://github.com/owner/repo) - One sentence describing what the project distills, where it comes from, or what it is for.
```

Suggested writing style:

- Say what it is before saying what it does.
- Be specific instead of using vague praise like "high quality", "powerful", or "useful".
- Match the tone and level of detail of nearby entries.

## Submission Process

1. Fork the repository and create a branch.
2. Add or update the entry in both [`README.md`](./README.md) and [`README.en.md`](./README.en.md).
3. If your change affects inclusion standards or collaboration rules, update the relevant contribution guide as well.
4. Run formatting locally, then check that entry style, links, and wording remain consistent with the current content.
5. Open a PR and explain why the change belongs in this repository.

## Local Check

Before submitting, run:

```bash
npm ci
npm run format
```

Then double-check:

- Markdown list formatting matches the existing entries.
- Links are publicly accessible.
- Names and descriptions are accurate and non-promotional.

## PR Notes

To help review move faster, please explain:

- What you added or changed.
- Which category it belongs to and why.
- If it is a new project, how it relates to the persona distillation theme.
- If there are similar entries already listed, how this one differs from them.

## Communication

- Small fixes can go straight to a PR.
- If you plan to restructure categories, rewrite many descriptions, or noticeably expand the inclusion scope, it is better to open an issue or PR first to explain the idea.
- Keep discussion focused on thematic boundaries, readability, and reader value.
