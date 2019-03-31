# ansible-glances

[![Build Status](https://travis-ci.org/mpataki/ansible-glances.svg?branch=master)](https://travis-ci.org/mpataki/ansible-glances)

This ansible role installs and configures [glances](https://nicolargo.github.io/glances/).

## Requirements

Really this should work on any debian based system, but has been tested on a Raspberry Pi running Rasbian (stretch).

## Role Variables

None.

## Example

```yaml
    - hosts: pi
      roles:
        - role: mpataki.glances
          tags: glances
```

