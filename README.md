# Model Context Protocol (MCP)

_Just heard of MCP and not sure where to start? See [the documentation website instead](https://modelcontextprotocol.io)._

This repo contains the:

- MCP specification
- MCP protocol schema
- Official MCP documentation

The schema is [defined in TypeScript](schema/2025-06-18/schema.ts) first, but
[made available as JSON Schema](schema/2025-06-18/schema.json) as well, for wider
compatibility.

The official MCP documentation is built using Mintlify and available at
[modelcontextprotocol.io](https://modelcontextprotocol.io).

## CI

The CI workflow (`.github/workflows/ci.yml`) runs on every pull request and on pushes to `main`. It validates TypeScript schema definitions, checks that generated schema JSON and documentation files are up to date, and verifies markdown formatting and links.

## Contributing

See [CONTRIBUTING.md](./CONTRIBUTING.md).

## License

This project is licensed under the [MIT License](LICENSE).
