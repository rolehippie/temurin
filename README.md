# workspace

[![Source Code](https://img.shields.io/badge/github-source%20code-blue?logo=github&logoColor=white)](https://github.com/rolehippie/temurin)
[![General Workflow](https://github.com/rolehippie/temurin/actions/workflows/general.yml/badge.svg)](https://github.com/rolehippie/temurin/actions/workflows/general.yml)
[![Readme Workflow](https://github.com/rolehippie/temurin/actions/workflows/docs.yml/badge.svg)](https://github.com/rolehippie/temurin/actions/workflows/docs.yml)
[![Galaxy Workflow](https://github.com/rolehippie/temurin/actions/workflows/galaxy.yml/badge.svg)](https://github.com/rolehippie/temurin/actions/workflows/galaxy.yml)
[![License: Apache-2.0](https://img.shields.io/github/license/rolehippie/temurin)](https://github.com/rolehippie/temurin/blob/master/LICENSE)
[![Ansible Role](https://img.shields.io/badge/role-rolehippie.temurin-blue)](https://galaxy.ansible.com/rolehippie/temurin)

Ansible role to install temurin Java runtimer.

## Sponsor

Building and improving this Ansible role have been sponsored by my current and previous employers like **[Cloudpunks GmbH](https://cloudpunks.de)** and **[Proact Deutschland GmbH](https://www.proact.eu)**.

## Table of content

- [Requirements](#requirements)
- [Default Variables](#default-variables)
  - [temurin_packages](#temurin_packages)
- [Discovered Tags](#discovered-tags)
- [Dependencies](#dependencies)
- [License](#license)
- [Author](#author)

---

## Requirements

- Minimum Ansible version: `2.10`

## Default Variables

### temurin_packages

List of packages to install

#### Default value

```YAML
temurin_packages:
  - adoptium-ca-certificates
  - temurin-8-jre
  - temurin-17-jre
```

## Discovered Tags

**_temurin_**

## Dependencies

- None

## License

Apache-2.0

## Author

[Thomas Boerger](https://github.com/tboerger)
