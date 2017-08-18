ipython-ansible-jenkins
=======================

**DEPRECATED**: We are moving away from Jenkins. We will be performing more
tests with free hosted CI services (Travis, Circle, Appveyor). Some of the
integration tests we previously ran in Jenkins are now run from:
https://github.com/jupyter/test-grid

Ansible playbook for the IPython Jenkins server.

This relies on [ICTO/ansible-jenkins](https://github.com/ICTO/ansible-jenkins) as a role, so make sure to do the submodule dance after cloning, changing branches, etc.

```bash
$ git clone https://github.com/ipython/ipython-ansible-jenkins.git
$ git submodule init
$ git submodule update
```
## Installation

```
ansible-playbook -i hosts site.yml
```
