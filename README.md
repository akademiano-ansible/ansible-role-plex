# wilmardo.plex

The Plex role for Ansible, install [Plex](https://www.plex.tv/).

## Requirements

## Role Variables

### Default usage

As default the role installs Plex.

### Advanced usage

## Example Playbook

```yaml
- hosts: plexservers
  roles:
    - { role: wilmardo.plex }
```

After running the playbook Plex and Tautulli need to be setup:
- Plex can be found at http://ipadress:32400/web

## License

BSD-3-Clause-Clear

## Author Information

This role was created in 2017 by [Wilmar den Ouden](https://wilmardenouden.nl).