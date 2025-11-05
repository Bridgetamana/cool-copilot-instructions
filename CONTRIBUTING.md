# Contributing to cool-copilot-instructions

Thank you for your interest in contributing.  
This project is open to anyone who wants to improve, extend, or refine instruction files for GitHub Copilot.

## Overview

This repository hosts practical `instructions.md` files that shape how Copilot behaves in specific workflows.  
Each instruction file should be:
- Focused on one purpose  
- Clear and reproducible  
- Easy to understand by anyone using Copilot  

We value contributions that improve quality, expand useful instruction types, or clarify documentation.

## How to Contribute

### 1. Fork the repository
Create your own copy by clicking **Fork** at the top of the page.

### 2. Create a new branch
Use a descriptive branch name for your change.
```bash
git checkout -b add-mentor-instruction
```

### 3. Add or update an instruction
To add a new instruction file, copy `instructions/base-template.md` and rename it.
- Follow the template sections
- Keep it concise and specific.
- Test your instruction with Copilot to make sure it behaves as intended.

### 4. Write a clear commit message
Use the format:
```bash
add: <instruction-name> instruction
```
Example (add: mentor-always instruction for guided explanations)

### 5. Open a Pull Request (PR)
Push your branch and open a PR to the main branch.

In your PR description
- Explain the purpose of the new instruction.
- Include an example of how it should be used.

A maintainer will review it and may suggest small changes before merging.

🎉Happy contributing
