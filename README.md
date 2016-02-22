Views Litepager
===============

Description
-----------
The Views Litepager module solves a problem of scalability for sites with large
amounts of content. COUNT queries executed on large datasets when using the
InnoDB MySQL engine can be painfully slow. This module adds a new pager option
for Views called "Lite pager" that does not execute the problematic COUNT query.
The Lite pager does not include the total number of pages of content like the
core Drupal pager does, but it does allow users to navigate from page to page.

Installation
------------

1. Install this module using the official Backdrop CMS instructions at
https://backdropcms.org/guide/modules

Usage
-----

To use the Lite pager for a specific view, navigate to your view's edit interface
and click to edit the pager settings. You will see a new option called Lite pager.
Simply select this Lite pager option and save your view.

License
-------

This project is GPL v2 software. See the LICENSE.txt file in this directory for
complete text.

Maintainers
-----------

- Herb v/d Dool (https://github.com/herbdool/)

Credit
------

Originally written for Drupal by Nathan Rambeck http://nathan.rambeck.org
