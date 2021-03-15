software_chrome
=========

This role will install software_chrome software

Requirements
------------

All dependencies will appear on requirements.yml file

Role Variables
--------------

software_packages:
  - google-chrome-stable

repo_url: 'deb [arch=amd64] http://dl.google.com/linux/chrome/deb/ stable main' # chrome repository
repo_key: 'https://dl-ssl.google.com/linux/linux_signing_key.pub' # chrome key

Not defined yet. But in the future we could stage software version in here

Dependencies
------------

All dependencies will appear on requirements.yml file

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: servers
      roles:
         - { role: software_chrome }

License
-------

BSD

Author Information
------------------
Made by @sergi-canas
