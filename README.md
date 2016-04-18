# Ansible Role: magentotools

Ansible playbook to install extra helpfull applications:
        Magerun
        Modman
        Composer
        IonCube

## Role Variables

Available variables are listed below change install process. Variables should

    magentotools_install_magerun: true  #For install Megento Magerun
    magentotools_install_modman: true   #For install Megento Modman
    magentotools_install_composer: true   #For Install Composer
    magentotools_install_ioncube: true   #For Install IonCube

## Example Playbook

	- hosts: backend
      become: yes
      roles:
        - fradee.magentotools


## License

MIT / BSD

## Notes

This is my one of firsts playbooks it is a beta version and can be improved, please help me to improve and fix bugs for this playbook.

Thanks.
