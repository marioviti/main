# main
Submodule Hub for other repositories, also a meta repository.

## Licenses

There are roghly 2 kinds of licenses: permissive (do whatever just don't sue me).
GPL is less permessive and aims to propagate to all third parties that redistribute or modify work making use of it.

https://exygy.com/which-license-should-i-use-mit-vs-apache-vs-gpl/

https://tldrlegal.com/license/apache-license-1.0-(apache-1.0)

https://tldrlegal.com/license/gnu-lesser-general-public-license-v3-(lgpl-3)

### Submodules

Licenses do not extends to submodules, this also raises a controversy about what redistribution can be meant when using pointers (wich a packaging or submodule system essentially are), pointing to a software released under GPL does not implies that the pointing software is redistributing it therefore the GPL license propagation does not apply.

https://softwareengineering.stackexchange.com/questions/240633/is-licensing-an-issue-for-git-submodules

## Submodules

I tend to have libraries I developed in separate repositories, therefore submodules are the most natural way to include them in an projects/application.

## Branches

Submodules can be used as libraries, to this end I use branches to switch between projects/applications in the main repository that makes use of these in different ways.
