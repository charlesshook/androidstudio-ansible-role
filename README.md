# Ansible Role: Lynis

Installs [Android Studio](https://developer.android.com/studio) on Linux.

## Role Variables

```
androidstudio_version
androidstudio_tar
androidstudio_download_url
androidstudio_checksum
```

## Dependencies

None.

## Example Playbook

```yaml
---
- hosts: server1
  gather_facts: True
  become: yes

  roles:
    - role: androidstudio
```

## License

MIT