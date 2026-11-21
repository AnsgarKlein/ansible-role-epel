# epel (Ansible Role)

[![Molecule](https://github.com/AnsgarKlein/ansible-role-epel/actions/workflows/molecule.yml/badge.svg)](https://github.com/AnsgarKlein/ansible-role-epel/actions/workflows/molecule.yml)

Simple ansible role to enable the
[EPEL](https://docs.fedoraproject.org/en-US/epel/) repository for RHEL-based
distributions.

EPEL is enabled by installing the `epel-release` package after all prerequesite repositories (PowerTools / CodeReady Builder) have been enabled.

## Variables

_no variables yet_

## Testing

Test with Molecule using docker.

```shell
python3 -m venv venv
source venv/bin/activate
python3 -m pip install -U pip
python3 -m pip install -U -r requirements.txt
ansible-lint
molecule test
```
