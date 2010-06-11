.. _overview:

==================
Overview
==================

These are my firefox userChrome.css and userContent.css I use with a dark gtk
theme with good results.

installing userChrome.css and userContent.css
---------------------------------------------

On my linux machine I simply create a symlink to these files in my firefox
profile:

::

  $ ln -s ~/userstyles/firefox/user{Content,Chrome}.css ~/.mozilla/firefox/<hash>.default/chrome/

Also, note the instructions in the userContent.css comments. There are a
handful of changes I had to make to the xulrunner forms.css to counteract some
dark gtk theme annoyances.
