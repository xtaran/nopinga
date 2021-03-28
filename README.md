nopinga
=======

About
-----

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

All options and parameter to options are passed to `noping` unmodified
— with the exception of unssupported options, namely `-4` and `-6`
(which make not much sense in this case) as well as `-f` (not yet
implemented.

Option accumulation is currently not supported either.


Dependencies
------------

`noping` is written in [Perl](https://www.perl.org/) and requires at
least Perl 5.10. Additionally it requires these Perl modules:

* `Net::DNS`
* `Regexp::Common`


Versioning
----------

The version number scheme adheres to [Semantic
Versioning](https://semver.org/).


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
