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


Agenda
======

* Who am I?
* What is this talk?
* GUI/CUI/CLI apps examples, Pros/Cons
* Useful libraries
* Conclusion

Who am I?
=========

.. container:: progressive

   * Open Source Programmer (mostly OpenStack)
   * SUSE
   * Linux User

What is this talk, BTW?
=======================

* I like CUI/CLI applications!

  * There are a lot of benefits of CUI/CLI apps
  * CUI/CLI apps aren't scary.
  * But I also like GUI ones :)

* Some examples of CUI/CLI/GUI applications

What kind of applications do we use usually?
============================================

.. container:: progressive

   * Text Editors

     * Vim/Emacs
     * Atom, Eclipse, PyCharm
   * Mail

     * Mutt, Alpine
     * Thunderbird
   * Code review

     * gertty (see demo)
     * GitHub, Gerrit
   * presentation

     * TeX, presentty (This!)
     * Impress(LibreOffice)
   * Blog

     * pelican
     * WordPress

What kind of applications do we use usually? - cont.
====================================================

.. container:: progressive

   * Automation

     * Ansible, Chef, Puppet
     * Jenkins
     * Imagine, if Ansible has only GUI? Selenium/Web Scraping = Nightmare?
   * Virtualization

     * Docker, Kubernetes, OpenStack

   .. code::

      -> CLI(not CUI) applications are good for automation


GUI Pros/Cons
====================================

.. container:: progressive

   * :) Easy to start to use (e.g. Scratch)
   * :) Good for a graph dashboard
   * :( Slow (sometimes)
   * :( Complicated UI, bad for automation (e.g. Click here, there...)

CUI/CLI Pros/Cons
===============================

.. container:: progressive

   * :) Fast

     * Narrow bandwidth
     * Poor computer
     * No mouse needed (can be used)

       * Keep the arms position
       * Easy to show how to use
   * :) Simple

     * Easy to show how to use
     * Less bugs(?)

   * :( Difficult to start to use
   * :( Difficult to show graphs and/or images


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

* figlet: http://www.figlet.org/


Conclusion
==========

.. container:: progressive

   * CLI/CUI apps are NOT scary, but there is a learning curve
   * CLI/CUI apps should be Fast, Simple, Easy to use
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
* Similar talk

  * https://www.youtube.com/watch?v=3O60E9CpyJA
