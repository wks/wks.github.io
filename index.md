---
# You don't need to edit this file, it's empty on purpose.
# Edit theme's home layout instead if you wanna make some changes
# See: https://jekyllrb.com/docs/themes/#overriding-theme-defaults
layout: default
title: Home
---

## Research

My research interests include the implementation of programming
languages, especially those with garbage collection.

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

K. Wang, Y. Lin, S. M. Blackburn, M. Norrish, and A. L. Hosking,
"**Draining the Swamp: Micro Virtual Machines as Solid Foundation for Language Development,**"
in *1st Summit on Advances in Programming Languages (SNAPL 2015)*, 2015.
[pdf](downloads/pdf/uvm-snapl-2015.pdf)

Y. Lin, K. Wang, S. M. Blackburn, M. Norrish, and A. L. Hosking,
"**Stop and Go: Understanding Yieldpoint Behavior,**"
in *Proceedings of the Fourteenth ACM SIGPLAN International Symposium on Memory Management, ISMM '15, Portland, OR, June 14, 2015*, 2015. 
[pdf](downloads/pdf/yieldpoint-ismm-2015.pdf)

## Contact

Email: wks1986 AT gmail DOT com

{% if false %}
vim: tw=72 spell
{% endif %}
