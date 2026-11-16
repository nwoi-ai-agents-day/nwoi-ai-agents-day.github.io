---
layout: page
title: Skills
eyebrow: Further material
lead: The handoffs from the day, skill collections that others share, and how to make your own skill.
permalink: /skills/
---

A skill is a folder with a `SKILL.md` file. The file is a recipe that tells
your agent how to do one task. Check a skill before you install it. To
install one, give your agent the link and say which skills to install.

## Handoffs

A handoff is a file your agent reads and follows. Give your agent the short
link and ask it to follow the file. Both files are on the
[CWI course website]({{ site.event.course_url }}).

- [Literature-review skill](https://cwi-aiagents-lectures.github.io/handoff/lit-review-skill.md),
  short link `bilgehan.io/lit.md`. Your agent makes a `lit-review` skill with
  you. We use it in Hands-on 2.
- [Local LaTeX project](https://cwi-aiagents-lectures.github.io/handoff/latex-project.md),
  short link `bilgehan.io/latex.md`. Your agent sets up a LaTeX project on your
  own computer. You can try it at home.

### What the literature-review handoff does

1. It interviews you, one question at a time. It asks about your field, the
   sources to search, the number of papers, how recent they should be, the
   output format, the checks it should do, where to save results, and whether
   the skill is for you or for this project only.
2. It writes `lit-review/SKILL.md` from your answers.
3. It runs one test with 3 papers.
4. It shows you the skill file, so you can read and change it.

It asks before it installs anything or writes outside the project. It never
invents papers. Every paper comes from a live lookup, or it is marked
"could not verify".

## Skill collections

Skill counts are approximate, as of November 2026.

- [anthropics/skills](https://github.com/anthropics/skills). Example skills
  from Anthropic. They cover Word, PDF, PowerPoint and Excel files, design,
  web app testing, and a skill for making skills. About 20 skills.
- [K-Dense scientific-agent-skills](https://github.com/K-Dense-AI/scientific-agent-skills).
  Science skills for biology, chemistry, medicine, drug discovery, and access
  to scientific databases. About 180 skills.
- [Orchestra Research AI-Research-SKILLs](https://github.com/Orchestra-Research/AI-Research-SKILLs).
  Skills for AI research, such as fine-tuning, evaluation and paper writing.
  About 100 skills.
- [pstack](https://github.com/cursor/plugins/tree/main/pstack) by Lauren Tan.
  Ways of working for planning, reviews, checking results, and running
  several agents in parallel. About 60 skills.

## How to make your own

Do a task with your agent. When it works, ask "Turn what we just did into a
skill." Then read the file it writes and fix what is wrong. You can also use
the [literature-review handoff](https://cwi-aiagents-lectures.github.io/handoff/lit-review-skill.md)
as a model for your own. The
[Claude Code skills documentation](https://code.claude.com/docs/en/skills)
explains where skills live and how they are loaded.

## Security

Skills can contain scripts, and your agent may run them. Use skills from
sources you trust, and read the files before you install them. Treat it like
installing software. See Anthropic's
[Agent Skills overview](https://platform.claude.com/docs/en/agents-and-tools/agent-skills/overview)
for more on this.
