Carrot
=====

Carrot is a lightweight-but-powerful programmer's editor running as a Chrome
Packaged App. Inspired by Sublime and built on top of the Ace editing
component, it offers:

-  Multiple cursors
-  Tabbed editing and retained files
-  Syntax highlighting and themes
-  Command palette/smart go to
-  Hackable, synchronized configuration files
-  Project files and folder view
-  Fast project-wide string search

More information, links to Carrot in the Chrome Web Store, and an
external package file are available at https://github.com/Dynamic-Build/Carrot/releases.
Documentation can be found at https://github.com/Dynamic-Build/Carrot/wiki.

You can also load Carrot from source code, either to hack around on or
to try the absolute bleeding edge. You'll need to have Node and NPM
installed first, then follow these steps:

0. Clone this repo to your local machine
1. Run ``npm install`` to get the development dependencies (Grunt, LESS,
   and some other packages)
2. Start ``grunt``, which will generate the CSS files from the LESS
   source
3. Visit ``chrome://extensions`` and enable Developer Mode.
4. Still on the extensions page, click the button marked "Load unpacked
   extension..." and select the directory containing Carrot's
   manifest.json.

If you use Carrot and would like to show your appreciation, please
consider donating to the `FSF's Fund to End Software
Patents <https://my.fsf.org/civicrm/contribute/transact?reset=1&id=17>`__.
