---
name: my-skill
description: [ONE sentence — what this does AND when to use it. The agent reads this line to decide whether to use the skill, so be specific. e.g. "Draft formative feedback comments from a rubric and a student text. Use when the educator asks for feedback drafts."]
---

# [Skill name]

[One or two lines: what this skill produces and the spirit of how to do it.]

## Steps
1. [First thing the agent should do — usually: read the input the user names.]
2. [Propose a plan and wait for approval, if the task is non-trivial.]
3. [Produce the output — say the exact format.]
4. [Any finishing touch — a disclosure footer, a summary, etc.]

## Rules
- [A hard constraint. e.g. "Use only the provided source; never add outside facts."]
- [A safety rule. e.g. "Stop if the input contains real student data."]
- [A quality rule specific to this task.]

## Check before finishing
- [How the agent should self-check — and what you'll verify by hand.]

<!--
For the lab: keep this starter folder with the course pack. Drop the folder
into your safe Codex project folder and ask Codex to set it up as a project
skill for you. You do not need to create hidden folders or technical paths by
hand.

Use it by describing the task naturally, for example:
"Use my rubric feedback skill on this rubric and this synthetic essay."

Tip: Codex can interview you and fill in this scaffold if you would rather
answer questions than edit the file yourself.
-->
