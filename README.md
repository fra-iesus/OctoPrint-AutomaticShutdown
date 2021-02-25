# OctoPrint Automatic Shutdown

This OctoPrint plugin enables the system to be automatically shut down after a print is finished.

The user can enable automatic shutdown for each print by using a checkbox in the sidebar.  Additionally, the user can 
trigger a shutdown by using the "shutdown now" button.  This is useful for non-admin users, who do not have access to
the system menu.

![Sidebar](/docs/screenshot.png?raw=true)

## Setup

Install via the bundled [Plugin Manager](https://github.com/foosel/OctoPrint/wiki/Plugin:-Plugin-Manager) (not valid anymore: original plugin is abandoned and not compatible with Python 3)
or manually using this URL:

    https://github.com/fra-iesus/OctoPrint-AutomaticShutdown/archive/master.zip

## Configuration

In order for the plugin work, the systemShutdownCommand must be set within the settings.

This setting can be edited in OctoPrint "Settings/Server/Shutdown system".
