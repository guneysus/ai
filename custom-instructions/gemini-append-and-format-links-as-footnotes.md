# Gemini: Append and Format Links as Footnotes

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