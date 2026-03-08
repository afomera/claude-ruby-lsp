# Claude Code Ruby LSP Plugin

Ruby language intelligence for [Claude Code](https://docs.anthropic.com/en/docs/claude-code) via [Shopify's ruby-lsp](https://github.com/Shopify/ruby-lsp) language server.

Provides go-to-definition, hover documentation, diagnostics, completions, formatting, and more for Ruby files.

## Prerequisites

Install the `ruby-lsp` gem:

```sh
gem install ruby-lsp
```

Verify it's available:

```sh
ruby-lsp --version
```

## Installation

```sh
/plugin marketplace add afomera/claude-ruby-lsp
/plugin install ruby-lsp@afomera
```

## Supported File Types

| Extension | Language ID |
|-----------|-------------|
| `.rb`     | ruby        |
| `.rake`   | ruby        |
| `.gemspec` | ruby       |
| `.ru`     | ruby        |
| `.erb`    | erb         |
| `.rbs`    | rbs         |
## Configuration

Ruby LSP supports project-level configuration via `.ruby-lsp/config.yml`. See the [ruby-lsp documentation](https://shopify.github.io/ruby-lsp/) for details.

## License

MIT
