---
description: "Guidelines for writing clear, professional, and minimal project READMEs."
applyTo: "**/*.md, **/*.mdx"
---

# README Writing Instruction

## Overview
This instruction helps Copilot write project READMEs that are clear, simple, and useful.  
It focuses on accuracy, tone consistency, and readability — similar to documentation written by Google or GitHub technical writers.

## Always
- Always start with a one-line description that clearly states what the project is or does.  
- Always include sections in this order (where relevant):  
  1. **Overview** or **About**  
  2. **Installation**  
  3. **Usage**  
  4. **Configuration** (if applicable)  
  5. **Contributing**  
  6. **License**  
- Always write in plain, direct English (no marketing tone).  
- Always format using Markdown headings, bullet points, and code blocks for commands.  
- Always link to other files in the repo instead of restating long details (for example, `[CONTRIBUTING.md](./CONTRIBUTING.md)`).

## Never
- Never add emojis or decorative symbols unless the repo’s tone already uses them.  
- Never include personal pronouns like “I” or “we.” Keep it neutral and technical.  
- Never over-explain obvious steps (e.g., don’t describe what `git clone` does).  

## Output Format
- Use concise Markdown.  
- Limit the introduction to 2–3 sentences.  
- Wrap long lines at around 80–100 characters.  
- Use fenced code blocks for commands and examples.  
- Add blank lines between sections for readability.

Example:
```md
# project-name

A simple Node.js utility for formatting and validating configuration files.

## Installation
```bash
npm install project-name
