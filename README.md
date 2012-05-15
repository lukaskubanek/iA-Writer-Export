# iA Writer Export

You like the elegance of the [Latex](http://www.latex-project.org/) output and the simplicity of the [Markdown](http://daringfireball.net/projects/markdown/) syntax?

You use the best Mac editor for writing and you wonder why there is no export to PDF functionality you really want to have?

Don't worry, here is a Mac service which adds this functionality to [iA Writer](http://www.iawriter.com/) using an amazing document format convertor library called [Pandoc](http://johnmacfarlane.net/pandoc/).

## Installation

1. Download [iA Writer](http://itunes.apple.com/app/id439623248?mt=12) from the App Store.
2. Install Pandoc 1.9.x using a package installer listed on the [installation page](http://johnmacfarlane.net/pandoc/installing.html).
3. If you have not ```pdflatex``` on your system, you have to install a [Latex distribution](http://www.tug.org/mactex) first (check it out by writing ```which pdflatex``` into your Terminal). 
4. Download [iA Writer Export service](https://github.com/kubanek-l/iA-Writer-Export/tags) and move it to ```~/Library/Services``` or use a simple install script (```./install```) which does the same for you.
5. Optionally you can set a shortcut for the export functionality. How to do this is described in the last section of [this article](http://www.makeuseof.com/tag/how-to-create-your-own-services-menus-mac/).

## Usage

Save your document first, it has to be saved before exporting. If you want to export the Markdown file to PDF, select ```iA Writer > Services > Export Markdown to PDF``` in the menu and wait until a new window with the exported PDF file appears. It will be saved in the same location as the Markdown file but with different extension.

Pandoc and iA Writer Export support more than iA Writer does. Check out the [Pandoc's Markdown](http://johnmacfarlane.net/pandoc/demo/example9/pandocs-markdown.html). Use links, source code highlighting, footnotes, images, tables, definitions, math equations, raw Latex, citations and more.

## Warranty

Please pay attention to the development status of this Mac service. There is absolutely no warranty on correct functionality.

## Contribution

The contribution is welcome! Feel free to create issues or pull requests at any time. Please keep in your mind that the project uses [Git Flow](http://nvie.com/posts/a-successful-git-branching-model/) and [Semantic Versioning](http://semver.org/) conventions.