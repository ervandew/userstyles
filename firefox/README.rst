.. _overview:

==================
Overview
==================

Here is my firefox userContent.css which I use with a dark gtk theme to get a
more readable ftp view along with dark versions of server not found, ssl cert
warning page, etc.

installing userContent.css
---------------------------------------------

On my linux machine I simply create a symlink to these files in my firefox
profile:

::

  $ ln -s ~/userstyles/firefox/userContent.css ~/.mozilla/firefox/<hash>.default/chrome/
