# ai

A collection of custom instructions and prompts for AI assistants (Gemini, ChatGPT, Claude, and others).

## Contents

### `custom-instructions/`

Reusable system/custom instructions that shape how an AI assistant formats and structures its responses.

| File | Description |
| --- | --- |
| [`gemini-append-and-format-links-as-footnotes.md`](custom-instructions/gemini-append-and-format-links-as-footnotes.md) | Tells Gemini to append referenced links as numbered footnotes (`[1]`, `[2]`, …) instead of inline raw URLs, using manual numbering since Gemini does not reliably render Markdown footnote syntax (`[^1]`). |

## Usage

Each file under `custom-instructions/` is self-contained. Copy its contents into the custom-instructions / system-prompt field of your AI assistant of choice:

- **Gemini** — *Settings → Saved info* (or the custom instructions field)
- **ChatGPT** — *Settings → Personalization → Custom instructions*
- **Claude** — Project instructions or a `CLAUDE.md` file

## Contributing

Add new instructions as individual Markdown files in the relevant directory, then list them in the table above. Name files descriptively, prefixing with the target assistant where the instruction is tool-specific (e.g. `gemini-...`, `chatgpt-...`).
