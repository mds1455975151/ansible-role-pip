ansible-role-pip    [![Build Status](https://www.travis-ci.org/mds1455975151/ansible-role-pip.svg?branch=master)](https://travis-ci.org/mds1455975151/ansible-role-pip)
=========

This role install pip (Python package manager tools) and configure repository mirror.

Role Variables
--------------
    # Pypi mirrors website url
    pip_index_url: http://mirrors.aliyun.com/pypi/simple/

    # Pypi mirrors host
    pip_mirrors_host: mirrors.aliyun.com

    # Install with the package installer (package) or the get-pip installer (installer)
    pip_install_method: "package"

    # The url for the get-pip.py installer
    pip_install_url: "https://raw.githubusercontent.com/pypa/pip/master/contrib/get-pip.py"

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: servers
      roles:
         - { role: mds1455975151.ansible-role-pip }

License
-------

BSD

Author Information
------------------

An optional section for the role authors to include contact information, or a website (HTML is not allowed).
