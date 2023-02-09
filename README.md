# firefox-compact-ui
Bring back simple, compact UI to the latest versions of the Firefox browser!

# How to use

Clone this repository and copy the files from `chrome` directory to your firefox profile `chrome` directory.
Go to `about:config` page in firefox, accept warning message if it appears for you. Enter the following text in the search field: `toolkit.legacyUserProfileCustomizations.stylesheets`. Set this option to `true` and restart the browser.

# Development

## How to enable remote debugging
Open Inspector, go to the settings and enable:
1. Enable browser chrome and add-on debugging toolboxes
2. Enable remote debugging

Restart firefox.

## How to inspect UI elements

Use the combination SHIFT+CTRL+ALT+I to open remote debugging window. From this windows you will be able to inspect UI elements.