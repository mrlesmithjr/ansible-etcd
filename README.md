# ansible-etcd

An [Ansible](https://www.ansible.com) role to install/configure an [etcd - cluster](https://coreos.com/etcd/)

## Requirements

None

## Role Variables

[defaults/main.yml](defaults/main.yml)

## Dependencies

None

## Example Playbook

```yaml
---
- hosts: etcd_cluster
  roles:
  - role: ansible-etcd
```

## License

MIT

## Author Information

Larry Smith Jr.
- [@mrlesmithjr](https://www.twitter.com/mrlesmithjr)
- [EverythingShouldBeVirtual](http://www.everythingshouldbevirtual.com)
- [mrlesmithjr@gmail.com](mailto:mrlesmithjr@gmail.com)