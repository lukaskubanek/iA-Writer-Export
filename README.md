# iA Writer Export

## Discontinuation Notice

The **iA Writer Export** service is no longer being actively developed because I switched from [iA Writer][http://www.iawriter.com/] to [Ulysses III][http://www.ulyssesapp.com], which is really the best [Markdown][http://daringfireball.net/projects/markdown/] editor for Mac OS X. **Ulysses** does support PDF export but not (yet) using [Latex][http://latex-project.org]. I might need that functionality later this year and in that case I would develop another Mac service for **Ulysses**.

Please note that the development of this service was not finished and you may encounter several errors when using it.

If you are a developer, you like this project and you'd like to become a maintainer of this repository, feel free to contact me.

## What is it?

The **iA Writer Export** is a Mac service which allows exporting Markdown files written in [iA Writer][http://www.iawriter.com/] to Latex PDF documents using a great document format convertor library called [Pandoc][http://johnmacfarlane.net/pandoc/].

## Installation

1. Install Pandoc (version `>1.9`) using a package installer listed on the [Pandoc's installation page][https://code.google.com/p/pandoc/downloads/list].
2. Install a [Latex distribution][http://www.tug.org/mactex] if you haven't `pdflatex` installed yet. You can check it out by writing `which pdflatex` into your Terminal.
3. Download this [iA Writer Export service][https://github.com/lukaskubanek/iA-Writer-Export/archive/master.zip] and move it to `~/Library/Services`.
4. Optionally you can set a shortcut for the export menu item. How to do this is described in the last section of [this article][http://www.makeuseof.com/tag/how-to-create-your-own-services-menus-mac/].

## Usage

![](/Screenshot.png)

Your Markdown file has to be saved on your hard drive before exporting. For exporting to PDF select `iA Writer > Services > Export Markdown to PDF` in the menu (see the screenshot above) and wait until a new Preview window with the exported PDF file appears. It will be saved in the same location as the Markdown file with different file extension (`.pdf`). This is also the case for iCloud documents which is a little inconvenient.

Pandoc and **iA Writer Export** support more than iA Writer does. Check out the [Pandoc's Markdown][http://johnmacfarlane.net/pandoc/demo/example9/pandocs-markdown.html]. Use links, source code highlighting, footnotes, images, tables, definitions, math equations, raw Latex, citations and more.