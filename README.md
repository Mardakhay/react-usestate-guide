# react-usestate-guide

> An interactive, dark-themed HTML learning guide for React's `useState` hook — built for beginners, with live demos, AI-powered code review, and a quiz.

---

## What's Inside

A single `react-usestate-guide.html` file. No build step, no dependencies, no install — just open it in a browser.

**10 sections** covering: what state is, the useState syntax, data types (number, string, boolean, array, object), how re-rendering works, functional updates, controlled forms, multiple state, TypeScript, and a cheatsheet table.

**3 live demos** — an interactive counter, a boolean toggle, and a real-time controlled input.

**5 coding challenges** — write React code directly in the page and hit *Check with AI*. Claude reviews your solution, tells you what's correct, flags any issues, and gives an improvement tip.

**10-question quiz** with instant feedback and a final score.

## Usage

```bash
git clone https://github.com/your-username/react-usestate-guide
open react-usestate-guide.html
```

The AI code checker calls the Anthropic API. It works out of the box on [claude.ai](https://claude.ai) artifacts — for standalone use, add your API key to the fetch headers in the script section.

## Stack

Pure HTML · CSS · Vanilla JS · Anthropic Claude API (claude-sonnet-4)
