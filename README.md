# Allium Syntax

VS Code extension providing syntax highlighting for [Allium](https://allium.sh) specification files (`.allium`).

## Features

- Syntax highlighting for all Allium language constructs:
  - Declarations: `entity`, `actor`, `rule`, `surface`, `contract`, `value`, `enum`, `invariant`, `variant`, `external entity`, `default`, `deferred`
  - Clause keywords: `when`, `requires`, `ensures`, `let`, `transitions_to`, `facing`, `exposes`, `provides`, and more
  - Built-in types: `String`, `Integer`, `Decimal`, `Boolean`, `Timestamp`, `Duration`, `Any`, and generic collections (`Set<T>`, `List<T>`, `Sequence<T>`)
  - Annotations: `@invariant`, `@guarantee`, `@guidance`
  - Language constants: `null`, `true`, `false`, `now`, `this`
  - Duration literals: `24.hours`, `7.days`, `30.seconds`
  - Collection and lifecycle methods: `.count`, `.any`, `.all`, `.first`, `.created`, `.destroyed`
  - Operators, strings, numbers, and line comments (`--`)
- Auto-closing pairs for `{}`, `()`, and `""`
- Code folding support

## Installation

Install from the [VS Code Marketplace](https://marketplace.visualstudio.com/items?itemName=01max.allium-syntax).

## Usage

Files with the `.allium` extension are automatically detected and highlighted.

## License

[MIT](LICENSE.md)
