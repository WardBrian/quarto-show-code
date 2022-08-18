# Quarto-show-code

This is a [quarto](https://quarto.org/) extension
for displaying source code from a file in a document. This allows you to
have a single source of truth for code examples and avoid duplication.

```
{{ showcode path/to/my/file.c }}
```

This also supports the optional arguments `language` to override the highlighting and
`skiplines` to skip the first `n` lines from the file (useful for skipping a preamble)

See the [example](https://brianward.dev/quarto-show-code/)
