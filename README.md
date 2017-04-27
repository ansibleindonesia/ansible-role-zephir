# Ansible Role: Zephir

Installs [Zephir](https://github.com/phalcon/zephir), a high level language
that eases the creation and maintainability of extensions for PHP on
RHEL/CentOS or Debian/Ubuntu servers.

## Requirements

No special requirements; note that this role requires root access, so either
run it in a playbook with a global `become: yes`, or invoke the role in your
playbook like:

```yml
- hosts: database
  roles:
    - role: phalcon.zephir
      become: yes
```

## License

Zephir is open-sourced software licensed under the MIT License. See the LICENSE file for more information.
