[![Build Status](https://travis-ci.org/wtanaka/ansible-role-lz4.svg?branch=master)](https://travis-ci.org/wtanaka/ansible-role-lz4)
[![CircleCI](https://circleci.com/gh/wtanaka/ansible-role-lz4.svg?style=svg)](https://circleci.com/gh/wtanaka/ansible-role-lz4)

wtanaka.lz4
===========

Install lz4

Example Playbook
----------------

    - hosts: all
      roles:
         - lz4

### `lz4_should_shortcircuit`

Default: True

When True, this role short-circuits itself if a "lz4" is already in the path

### All variables

The full set of configuration options available are visible in
[defaults/main.yml](defaults/main.yml)


Author Information
------------------

http://wtanaka.com/
