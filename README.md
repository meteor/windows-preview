Issue tracker for Windows support
===============

Add an issue here if something you use doesn't work on Windows. See the [wiki page](https://github.com/meteor/meteor/wiki/Preview-of-Meteor-on-Windows) for more details.


Known issues for the preview 1
===

Installer issues:
---

Check out this issue for the discussion: https://github.com/meteor/windows-preview/issues/6

Common issues:
- .Net Framework 3.5 is not available on your machine, this is why the installer crashes
- Your user doesn't have permissions to create directories in your user's LocalAppData:
  * try removing a `.meteor` directory left from a previous installation and try again
  * you might need to run the installer as an administrator
- The installer will run only in a compitability mode

