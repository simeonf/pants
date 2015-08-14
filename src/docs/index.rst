Pants Build
===========

**Welcome to the Pants Build System.** Pants is a build system for
software projects in a variety of languages. It works particularly well
for a source code repository that contains many distinct projects.

Getting started using Pants
---------------------------

Tutorials and basic concepts. How to use Pants to build things. How to
configure build-able things in BUILD files.

.. toctree::
   :maxdepth: 1

   first_concepts
   first_tutorial
   target_addresses
   links/jvm_targets
   links/python_projects
   links/page
   build_files
   invoking
   tshoot

Troubleshooting
---------------

-  Something that usually works just failed? See
   :ref:`tshoot`.
-  Publishing can fail in more ways. See :ref:`publish`.

Pants Patterns
--------------

Common Pants build idioms.

-  [[Third-Party Dependencies\|pants('src/docs:3rdparty')]]
-  [[Thrift\|pants('examples/src/thrift/org/pantsbuild/example:readme')]]
-  [[Publishing Artifacts\|pants('src/docs:publish')]]

Using Pants With...
-------------------

-  [[Emacs and Ensime\|pants('src/docs:with\_emacs')]]
-  [[IntelliJ IDEA\|pants('src/docs:with\_intellij')]]

News
----

-  [[Release History (Changelog)\|pants('src/python/pants:changelog')]]
-  [[2014-09-16 Announcement\|pants('src/docs:announce\_201409')]]
   "Hello Pants Build"

Powered by Pants
----------------

-  [[Find out why some organizations are using
   Pants\|pants('src/docs:powered\_by')]]

Advanced Documentation
----------------------

-  [[Set up your Source Tree for Pants\|pants('src/docs:setup\_repo')]]
-  [[Installing Pants\|pants('src/docs:install')]]

Pants Reference Documentation
-----------------------------

-  BUILD Dictionary
-  Options Reference

Contributing to Pants
---------------------

How to develop Pants itself and contribute your changes.

-  [[Pants Developer Center\|pants('src/python/pants/docs:readme')]]

