# beautiful-mermaid-cli

[한국어 (Korean)](docs/README_ko.md)

A thin CLI wrapper around beautiful-mermaid for rendering Mermaid diagrams as ASCII art.

## Tech Stack

- Runtime: [Bun](https://bun.sh/)
- Language: TypeScript
- Core: [beautiful-mermaid](https://github.com/nicholasgasior/beautiful-mermaid)

## Getting Started

```bash
# Install dependencies
bun install

# Run directly
echo 'graph LR; A-->B-->C' | bun src/cli.ts

# Global install
bun link
bmm --help
```
