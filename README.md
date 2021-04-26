# Tower Backup

![Ansible Lint](https://github.com/nleiva/ansible-backup/workflows/Ansible%20Lint/badge.svg)

Creates a backup of your Tower setup and uploads it to AWS S3. I run it on a schedule every week.

## Dependencies:

### Python libraries

```bash
pip3 install boto boto3 botocore
```

### Inputs

Example:

```yaml
my_user: ec2-user
my_version: 3.8.1-1
my_devices: tag_Name_tower_nleiva_com
my_facts:  yes
ansible_python_interpreter: /opt/my-envs/networking/bin/python
```