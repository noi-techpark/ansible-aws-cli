[![REUSE Compliance](https://github.com/noi-techpark/ansible-aws-cli/actions/workflows/reuse.yml/badge.svg)](https://github.com/noi-techpark/opendatahub-docs/wiki/REUSE#badges)
Ansible AWS CLI Role
====================

Installation of the AWS CLI.

## Example Playbook

```yaml
- hosts: all
  roles:
    - role: ansible-aws-cli
```

## Versioning

In order to have a verioning in place and working, create leightweight tags that point to the appropriate minor release versions.

Creating a new minor release:

```bash
git tag 1.0
git push --tags
```

Replacing an already existing minor release:

```bash
git tag -d 1.0
git push origin :refs/tags/1.0
git tag 1.0
git push --tags
```
