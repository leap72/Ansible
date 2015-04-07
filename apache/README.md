# Overview

Installs and configures [Apache HTTP Server](http://httpd.apache.org/).

It also installs Apache Modules and configures [`fcgi`](www.fastcgi.com) and [`suexec`](http://en.wikipedia.org/wiki/SuEXEC).


## Requirements

none

## Role Variables

none

## Dependencies

none

## Example Playbook

    - hosts: all
      roles:
         - role: apache

## License

MIT

## Author Information

Leap Sok <leap@sys-expert.com>
