## mimetex

[![Build Status](https://travis-ci.org/Oefenweb/ansible-mimetex.svg?branch=master)](https://travis-ci.org/Oefenweb/ansible-mimetex) [![Ansible Galaxy](http://img.shields.io/badge/ansible--galaxy-mimetex-blue.svg)](https://galaxy.ansible.com/Oefenweb/mimetex)

Set up [mimeTeX](http://www.forkosh.com/mimetex.html) in Ubuntu systems.

#### Requirements

* `build-essential` (will be installed)
* `libc6-dev-i386` (will be installed)
* `git-core` (will be installed)

#### Variables

* `mimetex_version` [default: `1.74-1`]: What version of mimetex to check out (set up). This can be either `1.50-1.1`, `1.73-2` or `1.74-1`
* `mimetex_install_dir` [default: `/usr/bin`]: Install directory

## Dependencies

None

#### Example

```yaml
---
- hosts: all
  roles:
    - mimetex
```

#### License

MIT

#### Author Information

Mischa ter Smitten

#### Feedback, bug-reports, requests, ...

Are [welcome](https://github.com/Oefenweb/ansible-mimetex/issues)!
