---
title: "Version Control with Git"
date: 2026-03-22
tags: ["git", "version-control"]
image:
  caption: 'Photo by Unsplash'
cover:
  image: "https://images.unsplash.com/photo-1q1p2DrLBtko?q=80&w=1200"
---

## What is Version Control?

Version control is a system that tracks changes to files over time. It allows you to go back to previous versions, collaborate with others, and keep a full history of your project.

## What is Git?

Git is the most widely used version control system in the world. It was created by Linus Torvalds in 2005. Git is distributed, meaning every developer has a full copy of the project history on their machine.

## Why Use Git?

- **Track changes** — see exactly what changed, when, and who changed it
- **Collaboration** — multiple people can work on the same project simultaneously
- **Backup** — your code is safely stored on remote platforms like GitHub
- **Branching** — work on new features without affecting the main codebase

## Basic Git Commands

| Command | Description |
|--------|-------------|
| `git init` | Initialize a new repository |
| `git clone <url>` | Copy a remote repository locally |
| `git add .` | Stage all changes |
| `git commit -m "message"` | Save staged changes with a message |
| `git push` | Upload commits to remote repository |
| `git pull` | Download latest changes from remote |
| `git branch` | List or create branches |

## My Experience with Git

This week I used Git extensively to set up my personal website. I cloned a template repository, made changes locally, and pushed them to GitHub. I also ran into a situation where I accidentally committed large files, which taught me the importance of setting up a proper `.gitignore` file before starting a project!
