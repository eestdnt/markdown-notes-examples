# Markdown note examples

This simple guide gives examples of using Markdown and Pandoc for making beautiful notes/reports/homework-assignments/mathematic-notes in daily usage. For more Markdown features, visit this [link](https://www.markdownguide.org/basic-syntax/).

## Required packages

- Pandoc
- Latex engines (available in miktex or texlive packages)
- Text editors

## Why Markdown?

Refer to this [page](https://www.markdownguide.org/getting-started/). TLDR, Markdown is more flexible than MS Word but more lightweight than Latex.

## Why Pandoc?

Refer to this [page](https://pandoc.org/). Markdown document is already readable but formatted output such as PDF or HTML is much more pleasant to the eyes, especially with mathematical equations.

## Examples

See [note-example.md](./note-example.md).

## Converting to PDF

Run this command to convert .md to .pdf using default settings.

```
pandoc note-example.md -o example.pdf
```

Run this command to convert .md to .pdf using some custom settings (stored in ./settings.yml).

```
pandoc note-example.md -o example.pdf --pdf-engine=pdflatex --metadata-file ./settings.yml
```

