This is a fork of Cisco + Shruberry's Tacacas+ daemons (http://www.shrubbery.net/tac_plus/)

## INSTALL file
This is a modified version of Cisco's tacacs+ (tac_plus) "developer's
kit."

Quick Installation Guide (an example):

1) ./configure [--prefix=<basedir>]
   By default, All tac_plus crud will be installed under /usr/local.
   This can be overridden with the --prefix option.  E.g.:

        ./configure --prefix=/usr/pkg

   see ./configure --help for other configure options.

2) make install

3) it may be necessary, or you may want to, add tacacs to your /etc/services
   file in order for tacacs to work properly.  eg:

   tacacs       tcp/49

4) read the tac_plug(8) manual page

5) Send any bugs, suggestions or updates to tac_plus@shrubbery.net.
   See the web page at http://www.shrubbery.net/tac_plus.

Prerequisites for building:
- Wietse Venema's TCP wrappers library

