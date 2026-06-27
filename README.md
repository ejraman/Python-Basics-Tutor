# Python Complete Tutor 🐍

An interactive Python learning app with a built-in AI tutor — covering Layer 1, Layer 2, and Layer 3 of the Python curriculum. Built as a single standalone HTML file that runs in any browser.

## What's inside

### Layer 1 — Basics
| # | Lesson |
|---|--------|
| 01 | Variables & Data Types |
| 02 | Operators |
| 03 | if / elif / else |
| 04 | Loops |
| 05 | Functions |
| 06 | Lists |
| 07 | Dictionaries |

### Layer 2 — Intermediate
| # | Lesson |
|---|--------|
| 08 | Classes & OOP |
| 09 | File I/O |
| 10 | try / except |
| 11 | Pandas |
| 12 | pip, bash & sed |

### Layer 3 — Advanced
| # | Lesson |
|---|--------|
| 13 | List comprehensions |
| 14 | Lambda functions |
| 15 | Decorators |
| 16 | Regex |
| 17 | datetime |
| 18 | os & pathlib |
| 19 | *args & **kwargs |
| 20 | Full roadmap |

## Features

- **20 lessons** covering the complete Python curriculum from beginner to intermediate-advanced
- **Interactive exercises** — write code, click Run, get instant feedback
- **Hints** — one click reveals a hint for every exercise
- **Progress tracker** — tracks which lessons you have completed
- **Built-in AI tutor** — click "Ask tutor" to open a chat panel powered by Claude AI. Ask any Python question in the context of the current lesson and get a tailored answer instantly
- **IBKR-aware** — examples and analogies are tuned for stock and options trading workflows

## How to use

### Option 1 — Run locally
1. Download `index.html`
2. Double-click to open in Chrome or Edge
3. The AI tutor requires an internet connection. All lessons and exercises work offline

### Option 2 — Run from GitHub Pages
Visit the live URL:
```
https://YOUR_USERNAME.github.io/python-tutor
```
No download needed. Opens directly in your browser.

## AI Tutor

The AI tutor is powered by the Anthropic Claude API. It knows:
- Which lesson you are currently on
- Your background (beginner, knows SQL and Data Science)
- Your use case (Python for IBKR stock and options trading system)

Click **💬 Ask tutor** in the top right of the app to open the chat panel. Type any Python question and press Enter.

Quick-tap buttons for common questions:
- What is self?
- = vs ==
- What is a DataFrame?
- How does a for loop work?
- What is a lambda function?
- What does pip freeze do?

## Tech stack

- Pure HTML, CSS, and vanilla JavaScript — no frameworks, no build step
- Anthropic Claude API (`claude-sonnet-4-6`) for the AI tutor
- Zero dependencies — single file, runs anywhere

## Curriculum roadmap

```
Layer 1  ✅  Variables · Operators · if/else · Loops · Functions · Lists · Dicts
Layer 2  ✅  Classes · File I/O · try/except · Pandas · pip · bash · sed
Layer 3  ✅  Comprehensions · Lambda · Decorators · Regex · datetime · os/pathlib · *args/**kwargs
Layer 4  🔜  numpy · matplotlib · requests · JSON · SQLAlchemy · logging
Layer 5  🔜  Flask/FastAPI · async/await · unit testing · packaging · git workflows
```

## License

Free to use for personal learning.
