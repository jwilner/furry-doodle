[![Tests](https://github.com/jwilner/furry-doodle/workflows/tests/badge.svg)](https://github.com/jwilner/furry-doodle/actions?query=workflow%3Atests+branch%3Amain)
[![Lint](https://github.com/jwilner/furry-doodle/workflows/lint/badge.svg)](https://github.com/jwilner/furry-doodle/actions?query=workflow%3Alint+branch%3Amain)
[![GoDoc](https://godoc.org/github.com/jwilner/furry-doodle?status.svg)](https://godoc.org/github.com/jwilner/furry-doodle)

# go-tmpl

go-tmpl is a convenient template for a go project.

The template includes:

- a valid and empty [go.mod](go.mod)
- a basic [Makefile](Makefile) with helpful commands
- [test CI](.github/workflows/tests.yml)
- [golangci-lint CI](.github/workflows/lint.yml) with `goimports` formatting

Run `bootstrap.sh` once cloned to bootstrap and swap out names where necessary.

<!-- jsonquote foo.json#bar -->
```json
{
  "a": [
    1,
    2,
    3
  ]
}
```
<!-- /jsonquote -->
