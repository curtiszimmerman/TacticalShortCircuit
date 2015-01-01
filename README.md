# TacticalShortCircuit

A fork of the wonderful [StayPuft](https://github.com/dlecina/StayPuft) theme by David Lecina, which is fork of Casper, the default theme for [Ghost](https://github.com/tryghost/ghost/).

## Ghost Version

TSC (TacticalShortCircuit) tries to match Casper's version numbering system. That is, TSC version A.B.C should roughly have the same (or more) features as Casper version A.B.C. Features and bug fixes may be added between major versions, so the best way to stay updated is to clone and pull changes from the repo.

**The current TSC version is 0.0.1, and should work with Ghost 0.5.6, as well as some (but not all) older versions.**

If the current version of TSC is not compatible with the version of Ghost you're running, try looking for an older one in the [Releases section](https://github.com/curtiszimmerman/TacticalShortCircuit/releases).

## Features

* Responsive design.
* Post comments using [Disqus](http://disqus.com/).
* In-site search using [GhostHunter](https://github.com/i11ume/ghostHunter).
* Support for [Font Awesome](https://github.com/FortAwesome/Font-Awesome).
* Basic support for [slidr.js](https://github.com/bchanx/slidr).
* Syntax highlighting using [Prism](https://github.com/LeaVerou/prism/).
* [Google Analytics](http://www.google.com/analytics/).

## Demo

This theme is being used in my [blog](http://curtisz.com/).

*  ["Welcome to Ghost" post](http://curtisz.com/blog/welcome-to-ghost/).
*  [Prism demo](http://curtisz.com/blog/prism-demo/).

## Installation

* Clone this repository on your themes folder:

```
cd ghost/content/themes
sudo git clone https://github.com/curtiszimmerman/TacticalShortCircuit
```

* **[Configure](#configuration) the theme.**
* Restart Ghost.
* Select the theme in your Settings page.

## Configuration

* Replace `assets/favicon.png` with your own favicon, or remove for the default Ghost favicon.
* Modify `partials/disqus.hbs` with your shortname.
* Modify `partials/google-analytics.hbs` with your own snippet.
* Replace `partials/copyright.hbs` with your own disclaimer.
* Modify `partials/sidebar-external.hbs` with your own external links.
* After configuration, you may have to restart for all changes to take place.

## Copyright & License

Original Copyright (c) 2013-2014 Ghost Foundation - Released under The MIT License.  
Modifications Copyright (c) 2014 David Lecina Fuentes - Released under The MIT License.
More Modifications Copyright (c) 2015 Curtis Zimmerman - Released under The MIT License.

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND
NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
