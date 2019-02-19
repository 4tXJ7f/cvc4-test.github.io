---
layout: post
title: "Mac and Win32 Nightly Builds Available"
author: "Morgan Deters"
tags: outdated
---

As mentioned on the [users’ mailing
list](http://cs.nyu.edu/pipermail/cvc-users/2013/000434.html) the other day,
[Win32 binaries are now
available](http://cvc4.cs.nyu.edu/builds/win32-opt/unstable/) for our nightly
development builds (and will be available for the next stable release, coming
soon).

Additionally, [Mac builds are available](http://cvc4.cs.nyu.edu/builds/macos/)
for the 1.0 release and for the nightly development “unstable” versions.  Or,
even better, if you have [MacPorts](http://www.macports.org/) installed, you
can add our repository to your sources.conf (you’ll probably find it in
/opt/local/etc/macports/sources.conf):

~~~bash
rsync://cvc4.cs.nyu.edu/macports/
~~~

and once you’ve updated your cache (“`sudo port sync`“) then you can easily
install the stable version (“`sudo port install cvc4`“) or the latest nightly
build (“`sudo port install cvc4-devel`“).
