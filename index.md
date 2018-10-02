---
# You don't need to edit this file, it's empty on purpose.
# Edit theme's home layout instead if you wanna make some changes
# See: https://jekyllrb.com/docs/themes/#overriding-theme-defaults
layout: default
title: Home
---

## About Me

I am currently employed in [Huawei](https://www.huawei.com) as a Senior
Engineer.

I was a PhD student in the
[College of Engineering and Computer Science](https://cecs.anu.edu.au/)
in the [Australian National University](http://www.anu.edu.au/).  My
supervisor was
[Steve Blackburn](http://users.cecs.anu.edu.au/~steveb/).
My research interest is the design and implementation of managed
languages, i.e. the kind of languages that usually run on virtual
machines and usually use garbage collection.  My
[thesis](http://hdl.handle.net/1885/147871) introduced the abstraction
layer of [micro virtual machines](https://microvm.org/) which aim to
allow the development of higher-quality, higher-performance managed
languages.

## Projects

I have some open-source projects for my researches, or for fun.

[**The Mu micro virtual machine**](https://microvm.org/): Mu is a
so-called "micro virtual machine", a minimal managed runtime for
language implementations.  Like microkernels, a micro VM only includes
essential parts of traditional language VMs (such as JVM, .NET, etc.),
and off-loads non-essential parts to a separate layer (a micro VM
"*client*").  This design intends to provide a reliable foundation for
the implementations of high-level languages.  I am the chief architect
of this project, and am responsible for its
[specification](https://gitlab.anu.edu.au/mu/mu-spec) and its [reference
implementation](https://gitlab.anu.edu.au/mu/mu-impl-ref2).

[**JSON HTML Query Language**](https://github.com/wks/jhql): A simple
tool for extracting text contents from HTML documents.

[More projects are hosted on GitHub.](https://github.com/wks)

## Publications

{% include publication_list.html %}

## Contact

Email: wks1986 AT gmail DOT com

{% if false %}
vim: tw=72 spell
{% endif %}
