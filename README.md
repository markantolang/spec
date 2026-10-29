# Markanto specification

Markanto is a Markdown variant with one canonical form: it reads familiar
Markdown tolerantly, models it in a strict semantic AST, and writes exactly one
canonical form per meaning. This repository holds its normative specification,
[`spec.md`](spec.md), and the language data the specification names
([`data/`](data/)).

## Versions

Every released version is a tag. A tag never moves, and `main` holds the latest
version.

| Version | Tag | Read online |
| --- | --- | --- |
| 0.2.0 | `v0.2.0` | <https://markanto.org/spec/> |
| 0.1.0 | `v0.1.0` | <https://markanto.org/spec/0.1.0/> |

Each version lists its changes in a section "Changes from …" near its start;
`git diff v0.1.0 v0.2.0` shows them in full.

## Implementations

- [markanto-js](https://github.com/markantolang/markanto-js) — the reference
  implementation (`@markantolang/parser` on npm), with the conformance corpus.

## License

ISC, see [`LICENSE`](LICENSE).
