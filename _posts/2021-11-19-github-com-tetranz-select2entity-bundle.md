---
title: select2entity-bundle
categories: ['php']
---
## [select2entity-bundle](https://github.com/tetranz/select2entity-bundle)

### A Symfony2 bundle that integrates Select2 as a drop-in replacement for a standard entity field on a Symfony form.


This is a Symfony bundle which enables the popular [Select2](https://select2.github.io) component to be used as a drop-in replacement for a standard entity field on a Symfony form.

It works with Symfony 4 and 5. For Symfony 2 and 3, please use version or 2.x of the bundle.
For Select2 4.0 and above. For older versions, use version 1.x of the bundle (not compatible with Symfony 5).

The main feature that this bundle provides compared with the standard Symfony entity field (rendered with a html select) is that the list is retrieved via a remote ajax call. This means that the list can be of almost unlimited size. The only limitation is the performance of the database query or whatever that retrieves the data in the remote web service.

It works with both single and multiple selections. If the form is editing a Symfony entity then these modes correspond with many to one and many to many relationships. In multiple mode, most people find the Select2 user interface easier to use than a standard select tag with multiple=true with involves awkward use of the ctrl key etc.

The project was inspired by [lifo/typeahead-bundle](https://github.com/lifo101/typeahead-bundle) which uses the Typeahead component in Bootstrap 2 to provide similar functionality. Select2Entity can be used anywhere Select2 can be installed, including Bootstrap 3.

Thanks to @ismailbaskin we now have Select2 version 4 compatibility.
