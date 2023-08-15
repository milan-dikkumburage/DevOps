# Installation Instructions

## 1. Install Ansible on CentOS 7 / Red Hat 8

```bash
sudo subscription-manager repos --enable ansible-2.9-for-rhel-8-x86_64-rpms
sudo yum install ansible -y

## 2. How to Install htop on CentOS 7 / Red Hat 8

```bash
sudo subscription-manager repos --enable codeready-builder-for-rhel-8-$(arch)-rpms
sudo yum install https://dl.fedoraproject.org/pub/epel/epel-release-latest-8.noarch.rpm
sudo yum install htop -y
