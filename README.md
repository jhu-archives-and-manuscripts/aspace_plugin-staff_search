# Staff Mode Search Plugin

## Summary

ArchivesSpace plugin to modify search display in staff mode 

## Configuration

Control display of the *context* (where found) and *audit information* (creation and last
modified information) through setting in *config/config.rb*. Setting a value to *false* turns
off the corresponding column. If settings below are the default, if a setting is not specified.

```ruby
AppConfig[:staff_mode_search] = {
    :show_audit_info_column => true,
    :show_context_column => true
}
```

## Activate the plugin
- Install the plugin:
  - Clone this repository into the *plugins/staff_mode_search* directory; or
  - Unzip the release zip into the *plugins/staff_mode_search* directory.

- Enable the plugin:
  - In *config/config.rb*, add the plugin name to the "AppConfig[:plugins]" list, e.g.:

    AppConfig[:plugins] = ['staff_mode_search']

- Restart ArchivesSpace
