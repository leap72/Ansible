# Overview
Installs and configures varnish.

Varnish is an HTTP accelerator designed for content-heavy dynamic web
sites as well as heavily consumed APIs. In contrast to other web accelerators, 
such as Squid, which began life as a client-side cache, or Apache and nginx,
which are primarily origin servers, Varnish was designed as an HTTP accelerator. 
Varnish is focused exclusively on HTTP, unlike other proxy servers that often i
support FTP, SMTP and other network protocols.

Reference: https://www.varnish-cache.org/

## Requirements

none

## Role Variables

none

## Dependencies

none

## Example Playbook

    - hosts: all
      roles:
         - role: varnish

## License

MIT

## Author Information

Leap SOK <leap@sys-expert.com>
