# ansible-role-velero

![Ansible](https://github.com/avnes/ansible-role-velero/actions/workflows/ansible.yaml/badge.svg)

Ansible role for installing velero.

## Requirements

Poetry. Install it from <https://python-poetry.org/docs/>

## Role Variables

```yaml
velero_version: 3.7.2
```

## Dependencies

None

## Example Playbook

```yaml
- hosts: all
  roles:
     - { role: avnes.velero }
```

## For pip compability

```bash
poetry export --dev --output requirements.txt
```

## Test

```bash
poetry install
poetry shell
poetry run molecule test
```

## License

MIT

## Author Information

<https://github.com/avnes>
