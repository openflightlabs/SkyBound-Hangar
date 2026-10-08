## v0.3.1:
- fixed an issue where files might have been renamed during install if it already existed in the Downloads folder
- new backup logic for installing overwriting additional downloads
- made logs much more informative
- separated additional downloads from the main download more
- simulators preferences for recently added addons are now saved across addons
- fixed issues with remove state of additional downloads
- fixed ui scaling introducing a gap at the bottom of the window
- fixed text extending beyond error message popups
- streamlined font colours across the app
 
## v0.3.0:
- recently updated now shows all simulators' addons (toggleable in settings)
- new popup asks which simulator's version should be opened if multiple addons have the same slug
- reorder simulators by dragging them around
- simulator detection moved from first run to source installation
- additional downloads' states made independent of main version's
- prevents  buzzheavier from downloading from popup ads
- fixes download expected size not working
- made download completion more reliable
- fixes buzzheavier downloads exiting prematurely
- fixes removing an addon not removing files not in in the download
- added option to have multiple uninstall directories
- made button states more reliable
- shift-clicking the install buttons opens location popup if more than one sim is found
- fixes the back button being broken if started via a skybound:// URL
- adjusted style for sources & simulators settings pages to feel more native to the app
- opening the updater no longer closes hangar
- fixed cmd window popping up when generating a download link
- added styles for horizontal rules

## v0.2.3:
- fixed "unsupported Zip archive" errors with password-protected archives
- fixed handling of multiple versions of addons
