## mimetex

[![CI](https://github.com/Oefenweb/ansible-mimetex/workflows/CI/badge.svg)](https://github.com/Oefenweb/ansible-mimetex/actions?query=workflow%3ACI)
[![Ansible Galaxy](http://img.shields.io/badge/ansible--galaxy-mimetex-blue.svg)](https://galaxy.ansible.com/Oefenweb/mimetex)

Set up [mimeTeX](http://www.forkosh.com/mimetex.html) in Ubuntu systems.

#### Requirements

* `build-essential` (will be installed)
* `libc6-dev-i386` (will be installed)
* `git` (will be installed)

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
    - oefenweb.mimetex
```

#### License

MIT

#### Author Information

Mischa ter Smitten

#### Feedback, bug-reports, requests, ...

Are [welcome](https://github.com/Oefenweb/ansible-mimetex/issues)!
