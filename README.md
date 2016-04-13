# Ansible Role: magentotools

Ansible playbook to install extra helpfull applications:
        Magerun
        Modman
        Composer

## Role Variables

Available variables are listed below change install process.

    magentotools_install_magerun: true  #For install Megento Magerun
    magentotools_install_modman: true   #For install Megento Modman
    magentotools_install_composer: true   #For Install Composer

## Example Playbook

	- hosts: database
      become: yes
      roles:
        - magentotools


## License

MIT / BSD

## Notes

This is my one of firsts playbooks it is a beta version and can be improved, please help me to improve and fix bugs for this playbook.

Thanks.
