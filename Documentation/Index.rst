.. include:: Includes.txt

.. _start:

===========================================
Welcome to the official TYPO3 Documentation
===========================================

TYPO3 CMS is an Open Source Enterprise Content Element System based on PHP.



.. rst-class:: horizbuttons-primary-m

- :ref:`tutorials`
- :ref:`references`
- :ref:`extensions`
- :ref:`whats_new`

__________________________________________________

.. _start-getting-stared:

Getting Started
===============

If you are new to TYPO3, it is recommended that you start with these resources:

Installation and basic setup:
    * Setup up your system according to the :ref:`System requirements <t3install:system-requirements>`
      for installing TYPO3
    * Follow :ref:`Quick installation with Composer <t3install:install-via-composer>`
      to install TYPO3
    * Set up the :ref:`site configuration <sitehandling-basics>` in the backend to configure
      the domain, languages, URLs and error pages.

Tutorials:
    * The :ref:`t3start:start` walks
      you through the backend - the interface for editing content and configuring the TYPO3
      installation. You need a browser and a working TYPO3 installation.
    * Look for more tutorials on :ref:`tutorials`

Get Help:
    * You can ask for support via StackOverflow or Slack
    * Find out more on the `help page <https://typo3.org/help>`__



.. _how-the-documentation-is-organized:

How the documentation is organized
==================================

* :ref:`Tutorials and Guides <tutorials>` is a comprehensive list of
  further guides and tutorials for each area of the CMS.
* The :ref:`references` section provides information about the TYPO3 core
  for a technical audience (developers, integrators). The main reference
  manual is :ref:`t3coreapi:start`.
* :ref:`System-Extensions` contains documentation for system
  extensions. These are extensions that are included in the
  TYPO3 core.
* :ref:`extensions` can be used to search for documentation of third party
  extensions.

Find out more about how to use the documentation and navigate in the :ref:`usage-tips`.

.. todo:: we can remove this once version selector is more prominent via the theme.

.. todo:: we can remove this once search is improved

* Specifically, you might want to read about the
  :ref:`Version selector <usage-version-selector>` which is used to switch to
  documentation for other versions.
* Find out how to :ref:`usage-browse-pages-by-keyboard`
* See our tips on using :ref:`usage-search`



.. _start-theme:

Create a theme
==============

*Theme* | *Templating* | *Sitepackage*

It is good practice to create a **Sitepackage**. This is an extension which
contains the resources required for a theme.

Sitepackage
    * `Concept of Sitepackages <https://www.slideshare.net/benjaminkott/typo3-the-anatomy-of-sitepackages>`__
    * :ref:`t3sitepackage:start`

More introductions
    * The `Fluid documentation <https://github.com/TYPO3/Fluid>`__
      contains information about Fluid. As it is an independent project, the documentation is not
      maintained on docs.typo3.org.
    * The system extension :ref:`fluid_styled_content <fsc:start>` handles the rendering of the default
      set of content elements shipped with the core by using the template engine
      `Fluid <https://typo3.org/fluid>`__
    * :ref:`Backend layouts <t3coreapi:be-layout>`
    * :ref:`Create custom content elements <t3coreapi:adding-your-own-content-elements>`

References
    * :ref:`t3tsref:start`
    * :ref:`t3viewhelper:start`


.. _start-extdev:

Develop custom extensions
=========================

:ref:`references` lists all relevant core manuals. One of these is
"TYPO3 Explained". It contains detailed information for core and extension developers,
for example:

* :ref:`QueryBuilder <t3coreapi:database-query-builder>` based on
  Doctrine
* :ref:`t3coreapi:DependencyInjection`
* :ref:`t3coreapi:request-handling`
* :ref:`t3coreapi:mail`

More topics can be found in :ref:`t3coreapi:start`.

For further information, look in the references:

* :ref:`t3tsref:start`: TypoScript is used for configuration *and* templating.
* :ref:`t3tca:start`: TCA is specific to database fields and how they behave and
  can be edited in the backend.
* :ref:`t3tsconfig:start`: is used to configure and customize the backend on a page
  (page TSconfig) and a user or group basis (user TSconfig).

If you are updating TYPO3 to the next major version, you may need to make changes
in your custom extensions.

The `Core changelog <https://docs.typo3.org/c/typo3/cms-core/master/en-us/>`__ lists
all relevant changes for each TYPO3 version since 7.



.. _start-configuration:

Configure TYPO3
===============

A major feature for TYPO3 is its configurability. The :ref:`t3coreapi:config-overview`
in "TYPO3 Explained" gives you an overview of various configuration languages.


Specifically, you might want to

* Set up the :ref:`site configuration <sitehandling-basics>` in the backend to configure
  the domain, languages, URLs and error pages.
* Configure :ref:`rte_ckeditor <ckeditor:configuration>`
  to enhance the editing experience when handling rich text editing.
* :ref:`Configure the form system extension <form:quickstartIntegrators>` to create
  custom forms for the frontend.
* :ref:`Configure backend users <t3start:user-management>`



.. _start-localization:

How to create translations
==========================

*Internationalization* | *Translation* | *Multiple Languages*

* :ref:`Supported languages <t3coreapi:i18n_languages>`
* :ref:`Manage backend languages <t3start:changing-backend-language>`
* :ref:`Working with languages as an editor <t3editors:languages>`
* :ref:`t3coreapi:internationalization` in "TYPO3 Explained"


.. _start-coredev:

Contribute to the core
======================

The "Core contribution guide" contains information for creating core
patches:

 * :ref:`Create a patch <t3contribute:quickstart-create-a-patch>`
 * :ref:`Commit message rules <t3contribute:commitmessage>`
 * :ref:`Setup an installation with DDEV <t3contribute:ddev>`

But contribution is not just about writing patches. You can contribute
in numerous ways, including

* :ref:`Writing issues <t3contribute:forge-index>`
* :ref:`Rewiew patches <t3contribute:improving-a-patch>`



.. _start-contribute-docs:

Contribute to official documentation
====================================

You are welcome to click on the "Edit me on GitHub" button on any page
to propose a change in the official documentation if you see something that
can be improved.

* :ref:`h2document:docs-contribute` gives a good introduction to the workflow
* The documentation is edited in text files using reStructuredText syntax.
  Use the :ref:`rest-cheat-sheet` to lookup most commonly used directives.

.. toctree::
   :hidden:

   Getting Started <https://docs.typo3.org/#gettting-started>
   Home/GuidesAndTutorials
   Home/References
   Home/Extensions
   Home/WhatsNew
   Cheat Sheets ➜ <https://docs.typo3.org/m/typo3/docs-cheatsheets/master/en-us/>
   Tell Me Something About Topic X  ➜  <https://docs.typo3.org/typo3cms/TellMeSomethingAbout/>
   Snippets  ➜  <https://docs.typo3.org/typo3cms/Snippets/>
   Home/About/Index
   Home/Contribute

