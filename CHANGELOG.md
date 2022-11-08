# Ansible Role for Jira

## 6.6.0 - TBC

### Major Changes

-   Remove Fedora 35 support
-   Remove openSUSE Leap 15.3 support

## 6.5.0 - 2022-10-14

-   Support Ansible community package 6.5.0

### Major Changes

-   Default with openJDK 11
-   Support Ubuntu 22.10
-   Support Fedora 37

## 6.4.0 - 2022-09-15

### Major Changes

-   Support Ansible community package 6.4.0

## 6.3.0 - 2022-08-24

### Major Changes

-   Support Ansible community package 6.3.0

## 6.2.0 - 2022-08-03

### Major Changes

-   Support Ansible community package 6.2.0
-   Revamp manually download related with OBS repo

## 6.1.0 - 2022-07-14

### Major Changes

-   Support Ansible community package 6.1.0
-   Remove Ubuntu 21.10 support

## 6.0.0 - 2022-06-22

### Major Changes

-   Support Ansible community package 6.0.0

## 5.9.0 - 2022-06-08

### Major Changes

-   Support Ansible community package 5.9.0

## 5.8.0 - 2022-05-20

### Major Changes

-   Support Ansible community package 5.8.0
-   Remove Fedora 34 support

## 5.7.0 - 2022-04-27

### Major Changes

-   Rename Ansible Role with FQCN
-   Support Ansible community package 5.7.0
-   Support RHEL 9
-   Support CentOS 9 Stream
-   Support openSUSE Leap 15.4

## 5.6.0 - 2022-04-07

### Major Changes

-   Support Ansible community package 5.6.0
-   Support Fedora 36
-   Support Ubuntu 22.04
-   Support Ansible community package 5.5.0
-   Support Ansible community package 5.4.0

## 5.5.0 - 2022-02-11

### Major Changes

-   Remove Ubuntu 21.04 support
-   Skip package upgrade before running molecule
-   Support Fedora Rawhide
-   Support Debian Testing

## 5.4.0 - 2021-12-31

### Major Changes

-   Remove openSUSE Leap 15.2 support
-   Upgrade minimal Ansible community package support to 4.10

## 5.3.0 - 2021-10-20

### Major Changes

-   Remove Fedora 33 support
-   Remove Ubuntu 20.10 support
-   Support Fedora 35
-   Support Ubuntu 21.10
-   Upgrade minimal Ansible community package support to 4.7.0

## 5.2.0 - 2021-09-19

### Major Changes

-   Install dependencies with package manager
-   Upgrade minimal Ansible community package support to 4.5.0

## 5.1.0 - 2021-07-18

### Major Changes

-   Move systemd service to `/etc/systemd` which generally available
-   Upgrade minimal Ansible community package support to 4.2.0
-   Support Debian 11
-   Support openSUSE Leap 15.3
-   Improve download archive logic

## 5.0.0 - 2021-06-02

### Major Changes

-   Upgrade minimal Ansible support to 4.0.0
-   Remove MySQL JDBC support
-   Support Fedora 34
-   Support Ubuntu 21.04
-   Simplify download archive logic

## 4.7.0 - 2021-03-13

### Major Changes

-   Bugfix [ansible-lint `namespace`](https://github.com/ansible-community/ansible-lint/pull/1451)
-   Bugfix [ansible-lint `no-handler`](https://github.com/ansible-community/ansible-lint/pull/1402)
-   Bugfix [ansible-lint `unnamed-task`](https://github.com/ansible-community/ansible-lint/pull/1413)
-   Simplify Python dependency with system packages
-   Support RHEL 8 with Molecule
-   Support RHEL 7 with Molecule
-   Remove CentOS 8 support
-   Improve HTTP transparent proxy support
-   Remove adhoc config with environment variables
-   Bugfix session timeout
-   Improve download archive logic
-   Support CentOS 8 Stream
-   Support openSUSE Tumbleweed
-   Migrate base Vagrant box from `generic/*` to `alvistack/*`

## 4.6.0 - 2020-12-28

### Major Changes

-   Simplify Molecule scenario for vagrant-libvirt
-   Migrate from Travis CI to GitLab CI
-   Support Fedora 33
-   Remove Fedora 32 support
-   Support Ubuntu 20.10
-   Remove redundant tags from tasks

## 4.5.0 - 2020-08-26

### Major Changes

-   Upgrade minimal Ansible Lint support to 4.3.2
-   Upgrade Travis CI test as Ubuntu Focal based
-   Upgrade minimal Ansible support to 2.10.0
-   Support openSUSE Leap 15.2
-   Remove Ubuntu 19.10 support

## 4.4.0 - 2020-06-04

### Major Changes

-   Support Fedora 32
-   Install from AdoptOpenJDK repo
-   Support Debian 10
-   `molecule -s default` with delegated to localhost

## 4.3.0 - 2020-04-22

### Major Changes

-   Template `molecule -s default` with dummy docker driver
-   Support CentOS/RHEL 8
-   Support Ubuntu 20.04
-   Remove Ubuntu 16.04 support
-   Upgrade minimal Molecule support to 3.0.2
-   Migrate role name to lowercase or underline
-   Migrate group name to lowercase or underline
-   Migrate molecule `group_vars` to file
-   Download archives to `{{ ansible_user_dir }}/.ansible/tmp`
-   Remove System V init scripts

## 4.2.0 - 2020-02-13

### Major Changes

-   Migrate molecule driver to Libvirt
-   Migrate molecule verifier to Ansible
-   Support Ubuntu 19.10

## 4.1.0 - 2020-01-16

### Major Changes

-   Default `interpreter_python` with `python3`
-   Bugfix `python3-xml` not exists for openSUSE Leap 15.1
-   Replace `java` with `openjdk`

## 4.0.0 - 2019-11-05

### Major Changes

-   Upgrade minimal Ansible support to 2.9.0
-   Upgrade Travis CI test as Ubuntu Bionic based
-   Cleanup supported archives

## 3.5.0 - 2019-10-06

### Major Changes

-   Support openSUSE Leap 15.1
-   Default with Python 3
-   Revamp molecule test with vagrant
-   Abstract `jira_owner` and `jira_group` as variable
-   Abstract `jira_home` and `jira_catalina` as variable

## 3.4.0 - 2019-09-18

### Major Changes

-   Run molecule test manually on Travis CI

## 3.3.0 - 2019-08-27

### Major Changes

-   Update for RHEL 7
-   Add Vagrant test for RHEL 7
-   Download archives to `/var/cache/ansible`
-   Upgrade packages if archives not found from `/var/cache/ansible`
-   Restart service serially

## 3.2.0 - 2019-07-08

### Major Changes

-   Update LXD test profile for Kubernetes v1.15.0 support
-   Add dummy tasks and vars placeholder for multi OS support
-   Fix molecule `group_vars` with links
-   Replace `with_items` with `loop`
-   Replace `with_dict` with `var`
-   Replace `with_first_found` with `lookup('first_found')`

## 3.1.0 - 2019-06-13

### Major Changes

-   Always include default variables from `vars/main.yml`
-   Always use `become: true` with molecule, especially for vagrant
-   Abstract archive download checksum with multiple version support
-   Improve service restart implementation

## 3.0.0 - 2019-05-20

### Major Changes

-   Upgrade minimal Ansible support to 2.8.0
-   Improve handlers implementation

## 2.6.0 - 2019-05-04

### Major Changes

-   Refine Travis CI Molecue test cases

## 2.5.0 - 2019-04-17

### Major Changes

-   Pre-download archives with checksum
-   Run test with `travis_wait 120`

## 2.4.0 - 2019-03-03

### Major Changes

-   Run systemd service with specific system user
-   Add openSUSE Leap 15 support
-   Remove CentOS 6 support

## 2.3.0 - 2019-01-30

### Major Changes

-   Porting test to Molecule based

## 2.2.0 - 2019-01-26

### Major Changes

-   Add systemd service support
-   Use handler for `systemctl daemon-reload`
-   Skip JIRA_HOME enforce permission check during service start

## 2.1.0 - 2018-12-08

### Major Changes

-   Upgrade Ansible support to 2.6 or higher
-   Support both Ubuntu 16.04/18.04 and RHEL/CentOS 6/7
-   CI with yamllint, ansible-lint and ansible-playbook --syntax-check
-   CI with LXD, improve systemd support
-   Use shell only when shell functionality is required
-   Upgrade both MySQL and PostgreSQL JDBC driver
-   Simplify implementation for building Docker image

## 1.1.0 - 2017-11-23

### Major Changes

-   Install Jira on Ubuntu 16.04/14.04 and CentOS 7/6 from source
-   Update /etc/init.d/jira with better support for running with dumb-init inside docker
-   Update test cases

## 1.0.0 - 2017-09-25

-   Ininitial release for Ansible 2.4
-   Support both Ubuntu 16.04/14.04 or RHEL/CentOS 7/6
