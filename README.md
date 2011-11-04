# jQuery Context Menu Plugin

This is a fork of the context menu plug-in by A Beautiful Site. More documentation can be found at the original site:

http://abeautifulsite.net/blog/2008/09/jquery-context-menu-plugin/

## Changes

- added a "buttons" option to the plugin constructor
  - specify an array of buttons which trigger the menu - options include "left", "middle", and "right"
  - default value (right-click only): ['right']
- namespaced events so that the plugin will not unbind existing events
