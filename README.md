# wezterm

[![Source Code](https://img.shields.io/badge/github-source%20code-blue?logo=github&logoColor=white)](https://github.com/rolehippie/wezterm)
[![General Workflow](https://github.com/rolehippie/wezterm/actions/workflows/general.yml/badge.svg)](https://github.com/rolehippie/wezterm/actions/workflows/general.yml)
[![Readme Workflow](https://github.com/rolehippie/wezterm/actions/workflows/docs.yml/badge.svg)](https://github.com/rolehippie/wezterm/actions/workflows/docs.yml)
[![Galaxy Workflow](https://github.com/rolehippie/wezterm/actions/workflows/galaxy.yml/badge.svg)](https://github.com/rolehippie/wezterm/actions/workflows/galaxy.yml)
[![License: Apache-2.0](https://img.shields.io/github/license/rolehippie/wezterm)](https://github.com/rolehippie/wezterm/blob/master/LICENSE)
[![Ansible Role](https://img.shields.io/badge/role-rolehippie.wezterm-blue)](https://galaxy.ansible.com/rolehippie/wezterm)

Ansible role to install wezterm terminal emulator.

## Sponsor

Building and improving this Ansible role have been sponsored by my current and previous employers like **[Cloudpunks GmbH](https://cloudpunks.de)** and **[Proact Deutschland GmbH](https://www.proact.eu)**.

## Table of content

- [Requirements](#requirements)
- [Default Variables](#default-variables)
  - [wezterm_package](#wezterm_package)
  - [wezterm_version](#wezterm_version)
- [Discovered Tags](#discovered-tags)
- [Dependencies](#dependencies)
- [License](#license)
- [Author](#author)

---

## Requirements

- Minimum Ansible version: `2.10`

## Default Variables

### wezterm_package

Download URL for the package to install

#### Default value

```YAML
wezterm_package: https://github.com/wez/wezterm/releases/download/{{ wezterm_version
  }}/wezterm-{{ wezterm_version }}.Ubuntu{{ ansible_distribution_version }}.deb
```

### wezterm_version

Version for the package

#### Default value

```YAML
wezterm_version: 20230408-112425-69ae8472
```

## Discovered Tags

**_wezterm_**


## Dependencies

- None

## License

Apache-2.0

## Author

[Thomas Boerger](https://github.com/tboerger)
