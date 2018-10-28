<p align="center"><img src="https://user-images.githubusercontent.com/4303310/44336611-0b307500-a489-11e8-9008-9e75ae746ef8.png" /></p>

> Ansible role to deploy/setup Java on ubuntu 
<p align="center">
    <a href="LICENSE.md">
      <img src="https://img.shields.io/badge/license-MIT-brightgreen.svg?style=flat-square" alt="Software License">
    </a>
    <a href="https://www.paypal.me/anmolnagpal">
      <img src="https://img.shields.io/badge/paypal-donate-179BD7.svg?style=flat-squares" alt="Donate">
    </a>
  </p>
</p>

## Role Variables

```yamlex
java_open_jdk_set_version: '8'
java_oracle_jdk_version: '1.8.0_181'
```

## Usage

### OpenJDK

To set multiple versions

```
java_open_jdk_version: ['6', '7', '8']
```

To set system defaults

```
java_open_jdk_set_version: '8'
```


## Example Playbook

```yaml
- hosts: java
  roles:
    - role: ansible-java
      become: true
```
## 👬 Contribution
- Open pull request with improvements
- Discuss ideas in issues

- Reach out with any feedback [![Twitter URL](https://img.shields.io/twitter/url/https/twitter.com/anmol_nagpal.svg?style=social&label=Follow%20%40anmol_nagpal)](https://twitter.com/anmol_nagpal)
