# wireguard_ui

Ansible role to manage a [wireguard-ui](https://github.com/ngoduykhanh/wireguard-ui) instance.

## Role Variables

Use the `wireguard_ui_version` to specify the version you want to install.

Default:

```yaml
wireguard_ui_version: "v0.6.2"
```

You can use the `wireguard_ui_os` variable to specify the os family where the wireguard-ui should be installed.

Default:

```yaml
wireguard_ui_os: linux
```

The Role

## Example Playbook

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

```yaml
- hosts: servers
  roles:
    - { role: wittdennis.wireguard_ui, wireguard_ui_version: "v0.5.2" }
```

## License

MIT
