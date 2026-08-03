# ExtensionMesh

**Open extension distribution.**

ExtensionMesh is an open project for practical extension distribution through
independent registries. Creators keep control of their releases, while
connectors let supported systems discover, install and update them.

The first maintained connector brings independent registries to Shopware 6.7.
Its requirements shape the shared model; support for additional systems remains
a future possibility, not a current promise.

## Public beta

[ExtensionMesh 0.1.0-beta.1](https://github.com/Extension-Mesh/shopware/releases/tag/v0.1.0-beta.1)
is available for broader evaluation on Shopware 6.7. Review the
[current boundaries and validation checklist](https://www.extension-mesh.dev/docs/project-status/)
before using it in production.

- **I use extensions:** [install the connector and add a registry](https://www.extension-mesh.dev/docs/for-users/).
- **I publish extensions:** [choose a complete or existing-release publishing flow](https://www.extension-mesh.dev/docs/for-creators/).

## What we are building

- **Registries** that can publish extension metadata and releases.
- **Connectors** that integrate registry data with a supported system.
- **Shared conventions and tooling** that make publishing, discovery,
  installation and updates predictable.

## Project principles

- **Open by default.** Source, documentation and technical decisions should be
  publicly accessible.
- **Implementation-led.** Real integrations drive the design.
- **Independent registries.** Registry operators retain control of their
  infrastructure and published extensions.
- **Explicit boundaries.** Connectors contain system-specific behavior.
- **No premature abstraction.** Common interfaces emerge from proven needs.

## Repositories

- [brand](https://github.com/Extension-Mesh/brand) — visual identity, assets and
  design guidelines.
- [shopware](https://github.com/Extension-Mesh/shopware) — the first system
  connector, currently in public beta for Shopware 6.7.
- [shopware-publisher](https://github.com/Extension-Mesh/shopware-publisher) —
  GitHub Actions tooling for publishing compatible Shopware plugin releases.
- [website](https://github.com/Extension-Mesh/website) — public website and
  project-wide documentation.

## Status

The Shopware connector is in public beta. Interfaces, generated metadata and
upgrade behavior may still change before a stable release. ExtensionMesh does
not certify registry operators or extension code; users choose which
independent sources they trust.

## Participate

Contributions, implementation feedback and independent registry use cases are
welcome. Start with the
[contribution guide](https://github.com/Extension-Mesh/.github/blob/main/CONTRIBUTING.md),
read the
[governance model](https://github.com/Extension-Mesh/.github/blob/main/GOVERNANCE.md),
and open an issue in the repository closest to your topic.
