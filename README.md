# GPT Prompt Library

Welcome to my personal GPT Prompt Library — a curated and evolving collection of high-utility prompts engineered to streamline tasks, improve thinking, and automate repetitive workflows using large language models like ChatGPT.

This repository is designed to help me (and others) rapidly solve common problems by reusing high-quality, tested prompts.

---

## Prompt Categories

Prompts are organized by category for easy access:

| Category        | Description |
|----------------|-------------|
| `general/`      | Everyday prompts for productivity, planning, summarization, rewriting, etc. |
| `data_science/` | Prompts for cleaning data, performing EDA, engineering features, and building ML models. |
| `debug/`        | Prompts to improve or troubleshoot other prompts. |

---

## How to Use

1. Browse to the `prompts/` directory.
2. Pick a category (e.g., `general/`).
3. Open a prompt `.md` file.
4. Copy the prompt into ChatGPT or your preferred LLM.
5. Fill in your custom input (as indicated in the template).
6. Iterate as needed.

You can also adapt prompts to your own needs, tweak the tone, or chain them together for larger workflows.

---

## Example Prompt Format

Prompts follow this structure:

```markdown
Prompt Name: summarize_text_v1

Description:
Summarizes long-form text into concise bullet points and extracts action items.

Prompt:
"Summarize the following text in clear, concise bullet points. Highlight any actions, key insights, or deadlines.

Input:
<your text here>

Output format:
- Summary bullet points
- Action items
- Deadlines or dates"


Versioning
Each prompt has a version suffix like _v1, _v2, etc. As I improve prompts or tailor them to more specific workflows, I’ll version and comment changes.

This helps maintain backwards-compatible prompt designs while testing new ideas.

Contributing
This is primarily for personal use right now, but I may open it up for contributions later.

If you find it helpful and want to contribute:

Fork the repo

Add or improve prompts

Submit a pull request with a clear description of what you changed and why

Tech Stack / Tools Used
This project is intentionally minimal and tooling-light. The main tools involved are:

GPT-4o (via ChatGPT)

GitHub (for version control and storage)

Markdown (for prompt formatting)

pandas and Python for data science-oriented prompts

Roadmap
 Add general-use daily prompts

 Add data science prompt suite (cleaning, EDA, modeling)

 Add prompt chaining templates for multi-step tasks

 Write a prompt-debugging guide

 Build a searchable web UI (optional, future)

Why This Exists
Prompt engineering is a form of thinking.

By externalizing and refining my prompts, I'm building a reusable mental toolkit — a second brain — that collaborates, reasons, and creates with me. This collection helps me reduce cognitive friction and build workflows I can rely on, whether I'm working with data, writing, or planning my day.

It’s also an exercise in deliberate tool use: moving from casual AI use to intentional, productive collaboration.
