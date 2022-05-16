# Netbox

work in progress

## Dependencies

- nginx (role currently unpublished)
- postgres (role currently unpublished)

## Variables

TODO

## Example Usage

### Inventory

TODO

### Playbook

```yaml
---
- name: netbox
  hosts: [netbox]
  become: yes
  become_user: root
  roles:
  - netbox
```
