FOSSAsia Summit 2018
====================

.. figlet:: CUI/CLI Software Again

.. code:: yaml

     Name     : Masayuki Igawa
     Slide URL: https://github.com/masayukig/terminal-software-again
     Date     : Sunday, March 25 2018

.. Most of the people really like webUI and/or smartphone UI. We think
   they are really fancy and cool. However, it sometimes requires
   complicated operation with a mouse, swipe and taps. Moreover, it's
   really hard to tell the operation to the others. We need a lot of
   screenshots to do that. Instead of that, there are a lot of CUI/CLI
   tools as alternatives. They are really simple but powerful and
   fast. In this session, audience can see the benefit of CUI/CLI
   tools. As a developer, GUI is really hard to make a fancy and modern
   design software. We actually have a lot of options not only GUI
   applications but also CUI/CLI applications.

   I really love CUI/CLI applications recently. Because it's fast,
   lightweight and can be operated with only a keyboard not mouse. In
   this talk, I'll give ...

DISCLAIMER
==========

| These slide are my own opinion.


Who am I?
=========

.. container:: progressive

   * OpenStack Programmer
   * SUSE
   * Linux User

What is the GUI/CUI/CLI application?
====================================




GUI Pros/Cons
====================================

.. container:: progressive

   * Easy to start to use
   * Good for a graph dashboard
   * Slow
   * Complicated

Benefits of CUI/CLI application
====================================

.. container:: progressive

   * Fast

     * Narrow bandwidth
     * Poor computer
     * No mouse

       * Keep the arms position
       * Easy to show how to use
   * Simple

     * Easy to show how to use
     * Less bugs(?)

What kind of applications do we use usually?
============================================

.. container:: progressive

   * Text Editors

     * Vim/Emacs
   * Mail

     * Mutt, Alpine
   * code review

     * gertty
   * presentation

     * presentty
   * Blog

     * pelican

What kind of applications do we use usually? - cont.
====================================================

.. container:: progressive

   * Automation

     * Ansible
     * Chef
     * Puppet
   * Virtualization

     * Docker
     * Kubernetes
     * OpenStack

How to make it? - Useful libraries and commands
===============================================

* urwid: https://pypi.python.org/pypi/urwid
* cliff: https://pypi.python.org/pypi/cliff
* jp2a: https://github.com/cslarsen/jp2a

  * jp2a 1.0.8 works but not in 1.0.7..

    .. code:: bash

       $ git clone https://github.com/cslarsen/jp2a
       $ autoreconf -vi
       $ ./configure --with-jpeg-prefix=/usr/local \
         --with-curl-config=`which curl-config`
       $ make -j && make -j install

Conclusion
==========

.. container:: progressive

   * CLI/CUI applications should be Fast, Simple, Easy to use
   * Graphs, Images are should be on GUI applications
   * Making CLI/CUI application is fun!

Appendix
========

* Web browser

  * Lynx, w3m, curl, wget

* bug management

  * boartty

* IoT

  * mqtty

* Games

  * ....? :-p

