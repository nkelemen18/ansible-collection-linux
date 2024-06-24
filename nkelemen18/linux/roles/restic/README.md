# Restic role
[Environment variables](https://restic.readthedocs.io/en/stable/040_backup.html#environment-variables) are configurable
with variables. Full list [here](./linux/roles/restic/defaults/main.yml)
```yaml
restic_conf_repository_file: ''
restic_conf_repository: ''
restic_conf_password_file: '/etc/restic/restic.pw'
restic_conf_password: ''
restic_conf_password_command: ''
restic_conf_key_hint: ''
restic_conf_cacert: ''
#...
```
