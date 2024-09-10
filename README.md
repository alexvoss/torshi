# Torshi

A tool for integrating rights, caring practices, and other human-rentric concepts into software engineering. Going beyond docs-as-code, we can use it to practice **docs-for-better-code**.

> [!IMPORTANT]
> The code in this repository is under active development and currently only
> provides the most basic proof-of-concept functionality. It will be a few more
> months (as of mid-September 2024) before it stabilises and this becomes usable
> as a tool. I am exposing it here, though, to inspire discussion about both the
> project aims and about the general approach to implementation.

## Features

in no particular order...

- [X] **Independent** of any specific static site generator - works with
      [Material for MkDocs](https://squidfunk.github.io/mkdocs-material/), [Readthedocs](https://docs.readthedocs.io/en/stable/), [plain MkDocs](https://www.mkdocs.org/), [Hugo](https://gohugo.io/), [Docusaurus](https://docusaurus.io/), even [Pandoc](https://pandoc.org/)!

- [ ] **Dialect agnostic** - passes through all Markdown, replacing
      only specific code blocks with HTML elements that are rendered as
      part of Markdown by the tools listed above.

- [ ] Renders BDD feature files written in [Gherkin](https://cucumber.io/docs/gherkin/reference/).

- [ ] Renders formulations of rights

- [ ] Renders caring practices

- [ ] Renders formulations of the UN Sustainable Development Goals

- [ ] Produces analyses that show you where rights still need to be implemented,
      what design decisions observed caring practices have inspired, what
      sustainability goals have been taken into consideration.

- [ ] Documentation produces with Torshi provides a basis for sustainability
      reporting, as required by, for example, the EU's Corporate Sustainability
      Reporting Directive.

## Technical features

- [X] Written in Rust for performance and to help with quality
- [ ] Extensive set of unit tests
- [ ] Examples that double as end-to-end tests