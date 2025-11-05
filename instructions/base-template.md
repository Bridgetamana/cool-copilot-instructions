---
description: "Briefly describe what this instruction helps Copilot do."
applyTo: "**"
---

# [Instruction Name]

## Overview
Explain in one or two sentences what this instruction is designed to achieve.  
Keep it short, clear, and action-oriented (for example, “This instruction helps Copilot write concise, well-commented React components.”)

## Always
List the things Copilot should *always* do when this instruction is active.  
Be specific and use action verbs.

Example:
- Always include JSDoc comments above each function.
- Always validate user inputs before processing.
- Always prefer semantic HTML tags over `<div>`.

## Never
List the things Copilot should *avoid* doing.  
This section helps refine its responses and prevent unwanted behaviors.

Example:
- Never use inline styles in React components.
- Never repeat explanations unless asked.
- Never use informal tone in documentation.

## Output Format
Describe how Copilot should format its responses.

Example:
- Use code blocks for examples.
- Add short explanations after code snippets.
- Use markdown formatting for clarity.

## Notes (Optional)
Add any additional context or tips for users testing or refining this instruction.

Example:
> Works best in front-end projects with JSX and TypeScript.  
> Use together with `frontend-style-guide.md` for consistent UI behavior.
