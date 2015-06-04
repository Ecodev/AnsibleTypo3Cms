TYPO3 CMS
=========

Ansible setup that configure a TYPO3 CMS instance.

Getting Started
---------------

* Install ansible on your (local) system e.g. `brew install ansible`.
* Configure `hosts` and make sure you can ssh into your server
* Test connection with:

```
$> ansible all -m ping
```

* Adjust variables in `groups_vas/all`.
* Download Ansible dependencies

```
ansible-galaxy install -r requirements.yml
```

* Bootstrap server:

```
$> ansible-playbook bootstrap.yml
```
