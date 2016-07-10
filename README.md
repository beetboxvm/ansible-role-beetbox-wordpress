# Ansible Role: Beetbox Wordpress

[![CircleCI](https://circleci.com/gh/beetboxvm/ansible-role-beetbox-wordpress.svg?style=svg)](https://circleci.com/gh/beetboxvm/ansible-role-beetbox-wordpress)

An Ansible role that creates and installs a WordPress project on beetbox.

## Requirements

This role is specifically developed as an extension to beetbox -- https://github.com/beetboxvm/beetbox

## Role Variables

Available variables are listed below, along with default values:

Download WordPress core.

    wp_download_core: no
    
Install WordPress.    
    
    wp_install_site: no
    
WordPress admin account name.
    
    wp_account_name: admin
    
WordPress admin account password.    
    
    wp_account_pass: admin
    
WordPress admin account email.    
    
    wp_account_email: admin@beetbox.local
    
WordPress locale.    
    
    wp_locale: ""


# beetbox

https://github.com/beetboxvm/beetbox

## Requirements

* [Vagrant](https://www.vagrantup.com/) >= 1.8
* [Virtualbox](https://www.virtualbox.org/)
* [Vagrant Hostsupdater](https://github.com/cogitatio/vagrant-hostsupdater)
* [Vagrant Auto-network](https://github.com/oscar-stack/vagrant-auto_network)

## Quickstart

  1. Open terminal (or [git bash](https://msysgit.github.io/) for windows users) and run the following commands --

  ```
  git clone https://github.com/beetboxvm/ansible-role-beetbox-wordpress.git wordpress && cd $_
  vagrant up
  ```

  2. Go to http://wordpress.local/

  ```
  username: admin
  password: admin
  ```

## License

MIT
