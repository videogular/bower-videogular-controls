CHANGELOG
================
## v0.4.1
* Fixed bug in vgScrubbarcurrenttime, it wasn't updating the current time.

## v0.4.0
* Added licenses in all files.
* Fixed some issues related to $apply in progress error.

## v0.3.2
* Now icons are setted as CSS classes.
* Added gitignore, package.json and Gruntfile.

## v0.3.1
* Added support for minification.
* Added minified version.
* Fixed controlbar rendering on init.
* Now all plugin HTML templates are embedded in JS files (easier to deploy with bower).

## v0.3.0
* No changes.

## v0.2.0
* Support for full screen on devices without native full screen.
* Removed `$rootScope` dependencies.
* Added `vgComplete`, `vgUpdateVolume`, `vgUpdateTime`, `vgUpdateSize`, `vgUpdateState` and `vgPlayerReady` callbacks.
* Exposed API with name **"API"** instead of **"vg"**.
* Fixed problems with stretch mode.
* Improved code quality in link functions.
* Added **this** changelog.
