# Ansible Role: ansible-role-nextcloud_exporter

An Ansible Role that installs and configures the Prometheus Nextcloud exporter by [Robert Jacob](https://github.com/xperimental/nextcloud-exporter).

For further installation instructions follow the steps on the [Project page.](https://github.com/xperimental/nextcloud-exporter#client-credentials)

## Requirements

- Prometheus instance

## Dependencies

None

## Supported OS

The role currently supports Debian, Ubuntu, CentOS.

## Role Variables

Available variables are listed below, along with default values (see `defaults/main.yml`):

    # Netcloud Login url (e.g. https://nextcloud.example.org)
      nextcloud_url:

    # Nexcloud Auth Token
      nextcloud_auth_token:

    # Nextcloud Login username
      nextcloud_username:

    # Nextcloud Login password
      nextcloud_password:

## Example Playbook

    - hosts: nextcloud
      roles:
        - serverfriendsorg.nextcloud_exporter

## License

GNU General Public License v3.0

## Author Information

This role was created in 2021 by [Steven Conrad Bayer](https://steven.serverfriends.org/).
