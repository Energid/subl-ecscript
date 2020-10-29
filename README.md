EcScript Highlighting for Sublime Text
======================================

If you are an Actin EcScript user who uses Sublime Text for editing scripts, 
then this plugin is for you.

It provides nice syntax coloring and indenting for EcScript files, and also
registers the .ecs and .ecscript file extensions so Sublime can autodetect
your scripts.

Installation
------------

If not already present, install [Package Control](https://packagecontrol.io/installation)
for Sublime Text. Open the packages folder using the "Preferences ==> Browse Packages..."
menu in Sublime. Within the window that appears, enter the "User" folder. Copy the
"ecscript.sublime-syntax" file from your cloned copy of this repository here.
Verify there is now an "EcScript" menu item under the "View ==> Syntax" menu in Sublime.

Comments and Suggestions
------------------------

Please follow, fork or submit issues on [GitHub][1].

License
-------

    MIT License

    Copyright (c) 2020 Energid Technologies

    Permission is hereby granted, free of charge, to any person obtaining a copy
    of this software and associated documentation files (the "Software"), to deal
    in the Software without restriction, including without limitation the rights
    to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
    copies of the Software, and to permit persons to whom the Software is
    furnished to do so, subject to the following conditions:

    The above copyright notice and this permission notice shall be included in all
    copies or substantial portions of the Software.

    THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
    IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
    FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
    AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
    LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
    OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
    SOFTWARE.

Version History
---------------

* v2.1 (2020-10-29) Added highlighting for `INF`, `BORDER`, `CNA` tokens and 'g', 'kg' units.
* v2.0 (2020-10-06) Updated syntax for Actin 6.0 release.
* v1.1 (2020-04-30) Deprecated `pose_seq` and `interp_pos_seq` commands.
* v1.0 (2020-04-08) Initial release

[1]: https://github.com/Energid/subl-ecscript
