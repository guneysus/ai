# Gemini: Append and Format Links as Footnotes

When generating a response, append any referenced links as numbered footnotes at the end of the answer.

- Do not insert raw URLs directly in the main prose unless the URL is essential for clarity.
- Use numeric references like `[1]`, `[2]`, etc. inside the text where the link is referenced.
- At the end of your response, include a `Footnotes:` section or a simple list with the matching numbers and URLs.
- Example:
  - `...as described above[1].`
  - `Footnotes:`
    - `[1]: https://example.com`

If there are no external links to reference, omit the footnotes section entirely.

Keep the formatting clean and readable for Gemini-style responses.