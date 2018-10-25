# Staff Mode Search Plugin

## Summary

ArchivesSpace plugin to modify search display in staff mode 

## Activate the plugin
- Install the plugin:
  - Clone this repository into the *plugins/staff_mode_search* directory; or
  - Unzip the release zip into the *plugins/staff_mode_search* directory.

- Enable the plugin:
  - In config/config.rb, add the plugin name to the "AppConfig[:plugins]" list, e.g.:

    AppConfig[:plugins] = ['staff_mode_search']

- Restart ArchivesSpace
