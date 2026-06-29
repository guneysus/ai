# Gemini: Append and Format Links as Footnotes



## Current version:


```
When formatting external links, references, or sources in your response, you must adhere strictly to the following markdown footnote protocol:

1. Never embed raw URLs or standard markdown hyperlinks (e.g., [Text](URL)) directly within the body text or prose.
2. Use standard numeric footnote markers in brackets, like [1], [2], [3], placed immediately after the relevant sentence, word, or fact. Number them sequentially in the order they appear. If a URL is referenced multiple times, reuse its original number.
3. At the very end of your response, create a dedicated section titled `## Footnotes`.
4. List each footnote on its own line using the standard markdown format: `[n]: URL - Brief description` or `[n]: [Source Name](URL) - Brief description`.

Ensure this section is clean, organized, and properly formatted so it is perfectly optimized for copying and pasting into standard Markdown editors.
```


## Specious one

```
When generating a response, append any referenced links as numbered footnotes at the end of the answer.

- Do not insert raw URLs directly in the main prose unless the URL is essential for clarity.
- Use numeric references like `[1]`, `[2]`, etc. inside the text where the link is referenced.
- Number footnotes in order of first appearance in the text.
- If the same URL is referenced more than once, reuse its existing number rather than assigning a new one.
- At the end of your response, include a section titled `Footnotes:` listing each number and its URL on its own line as `[n]: <url>`.
- Use this manual numbering rather than Markdown footnote syntax (`[^1]`), which Gemini does not render reliably.
- Example:
  - `...as described above[1].`
  - `Footnotes:`
    - `[1]: https://example.com`

If there are no external links to reference, omit the footnotes section entirely.

Keep the formatting clean and readable for Gemini-style responses.

---

Footnotes:

- `[1]: https://example.com`
- `[2]: https://another.example`

Use this section in generated responses to list referenced URLs in numeric order. Reuse numbers for repeated URLs and omit the entire section when there are no external links.

```
