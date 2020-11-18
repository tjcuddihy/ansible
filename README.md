# Getting Started
---------------

1. Install [homebrew](http://brew.sh/) with the command from the site
1. `git clone git@github.com:tjcuddihy/ansible-mac.git`
1. `cd ansible-mac`
1. `brew install pyenv`
1. `pyenv install <latest_python_version>` (Check playbook up to date)
1. Make sure pyenv's python on path (it will be after my shell settings are in place from playbook)
1. `python -m venv venv`
1. `source venv/bin/activate`
1. `pip install ansible` (always the best way to install Ansible)
1. Then `./playbook.yml`
