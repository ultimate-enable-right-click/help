[Homepage](https://ultimate-enable-right-click.github.io)
[한국어](./patch-notes-ko.md)

# Patch Notes 

2.2.8
 - Resolved CloudFlare captcha error.
 - Now the Chrome, Edge, and Whale extensions use Manifest 3.

2.2.7
 - Now it prevents websites from blocking paste. Certain websites block users from pasting text in a user's clipboard to websites' forms, and the extension will now block it.

2.2.5
 - Resolved conflict of extension UI with browser's built-in dark mode.
 - Now properly supports Whale browser's dual tab mode.

2.2.0
 - Added dark mode support for the extension's popup and settings page.

2.1.0
 - Now CSS module can neutralize text selection prevention using `pointer-events` CSS property.

🎉2.0.0
 - Visit the newly added ✨dashboard✨ to view all the settings you have saved at a glance. Click on the gear icon in the extension's popup to open the dashboard.
 - Now a setting for a domain is applied to all of its subdomains. For example, a setting for google.com will now be applied to www.google.com.

1.3.0
 - Now it prevents browser window/tab from being closed while users are right-clicking, selecting text, or dragging objects.

1.2.5
 - Popup UI: Now you can click on the slider bar instead of dragging the slider knob to modify running/stopped state of the extension.

1.2.0
 1. Now it prevents websites from blocking copy & cut functions.
   1) On certain websites, when a user copies selected contents from context menus or by pressing Ctrl+C, nothing is actually copied, an alert window is shown, or some modification is applied to copied contents. Now we prevent such behaviors.
   2) Currently it is under the "Enable right click". To disable it, click on the app's icon and move the slider under the "Enable right click" to the left.

1.1.5
 - Several popup UI improvements.
   - Addressed a frequent user report that slider knobs in the popup UI are hard to discern.
 - Launched a Firefox version of the app. It is available for installation in the app's homepage.

1.1.1
 - Updated CSS module to set pointer-events CSS properties. Removed a selector which caused a bug of Chrome.

1.1.0
 - Now it suppresses alert windows while users are right-clicking, selecting text, or dragging objects.

1.0.2
 - Resolved compatibility issues with older versions of Chrome.
