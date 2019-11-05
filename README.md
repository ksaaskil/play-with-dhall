# Examples of [dhall-lang](https://dhall-lang.org/#)

Mostly taken from the [Getting started](https://github.com/dhall-lang/dhall-lang/wiki/Getting-started) page.

## Usage

Install [dhall](https://github.com/dhall-lang/dhall-lang/wiki/Getting-started%3A-Generate-JSON-or-YAML#installation).

```bash
dhall < examples/simple.dhall  # From file
dhall-to-json <<< '[{ foo=1}]' # From stdin
dhall-to-yaml <<< '[{ foo=1}]'
```