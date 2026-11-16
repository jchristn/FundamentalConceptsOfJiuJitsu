# Contributing

Thank you for helping improve *Fundamental Concepts of Jiu Jitsu*. Corrections are welcome from anyone.

## What is accepted

- **Factual inaccuracies:** a technique, position, rule, or term described incorrectly.
- **Errors in the text:** typos, grammar, broken cross-references, or inconsistent terminology.
- **Suggestions for a future edition:** please open an issue rather than a pull request. This edition will not be expanded with new content, but suggestions are kept for future editions.

## Reporting an issue

Open an issue and include:

1. The chapter and section where the problem appears.
2. The exact passage, quoted.
3. What is wrong, and what you believe is correct. A source or explanation helps.

## Submitting a pull request

Pull requests against the Markdown in `markdown/` are the main way to contribute a fix.

1. Fork the repository and create a branch.
2. Edit the relevant chapter file in `markdown/`. Each chapter is one file, named by its position in the book (for example, `markdown/24_Knee_on_Belly.md`).
3. Keep each pull request focused on one fix or a small group of related fixes, and explain the reason for the change in the description.
4. Do not edit the files in `word/` or `covers/`. Accepted changes are carried into the Word manuscript and the published edition by the author.

### Style

- Match the voice and vocabulary of the surrounding text. Terms such as the four battles, the Konami Code, and the strike zone are used deliberately and are defined in `markdown/33_Glossary.md`.
- Use straight quotes and plain Markdown.
- Keep the book conceptual. Corrections should fix what is there, not add new techniques or sequences.

## After a fix is accepted

Accepted fixes are recorded in `ERRATA.md` and `CHANGELOG.md`, and are included in the next update of the published edition on Amazon KDP.

## License of contributions

By submitting a pull request, you agree that your contribution may be included in the book and distributed under the same license as the rest of this work (see [LICENSE](LICENSE)), including in the published edition.
