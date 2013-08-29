openSUSE-vagrant-box
====================

Dropbox download links:
 - [openSUSE-12.3](http://bit.ly/openSUSE-12-3-virtualbox-box) - 527 MB

This VM is a vanilla installation of openSUSE 12.3 inside VirtualBox from the network media. All the packages were updated on August 28, 2013. In addition:

  - kernel-desktop was removed in favour of kernel-default
  - removed *yast2*, *glibc-locale*, w3m, wol, wireless-tools, wireless-regdb some others

Comes with ruby2.0 from [devel:languages:ruby](https://build.opensuse.org/project/show?project=devel%3Alanguages%3Aruby%3Aextensions) and chef (package
  rubygem-chef 11.6.0-14.2) from
  [devel:languages:ruby:extensions](https://build.opensuse.org/project/show?project=devel%3Alanguages%3Aruby%3Aextensions). These
  repositories were left enabled by default.

  The box has only **360 MB RAM** - [recommended by vagrant docs](http://docs-v1.vagrantup.com/v1/docs/base_boxes.html).
