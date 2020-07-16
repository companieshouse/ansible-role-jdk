# ansible-role-jdk
An Ansible role for installing OpenJdk.

## Requirements

The target host should be setup prior to the run. This role has been setup and has been tested against Centos8 for use of AMIs. The requirements include:
- CentOS 8 based AMI
- Python3 installed

## Role Variables

Variable         |Default     | Description
-----------------|:------:    |-------------
version          |`1.8.0`     | The java version to install
java_home        |`/usr/lib/jvm/java-1.8.0-openjdk-1.8.0.<release>.x86_64` | The default java path and JAVA_HOME are set within the Ansible provisioning tasks

## Dependencies

None.

### Example Requirements File

The version is the branch name which indicates the version of Java you require for your project
```
- src: https://github.com/companieshouse/ansible-role-jdk
  name: ansible-role-jdk
  version: "java8"
```  

## License

MIT
