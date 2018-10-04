
How To Clear - Scope of this training
=====================================

For official documentation on these topics please see
[https://clearlinux.org/documentation](clearlinux.org/documentation).

## Aim and scope of this training

The goal of this training is to cover most of the technology used to
create the Clear Linux\* OS. It includes extensive instructions on
how to use the tools and explains how the tools work internally. The
training uses the tools to create a custom Clear Linux OS for your
own purposes, be it testing, development or other.

A key point to this training is that we want to show users how Clear
Linux OS is made and why it matters. For this reason, the training
goes relatively deep into the methods used to create updates and how
they are deployed to targets.  The design is very different than what
a traditional software developer would use, or what is used in the
embedded sector. For that reason, the reality of how Clear Linux OS
is made may be very different from what new users may expect.

The methodology centers heavily around the concept that the target
devices should be able to update often and quickly. At the opposite
side, on the server that generates the content, the Clear Linux OS
uses more elaborate and time intensive methods to assure all clients
can properly update, which explains some of the major differences
between Clear Linux OS and other Linux distributions.

## What isn't covered

This training document is meant to provide methods and tools for
users in the public. It builds upon Open Source resources and server
content that is available to the general public.

The training does not cover `koji` specifically. The Clear Linux OS
team uses koji to maintain RPM repositories but it is only one method
to maintain RPM repositories and it is not required. Clear Linux OS
provides `koji` in a bundle for those that wish to use it.

There are many other aspects related to the maintenance of a good
Linux OS that are not covered in this training, such as legal and
liability aspects, license compliance, and others. Before you start
maintaining a Linux OS yourself, you should be aware that you may
have duties and requirements that you must follow, even if you are
reusing content from the Clear Linux OS.
