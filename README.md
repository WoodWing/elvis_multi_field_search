# Elvis multi-field search plug-in

This simple Elvis plug-in opens a search dialog and let you search on a list of pre-configured metadata fields. The current implementation supports:

* Elvis (pro) web client and brand portal
* Searching text fields (not date, number, etc)
* Assets that match all given terms are shown in the results (AND query)

## Prerequisites

The integration requires:

* Fully installed and licensed Elvis server. You can obtain Elvis via: https://www.woodwing.com/en/digital-asset-management-system
* Elvis administrator knowledge

## Installation

* Read the instruction on installing Elvis plugins: https://helpcenter.woodwing.com/hc/en-us/articles/202965685-Plug-ins-introduction-management.
* Copy the contents of this folder to the Elvis Server plugins folder: `<Elvis Config>/plugins/active`.
* Open `action.config.xml` and configure the fields you want to search on using the searchFields property.

## Changelog

v1.1
* Bug fixes for various browsers

v1.0
* Initial implementation
* Search on a list of configured fields 