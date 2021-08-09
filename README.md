# ansible-netplan

Simple Ansible role to configure netplan interfaces

## Variables

This roles will create interfaces based on `netplan_interfaces`.

Example:

```yaml
netplan_interfaces:
    - name: eth0
      dhcp4: true
    - name: eth1
      addresses:
        - 1.2.3.4/32
        - 5.6.7.8/24
```

## Author Information

[https://github.com/devops-works](https://github.com/devops-works)
