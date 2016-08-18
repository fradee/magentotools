# Ansible Role: magentotools

Ansible playbook to install extra helpfull applications:
        Magerun
        Modman
        Composer
        IonCube for php5 & php 7

## Role Variables

Available variables are listed below change install process. Variables should

    magentotools_install_magerun: true  #For install Magento Magerun
    magentotools_install_modman: true   #For install Magento Modman
    magentotools_install_composer: true   #For Install Composer
    magentotools_install_ioncube: false   #For Install IonCube
    magentotools_install_ioncube_php7: false # Set up ioncube for php5
    magentotools_install_ioncube_php5: false # Set up ioncube for php7

## Example Playbook

	- hosts: backend
      become: yes
      roles:
        - fradee.magentotools


## License

MIT / BSD

## Notes
For install composer you must install php first
This is my one of firsts playbooks it is a beta version and can be improved, please help me to improve and fix bugs for this playbook.

Thanks.
