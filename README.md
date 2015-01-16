ansible-role-aliases
====================

Ansible Role - Add Aliases on RHEL/CentOS and Debian/Ubuntu.

## Requirements

None.

## Role Variables

		aliases_shell: zsh
		aliases_user: user
		aliases_aliases: []

## Example Playbook

    - hosts: all
      roles:
        - role: lesmyrmidons.aliases
          aliases_shell: bash
          aliases_user: vagrant
          aliases_aliases:
            - "alias ll='ls -la'"
            - "alias ping='ping -c4'"

## License

MIT / BSD
