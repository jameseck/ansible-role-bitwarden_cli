# Ansible Role: jameseck.bitwarden_cli

A simple role to install the Bitwarden cli on Fedora.

## Role Variables

Available variables are listed below along with default values (`defaults/main.yml`):

    bitwarden_version: 1.13.3
  The version of the Bitwarden cli to install

    bitwarden_dest_dir: /usr/local/bin
  The destination directory for the Bitwarden cli binary

    bitwarden_staging_dir: /tmp/ansible-role-bitwarden_cli
  A staging directory to download the Bitwarden cli zip to

    bitwarden_binary_owner: root
  The owner for the Bitwarden binary

    bitwarden_binary_group: root
  The group for the Bitwarden binary

    bitwarden_binary_mode: 0755
  The mode for the Bitwarden binary

## Example Playbook

    - hosts: workstation
      roles:
        - jameseck.bitwarden_cli

## License

MIT / BSD

## Author Information

James Eckersall
