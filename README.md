# noobient.example_role

## Synopsys

This role serves as a skeleton for other Ansible Galaxy roles.

## Parameters

| Name | Required | Example | Description |
|---|---|---|---|
| `msg` | yes | `Hello world!` | Message to be displayed. |

## Examples

```yml
- include_role:
    name: noobient.example_role
  vars:
    msg: 'Hello world!'
```

## Return Values

N/A

## Support

| Platform | Support | Status |
|---|---|---|
| Linter | ✅ | [![Lint](https://github.com/noobient/ansible-galaxy-example_role/actions/workflows/lint.yml/badge.svg)](https://github.com/noobient/ansible-galaxy-example_role/actions/workflows/lint.yml) |
| AlmaLinux 8 | ✅ | [![AlmaLinux 8](https://github.com/noobient/ansible-galaxy-example_role/actions/workflows/almalinux-8.yml/badge.svg)](https://github.com/noobient/ansible-galaxy-example_role/actions/workflows/almalinux-8.yml) |
| AlmaLinux 9 | ✅ | [![AlmaLinux 9](https://github.com/noobient/ansible-galaxy-example_role/actions/workflows/almalinux-9.yml/badge.svg)](https://github.com/noobient/ansible-galaxy-example_role/actions/workflows/almalinux-9.yml) |
| AlmaLinux 10 | ✅ | [![AlmaLinux 10](https://github.com/noobient/ansible-galaxy-example_role/actions/workflows/almalinux-10.yml/badge.svg)](https://github.com/noobient/ansible-galaxy-example_role/actions/workflows/almalinux-10.yml) |
| Fedora 42 | ✅ | [![Fedora 42](https://github.com/noobient/ansible-galaxy-example_role/actions/workflows/fedora-42.yml/badge.svg)](https://github.com/noobient/ansible-galaxy-example_role/actions/workflows/fedora-42.yml) |
| Fedora 43 | ✅ | [![Fedora 43](https://github.com/noobient/ansible-galaxy-example_role/actions/workflows/fedora-43.yml/badge.svg)](https://github.com/noobient/ansible-galaxy-example_role/actions/workflows/fedora-43.yml) |
| Ubuntu 22.04 | ✅ | [![Ubuntu 22.04](https://github.com/noobient/ansible-galaxy-example_role/actions/workflows/ubuntu-22.04.yml/badge.svg)](https://github.com/noobient/ansible-galaxy-example_role/actions/workflows/ubuntu-22.04.yml) |
| Ubuntu 24.04 | ✅ | [![Ubuntu 24.04](https://github.com/noobient/ansible-galaxy-example_role/actions/workflows/ubuntu-24.04.yml/badge.svg)](https://github.com/noobient/ansible-galaxy-example_role/actions/workflows/ubuntu-24.04.yml) |
| Ubuntu 26.04 | ✅ | [![Ubuntu 26.04](https://github.com/noobient/ansible-galaxy-example_role/actions/workflows/ubuntu-26.04.yml/badge.svg)](https://github.com/noobient/ansible-galaxy-example_role/actions/workflows/ubuntu-26.04.yml) |
