# Elvis DAM multi-field search plug-in

This simple Elvis plug-in opens a search dialog and let you search on a list of pre-configured metadata fields. The current implementation supports:

* The Elvis DAM Pro client and Brand portal
* Searching text fields (not date, number, etc)
* Assets that match all given terms are shown in the results (AND query)

![multi-field search plugin in action](https://github.com/WoodWing/elvis_multi_field_search/blob/master/multi-field-search.gif "multi-field search plugin in action")

## Prerequisites

The integration requires:

* Fully installed and licensed [Elvis DAM server](https://www.woodwing.com/en/digital-asset-management-system). 
* Elvis administrator knowledge

## Installation

* Read the [instruction](https://helpcenter.woodwing.com/hc/en-us/articles/202965685-Plug-ins-introduction-management) on installing Elvis plugins.
* Copy the contents of this folder to the Elvis Server plugins folder: `<Elvis Config>/plugins/active`.
* Open `action.config.xml` and configure the fields you want to search on in the searchFields property.

## Changelog

v1.1
* Bug fixes for various browsers

v1.0
* Initial implementation
* Search on a list of configured fields 