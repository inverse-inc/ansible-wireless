# Ansible hostapd role

Configure `mac80211_hwsim` kernel module.

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
  - mac80211_hwsim
```

`mac80211_hwsim` kernel module is installed.
