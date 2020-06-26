![Build](https://github.com/GonzalezAndrew/ansible-role-packer/workflows/Molecule/badge.svg)
Role Name
=========

Installs Packer a software tool for creating machine images.

Requirements
------------

None.

Role Variables
--------------

Below are the role variables and their default values.
```
packer_version: 0.12.6
```
The Packer version to install.
```
packer_bin_path: /usr/local/bin
```
The location where the Packer binary will be installed. Hashicorp recommends to install the Packer binary to be included by your system `$PATH`.
```
packer_os: "linux"
packer_arch: "amd64"
```
The system operating system and architecture to use.
```
packer_download_url: "https://releases.hashicorp.com/packer/{{ packer_version }}/packer_{{ packer_version }}_{{ packer_os }}_{{ packer_arch }}.zip"
```
The Packer download url.

Dependencies
------------

None.

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: servers
      roles:
         - gonzalezandrew.ansible_role_packer

License
-------

MIT

Author Information
------------------

- [GitHub](https://github.com/GonzalezAndrew)
- [LinkedIn](https://www.linkedin.com/in/-andrew-gonzalez/)
- [Twitter](https://twitter.com/_GonzalezAndrew)
