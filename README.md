[![CircleCI](https://circleci.com/gh/andrewrothstein/ansible-couchdb-lucene.svg?style=svg)](https://circleci.com/gh/andrewrothstein/ansible-couchdb-lucene)
andrewrothstein.couchdb-lucene
===========================

Installs [CouchDB Lucene](https://github.com/rnewson/couchdb-lucene)

Requirements
------------

See [meta/main.yml](meta/main.yml)

Role Variables
--------------

See [defaults/main.yml](defaults/main.yml)

Dependencies
------------

See [meta/main.yml](meta/main.yml)

Example Playbook
----------------

```yml
- hosts: servers
  roles:
    - andrewrothstein.couchdb-lucene
```

License
-------

MIT

Author Information
------------------

Andrew Rothstein <andrew.rothstein@gmail.com>
