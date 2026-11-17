---
title: Welcome to 0xShanXs
published: 2026-11-17
description: An introduction to my cybersecurity journey, my SOC labs and the Blue Team writeups you'll find on this blog.
tags: [Cybersecurity, Blue Team, SOC]
category: General
draft: false
---

Welcome! This blog is my public notebook for learning cybersecurity from the defender's side. I'll use it to document my journey, my SOC labs and my Blue Team writeups, so that what I learn is written down properly and maybe useful to someone else.

## What you'll find here

- **SOC labs:** alert triage, log analysis and investigation walkthroughs.
- **Blue Team writeups:** detection, response and hardening exercises, step by step.
- **Notes from the journey:** tools, techniques and mistakes worth remembering.

## How a writeup is structured

I try to keep every writeup in the same shape so it's easy to skim and easy to reuse:

1. **Scenario:** what the lab or incident is and what question I'm trying to answer.
2. **Tooling:** the platforms, logs and data sources involved.
3. **Investigation:** the steps I took, including the dead ends.
4. **Findings:** what happened, with indicators of compromise where relevant.
5. **Detection ideas:** how I'd catch this earlier next time.
6. **Lessons learned:** what I'd do differently.

## Adding a new post

New writeups live in `src/content/posts/` as Markdown files that start with this front matter:

```md title="src/content/posts/my-first-writeup.md"
---
title: My First Lab Writeup
published: 2026-11-20
description: A short summary shown on the post card.
tags: [Cybersecurity, Blue Team, SOC]
category: Writeups
draft: false
---

Write the post here.
```

:::note
Everything on this blog comes from labs, CTF-style exercises and environments I own or am authorized to test.
:::

Thanks for reading, and stay curious.
