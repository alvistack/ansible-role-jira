# Ansible Role for Jira

## 3.1.0 - TBC

### Major Changes

  - Always use `become: true` with molecule, especially for vagrant
  - Improve service restart implementation

## 3.0.0 - 2019-05-20

### Major Changes

  - Upgrade minimal Ansible support to 2.8.0
  - Improve handlers implementation

## 2.6.0 - 2019-05-04

### Major Changes

  - Refine Travis CI Molecue test cases

## 2.5.0 - 2019-04-17

### Major Changes

  - Pre-download archives with checksum
  - Run test with `travis_wait 120`

## 2.4.0 - 2019-03-03

### Major Changes

  - Run systemd service with specific system user
  - Add openSUSE Leap 15 support
  - Remove CentOS 6 support

## 2.3.0 - 2019-01-30

### Major Changes

  - Porting test to Molecule based

## 2.2.0 - 2019-01-26

### Major Changes

  - Add systemd service support
  - Use handler for `systemctl daemon-reload`
  - Skip JIRA\_HOME enforce permission check during service start

## 2.1.0 - 2018-12-08

### Major Changes

  - Upgrade Ansible support to 2.6 or higher
  - Support both Ubuntu 16.04/18.04 and RHEL/CentOS 6/7
  - CI with yamllint, ansible-lint and ansible-playbook --syntax-check
  - CI with LXD, improve systemd support
  - Use shell only when shell functionality is required
  - Upgrade both MySQL and PostgreSQL JDBC driver
  - Simplify implementation for building Docker image

## 1.1.0 - 2017-11-23

### Major Changes

  - Install Jira on Ubuntu 16.04/14.04 and CentOS 7/6 from source
  - Update /etc/init.d/jira with better support for running with dumb-init inside docker
  - Update test cases

## 1.0.0 - 2017-09-25

  - Ininitial release for Ansible 2.4
  - Support both Ubuntu 16.04/14.04 or RHEL/CentOS 7/6
