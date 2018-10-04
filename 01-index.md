
How To Clear
============

For official documentation on these topics please see
[https://clearlinux.org/documentation](clearlinux.org/documentation).

## Table of Contents

 1.  [Index](01-index.md)
 2.  [Concepts](02-concepts.md)
 3.  [Extent of this training](03-scope.md)
 4.  [Basic mixing](04-mixing.md)
 5.  [Deploying a mix](05-deploying.md)
 6.  [Adding in custom RPMs](06-rpms.md)
 7.  Developer topics:
     1.  [Telemetry](07-1-telemetry.md)
     2.  [QA and testing](07-2-qa-testing.md)
     3.  [Debugging](07-3-debugging.md)

```
~ $ git clone https://github.com/clearlinux/how-to-clear
~ $ sudo swupd update
```

## Foreword

Clear Linux OS for Intel® Architecture was designed a long time ago
to fill a major gap in the existing Linux OS ecosystem. The problem
identified was that Linux OS distributions were either updated once
or twice a year, or the distro turned your system into a dependency
hell because it allowed your package management system to combine
incompatible components.

Clear Linux OS attempts to solve this problem by preventing you from
combining fundamentally incompatible components, and allowing you to
update with a frequency of several times a day, if needed. This allows
users to receive smaller updates and maintain functional software
without the overhead of dealing with software incompatibilities.

Over the last few years, the Clear Linux OS team has consistently
delivered this in a usable form and we've used Clear Linux OS as
a vehicle to deliver much more technological advancement to users.
We've also allowed people to use our tooling to do exactly the same,
without recreating Clear Linux OS from scratch. Our tooling, concepts,
and content are modular and Free (as in beer and speech), and we have
published everything.

The tooling covered in this training reproduces what the Clear Linux
OS team develops and uses to create and maintain the OS. The tooling
allows users to create a derivative OS that is based on Clear Linux
OS in various degrees of similarity. Either the derivative can be
entirely new and use only the tooling provided, or the derivative
can contain only minor changes.

The training revolves around mixer from start to finish, and makes
several segues into more advanced topics that are relevant for the
whole picture. In all details, we show in precise ways how the actual
deployment of the results of the advanced topics can be pushed to
actual target OS installations.

## About this document

This training document is a living training that will be adopted in
the future to adjust for changes in the tooling and options, as well
as any fixes that must be included.

The content itself is designed to be self-contained and allow someone
to use a clean Clear Linux OS installation to do the training in its
entirety. There should not be a need to install third party software,
and the training material should explain all the concepts without
the need for external reference documentation. It is expected that
people will consult manual pages where appropriate.

Due to the nature of the Clear Linux OS tools, a functional network
connection is required to use many of the tools. While it is possible
to create a set of trainings that would function entirely offline,
this would be time consuming and out of date almost immediately.

This training is hosted on github. We appreciate any feedback and
comments, especially in the form of Pull Requests. Please visit the
project page to open a ticket or clone/branch the training and help us.

[how-to-clear](https://github.com/clearlinux/how-to-clear/)

For the convenience of students, we've included a folder called `files`
and added most of the files that need to be created or downloaded
during the training exercises. This allows students to skip through
some of the steps and get the proper files in place quickly and stay
focused on the topic without spending time on meta-problems.

## Need help?

The Clear Linux OS team can be reached for generic questions about
Clear Linux OS, bugs, feedback, and any relevant discussion through
the following methods:

* [Mailinglist](https://lists.clearlinux.org/mailman/listinfo/dev)
* [IRC](http://webchat.freenode.net?channels=%23clearlinux)
* [Github](https://github.com/clearlinux/distribution)
