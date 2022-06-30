# Ansible Controller Backup

![Ansible Lint](https://github.com/nleiva/ansible-backup/workflows/Ansible%20Lint/badge.svg)

Creates a backup of your Ansible Controller setup and uploads it to AWS S3. I run it on a schedule every week.

## Inputs

Example:

```yaml
my_user: nleiva
my_version: 2.2.0-6.1
my_devices: host1.lab.home
my_facts:  yes
```