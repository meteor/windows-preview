Issue tracker for Windows support
===============

Add an issue here if something you use doesn't work on Windows. See the [wiki page](https://github.com/meteor/meteor/wiki/Preview-of-Meteor-on-Windows) for more details.


Known issues for the preview 1
===

Installer issues:
---

Check out this issue for the discussion: https://github.com/meteor/windows-preview/issues/6

Common issues:
- The installer can crash if .Net Framework 3.5 is not present on your machine
- The installer will fail to copy the files if your user doesn't have permissions to create directories in your %HOME/AppData/Local directory:
  * try removing a `.meteor` directory left from a previous installation and try again
  * you might need to run the installer as an administrator
- If the installer still crashes, try running it in the compatibility mode
