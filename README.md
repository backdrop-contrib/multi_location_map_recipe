Multi Location Map Recipe
======================

This recipe creates a content type and view that can be used to place 
multiple points (location nodes) on a single map.

This recipe creates:

* A Location content type
* A Locations view that will display a map with all published locations on it
* A Map menu item in the main menu

Requirements
------------

Requires [BackdropCMS 1.20](https://github.com/backdrop/backdrop/releases/tag/1.20.0) or greater.

REQUIRED: The GeoCoder modules requires API keys to properly geocode
and display points on a map (admin/config/content/geocoder). 

See: https://simplo.site/posts/placing-multiple-locations-map-backdrop-cms 

This recipe module requires the following modules:

* Geofield
* Geocoder
* Addressfield

Installation
------------

- This recipe can be found in the Recipes package on the modules 
  page (admin/modules/list).

- Install this like any other module using the official Backdrop CMS 
  instructions at https://backdropcms.org/guide/modules.

- Disabling and uninstalling this module will not delete any of the 
  configuration that this module provides, but will disable any CSS
  files that came with the recipe.

Uninstall or Upgrate Options
----------------------------

It is not currently possible to uninstall or upgrade this recipe.
If you no longer wish to keep this functionality, you will need 
to remove the items added by the recipe manually.

Once installed, you can make any necessary changes yourself to
the included content types, fields or views.


Issues
------

Bugs and Feature requests should be reported in the Issue Queue:
https://github.com/backdrop-contrib/multi_location_map_recipe/issues.

Feedback
--------

We are experimenting with config recipes and welcome your feedback. Please,
let us know how this config recipe worked for you and how you think we 
could improve it for other users in the future. 
https://github.com/backdrop-contrib/multi_location_map_recipe/issues/1

Current Maintainers
-------------------

- [Tim Erickson](https://github.com/stpaultim).

Credits
-------

- Sponsored by [Simplo](https://www.simplo.site)

License
-------

This project is GPL v2 software. 
See the LICENSE.txt file in this directory for complete text.


