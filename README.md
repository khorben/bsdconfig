bsdconfig
=========

This is a fork of bsdconfig, a configuration tool for the system on the
[FreeBSD](https://www.FreeBSD.org) Operating System. The objective is to keep
the architecture and workflow, but to make the code more flexible and portable,
in order to more easily allow fixing issues and continuous testing.

This project is sponsored by the FreeBSD Foundation.

Dependencies
------------

bsdconfig relies on bsddialog in order to render widgets. bsddialog is imported
in FreeBSD in
[contrib/bsddialog](https://cgit.freebsd.org/src/tree/contrib/bsddialog), while
its upstream is at <https://gitlab.com/alfix/bsddialog>.

References
----------

The upstream code can be obtained at
<https://cgit.freebsd.org/src/tree/usr.sbin/bsdconfig>.

