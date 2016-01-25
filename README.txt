Countries list module
======================================================

DESCRIPTION
------------
This module provides the possibility to add a field with a list of countries,
something which is very usual when building a site with registered users.
In front of other existent modules, this offers extrem simplicity on its
configuration since it is based on the core list of countries, which means
that you instantly get the list of all the countries with their translation
on you own language (if you are using the translation provided for Drupal
core on your language which is likely to have all the countries properly
translated to your language). Having the list of countries "as a list" is
far better than using a simple text field, because it avoids spelling errors
on user input.

The advantage of that module is that it is simple, uses a resource existing
on every installed Drupal site and it is multilingual. Other modules fail on
that list. Location or Address Field are very complete addresses solutions
that provide the country list and its translation, but among many other fields
that you will not require if you are just trying your users to introduce their
country. Countries is a very powerful module to manage a list of countries
despite it fails on its multilingual approach, which obligues to introduce the
translation name to every country through regular locale translation, when
countries are already translated on the core list, which is not used. All
these modules may be interesting for many other reason, but very heaveweight
for just having a countries list field on you entities.

Using it is very easy: activate the module as any other module, and add a
field of type "Countries", that's all. And enjoy! The output formatter
provides 3 possibilities: the translated name on the current language, the
country code and the country code on lowercase. It has been tested with Views,
Field Formatter Conditions and Rules.

REQUIREMENTS
------------
Drupal 7.x

INSTALLATION
------------
1.  Place both the module into your modules directory.
    This is normally the "sites/all/modules" directory.

2.  Go to admin/build/modules. Enable the modules.
    The "Countries list" modules is found in the Fields section.

Read more about installing modules at http://drupal.org/node/70151

3.  Add a field to your entity
    The module provides a new type of field called "Countries"
	on the regular menu for selection types of fields. From that
	point is configured like any other module, since it does not
	have extra parameter on its own.

AUTHOR
-------
Jordi Trujillo Rius - http://drupal.org/user/25348 (jorditr@innodus.com)


VERSIONS
--------
1.0.1 - news upgrades
1.0.1 - wrong table name on install was causing the field to not being properly
        created: solved
1.0.2 - formatter had php notice when rendering the field if it was empty: solved
1.0.3 - formatter now supports fields with multiple values

Commited to GitHub.com -- And verified.
