nopinga
=======

`nopinga` is a small wrapper around `noping`, the NCurses frontend to
[liboping](https://github.com/octo/liboping) to allow to ping all
addresses a hostname given on the commandline potentially resolves to.

This helps to ping both, IPv4 and IPv6 addresses of dual-stack hosts
as well as pinging all IP addresses of loadbalancer systems.

It is essentially an implementation of [liboping issue
#52: Please add a (n)oping option to ping all IP addresses (i.e. both,
IPv4 and IPv6) for given
hostnames](https://github.com/octo/liboping/issues/52), so far only
for `noping`, but it should be easy to add support for `oping`, too.

Author, Copyright and License
-----------------------------

This program is free software: you can redistribute it and/or modify
it under the terms of the GNU General Public License as published by
the Free Software Foundation, either version 3 of the License, or
(at your option) any later version.

This program is distributed in the hope that it will be useful, but
WITHOUT ANY WARRANTY; without even the implied warranty of
MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
GNU General Public License for more details.

You should have received a [copy of the GNU General Public
License](LICENSE.md) along with this program.  If not, see
https://www.gnu.org/licenses/.
