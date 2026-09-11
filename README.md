<!-- Template: replace every {{...}} placeholder, then delete this comment.
     Sections wrapped in OPTIONAL comment blocks stay hidden until they apply
     (first release, docs site, first audit) — uncomment them then. -->

# OpenZeppelin Contracts for {{Ecosystem}}

[![Lint and Test](https://github.com/OpenZeppelin/{{repo}}/actions/workflows/test.yml/badge.svg)](https://github.com/OpenZeppelin/{{repo}}/actions/workflows/test.yml)
[![Coverage Status](https://codecov.io/gh/OpenZeppelin/{{repo}}/graph/badge.svg)](https://codecov.io/gh/OpenZeppelin/{{repo}})
[![License](https://img.shields.io/github/license/OpenZeppelin/{{repo}})](LICENSE)
<!-- OPTIONAL badges — uncomment with the first release / the docs site:
[![Github Release](https://img.shields.io/github/v/tag/OpenZeppelin/{{repo}}.svg?filter=v*&sort=semver&label=github)](https://github.com/OpenZeppelin/{{repo}}/releases/latest)
[![{{Registry}} Package]({{registry-badge-url}})]({{registry-package-url}})
[![Docs](https://img.shields.io/badge/docs-%F0%9F%93%84-yellow)](https://docs.openzeppelin.com/{{docs-slug}})
-->

> [!WARNING]
> This is experimental software and is provided on an "as is" and "as available" basis. We do not give any warranties and will not be liable for any losses incurred through any use of this code base.

**OpenZeppelin Contracts for {{Ecosystem}}** is a collection of secure smart contract libraries written in {{Language}} for the [{{Ecosystem}}]({{ecosystem-url}}) network. Our goal is to bring Web3 standards under the OpenZeppelin quality by providing a set of high-quality, battle-tested contracts that can be used to build decentralized applications on the {{Ecosystem}} network.

## Usage

{{Ecosystem}} smart contracts are written in {{Language}} leveraging {{framework/SDK}}. Follow the installation guide in the [{{Ecosystem}} documentation]({{setup-guide-url}}).

**Required version**: {{toolchain}} [{{version}}]({{toolchain-release-url}}).

<!-- OPTIONAL — uncomment once the library is published. Adapt the wording to the
     ecosystem's own vocabulary (crates on crates.io, packages on npm or the
     Move Registry, Scarb packages, ...).

### Published {{packages/crates}}

This library is published on {{registry}}:

- [{{name}}]({{registry-url}}): {{one-line description}}
- [{{name}}]({{registry-url}}): {{one-line description}}

### Add the library to your project

Pin to a specific version:

```{{toml|shell}}
{{dependency snippet: a [dependencies] block or the package-manager install command}}
```

> [!WARNING]
> Install from tagged releases, never from the development branch — the release
> process involves security measures the default branch does not guarantee.

### Example

```{{language}}
{{minimal example: import one module from the library and use it in a contract}}
```

-->

## Docs

Documentation is available inline in the source code. You can generate the documentation locally using:

```bash
{{doc generation command, e.g. `cargo doc --no-deps --lib --open`}}
```

<!-- OPTIONAL — uncomment once the documentation site is live:
High-level guides live on the [documentation site](https://docs.openzeppelin.com/{{docs-slug}}).
-->

**AI agents:** [`llms.txt`](llms.txt) is the discovery entry point for integrating this library into a downstream project — it points to the package catalogs, examples, generated API reference, and audits.

<!-- OPTIONAL — uncomment each line as the integration becomes available for this ecosystem.

## Tooling

- [Contracts Wizard](https://wizard.openzeppelin.com/) — interactive generator for starter contracts built on this library.
- [OpenZeppelin Skills](https://github.com/OpenZeppelin/openzeppelin-skills) — agent skills for developing with this library in AI coding tools.
- [OpenZeppelin MCP](https://github.com/OpenZeppelin/openzeppelin-mcp) — MCP server exposing OpenZeppelin contract generators to AI assistants.

-->

## Security

> [!WARNING]
> This library has not been audited yet. Use at your own risk.

<!-- OPTIONAL — after the first audit, delete the warning above and uncomment:
Past audits can be found in [`audits/`](audits).
-->

For security concerns, please refer to our [Security Policy](SECURITY.md).

Smart contracts are an evolving technology and carry a high level of technical risk and uncertainty. Although OpenZeppelin is well known for its security audits, using OpenZeppelin Contracts for {{Ecosystem}} is not a substitute for a security audit.

## Contribute

We welcome contributions from the community!

If you are looking for a good place to start, find a good first issue [here](https://github.com/OpenZeppelin/{{repo}}/issues?q=is%3Aissue%20state%3Aopen%20label%3A%22good%20first%20issue%22).

You can find more details in our [Contributing](CONTRIBUTING.md) guide, and please read our [Code of Conduct](CODE_OF_CONDUCT.md).

## License

OpenZeppelin Contracts for {{Ecosystem}} is released under the terms of the [`LICENSE`](LICENSE) file.
