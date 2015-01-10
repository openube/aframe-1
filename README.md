[![Build status](https://ci.appveyor.com/api/projects/status/2ti8tnlabd7782fg/branch/master)](https://ci.appveyor.com/project/Thwaitesy/aframe/branch/master)

Documentation
==========================================================================
[Please view the website (https://aframe.github.io)](https://aframe.github.io)

Changelog
==========================================================================
*0.5.4*
- Fix for Selenium StaleElementReferenceException. Will retry once if caught.

*0.5.0*
- Added 'AlwaysSearch' for all controls or just the individual ones. Should fix stale control issues.  

*0.4.26*
- Added launch overload for desktop to allow for System.Diagnostics.ProcessStartInfo 

*0.4.0*
- [BREAKING CHANGE] Changed name from MainFrame to AFrame.
- Added preliminary support for desktop automation (WPF, WIN FORMS)

*0.3.19*
- [BREAKING CHANGE] Changed MainFrame namespace from MainFrame to MainFrame.Core (NuGet package id has changed also - so please remove and reinstall nuget packages)
- Relocated files in project
- Added sample for MainFrame.Web using nuget's website

*0.2.0*
- Added support for iFrames.
- Refactored extensively.

*0.1.1*
- Updated Playback to include a properties / brain to hold information.
- Added absolute selector debugging 

*0.1.0*
- Added support for multiple selectors
- Added implicit search timeouts

*0.0.2*
- Added jQuery Selectors for web component

*0.0.1*
- Initial release

Contributors
==========================================================================
[Sam Thwaites](https://github.com/Thwaitesy)   

Licence
==========================================================================
See [LICENCE](https://github.com/Thwaitesy/AFrame/blob/master/LICENCE)

