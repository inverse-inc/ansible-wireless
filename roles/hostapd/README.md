# Ansible hostapd role

Configure `hostapd` daemon.

## Requirements

No

## Variables

See [defaults variables](defaults/main.yml)

## Examples

```
- name: configure Hostapd Linux
  hosts: wireless
  gather_facts: no
  collections:
  - inverse_inc.wireless
  
  roles:
  - hostapd
```

`hostapd` is started at end of playbook.

There is one service per entry in hostapd__configs
