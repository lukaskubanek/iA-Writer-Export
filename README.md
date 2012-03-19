# iA Writer Export

You like the elegance of the Latex output and the simplicity of the Markdown syntax?

You use the best Mac editor for writing and you wonder why there is no export to PDF functionality you really want to have?

Don't worry, here is a Mac service which adds this functionality to [iA Writer](http://www.iawriter.com/) using the amazing document format convertor library [Pandoc](http://johnmacfarlane.net/pandoc/).

## Installation

1. Download [iA Writer](http://itunes.apple.com/app/id439623248?mt=12) from the App Store.
2. Install Pandoc 1.9.x. Use a package installer listed on this [installation page](http://johnmacfarlane.net/pandoc/installing.html).
3. If you have not done it yet, install pdflatex or a whole Latex distribution (first check it out by writing ```which pdflatex``` into your Terminal). 
4. Move the service to ```~/Library/Services``` or use a simple install script (```./install```) which does the same for you.
5. Optionally you can set a shortcut for the export functionality. How to do this is described in the last section of [this article](http://www.makeuseof.com/tag/how-to-create-your-own-services-menus-mac/). 

## Tasks

- handling documents with special characters in their names (currently only a message is being shown)
- automatically save document when exporting
- support for other extensions