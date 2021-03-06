
Credits
=======

The application and category icons originate from the Moka icon theme:
	* Link: https://github.com/moka-project/moka-icon-theme
	* Author: Sam Hewitt <hewittsamuel@gmail.com>
	* License: Creative Commons Attribution-ShareAlike 4.0 (https://creativecommons.org/licenses/by-sa/4.0)

The folder icons originate from the Arc icon theme:
	* Link: https://github.com/horst3180/arc-icon-theme
	* Author: horst3180 http://horst3180.deviantart.com

License
=======

This theme is licensed under Creative Commons Attribution-ShareAlike 4.0 (https://creativecommons.org/licenses/by-sa/4.0).

Any bundled software is free software; you can redistribute it and/or modify it under the terms of the GNU General Public License as published by the Free Software Foundation; either version 3, or (at your option) any later version.

Useful commands
===============

To find circular symbolic links:

	find . -follow -printf ""

To find broken links use `./deadlinks` or:

	find -L usr/ -type l

To find files with spaces in their filenames (that breaks the icon cache generation):

	find . | egrep '. '
