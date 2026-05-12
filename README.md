# From Idea to Prompt to Production-Ready Code?

Presentation assets for **From idea to prompt to production-ready code? How AI-powered platforms can help you building apps.**

## Session

### Title

From idea to prompt to production-ready code? How AI-powered platforms can help you building apps.

### Abstract

A new wave of AI-powered platforms like Bolt, Lovable, Replit, and others promise to turn a simple prompt into a fully working application. But how well do they actually deliver? And more importantly, can you take what they generate and ship it to production?

In this session, I'll put one of these platforms to the test. Starting from nothing but a prompt, you'll see me build a real application live on stage and take it through the full journey from generated prototype to something production-ready. We'll look at code quality, architecture decisions, customization options, and deployment.

I'll also share what I've learned from working with these tools: when they work great, where they struggle, and how you as a developer can use them to move faster without losing control over what you're building. Whether you're looking at these platforms for rapid prototyping, client demos, or side projects, you'll leave with a good understanding of what's possible today.

Expect an audience driven live demo going from prompt to deployment, honest takes, and plenty of practical takeaways.

## Overview

This repository contains:

- A Demo Time scenario in `.demo/demo.yml`
- Slide content files in `.demo/slides/`

## Prerequisites

- Visual Studio Code
- Demo Time extension: `eliostruyf.vscode-demo-time`
- A modern browser (Chrome, Edge, or Safari)

## Run With Demo Time

1. Open the workspace in VS Code.
2. Ensure the Demo Time extension is installed.
3. Open `.demo/presentation.yml`.
4. Start the demo using the Demo Time commands from the Command Palette.

The Demo Time flow includes polls, website navigation, clipboard actions, and markdown slides from `.demo/slides/`.

## Project Structure

```text
.
├── .demo/
│   ├── presentation.yml
│   ├── slides/
│   ├── assets/
│   ├── layouts/
│   └── theme/
├── sources/
│   ├── From Prompt to Production.html
│   └── deck-stage.js
└── .vscode/
    ├── extensions.json
    └── settings.json
```
