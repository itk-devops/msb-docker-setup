# Ansible docker installation for Ubuntu

This is a collection of ansible roles to setup docker with standard server configuration on ubuntu in AAK.

## Usage

```shell
ansible-playbook -i hosts ubuntu-docker.yml --limit deploy-test.itkdev.dk
```