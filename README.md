# stg-chrome-extension

Various enchancements for the timesheet page for STG consultants.
* Various usability improvements
* Prevents user from being auto-logged out after timeout

## Install Steps
1. Click 'clone or download', and select 'download zip'.
0. Extract the zip file.
0. In Google Chrome, select 'More Tools', then 'Extensions' from the menu in the upper-right.
0. Make sure the 'Developer mode' option is checked.
0. Click 'LOAD UNPACKED' and then select the folder you extracted.

It will work automatically any time it detects the 'stgconsulting.force' url.
Because I didn't go through the Chrome store you will see a message saying to disable extensions in developer mode whenever you start chrome. Click cancel to ignore it or the extension won't run.

In order to allow the extension to continue to keep you logged in you have to select 'always allow popups' from the timesheet page if it gets blocked. You may occasionally see a window pop open and then immediately close. This window is the page asking if you would like to continue your session. The extension will click to continue automatically and then the window closes.
