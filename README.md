Ansible Role: home
==================

[![Build Status](https://travis-ci.org/noitorai/ansible-role-home.svg?branch=master)](https://travis-ci.org/noitorai/ansible-role-home)

自分の home 環境を構築するためのロールです。

Requirements
------------

よく使うパッケージをインストールする場合には、root権限が必要です。

Role Variables
--------------

[defaults/main.yml](defaults/main.yml) を参照してください。

Dependencies
------------

なし

Example Playbook
----------------

```
    - hosts: servers
      roles:
         - home
```

License
-------

[Apache License 2.0](LICENSE)
