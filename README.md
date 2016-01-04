# Ansible Role: Beetbox Backdrop

An Ansible role that creates and installs a WordPress project on beetbox.

## Requirements

This role is specifically developed as an extention to beetbox -- https://github.com/drupalmel/beetbox

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

## Dependencies

- Beetbox -- https://github.com/drupalmel/beetbox

## License

MIT