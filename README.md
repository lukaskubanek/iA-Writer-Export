# iA Writer Export

## Discontinuation Notice

The **iA Writer Export** service is no longer being actively developed because I switched from [iA Writer][1] to [Ulysses III][2], which is really the best [Markdown][3] editor for Mac OS X. **Ulysses** does support PDF export but not (yet) using [Latex][4]. I might need that functionality later this year and in that case I would develop another Mac service for **Ulysses**.

Please note that the development of this service was not finished and you may encounter several errors when using it.

If you are a developer, you like this project and you'd like to become a maintainer of this repository, feel free to contact me.

## What is it?

The **iA Writer Export** is a Mac service which allows exporting Markdown files written in [iA Writer][5] to Latex PDF documents using a great document format convertor library called [Pandoc][6].

## Installation

1. Install Pandoc (version `>1.9`) using a package installer listed on the [Pandoc's installation page][7].
2. Install a [Latex distribution][8] if you haven't `pdflatex` installed yet. You can check it out by writing `which pdflatex` into your Terminal.
3. Download this [iA Writer Export service][9] and move it to `~/Library/Services`.
4. Optionally you can set a shortcut for the export menu item. How to do this is described in the last section of [this article][10].

## Usage

![][image-1] 

Your Markdown file has to be saved on your hard drive before exporting. For exporting to PDF select `iA Writer > Services > Export Markdown to PDF` in the menu (see the screenshot above) and wait until a new Preview window with the exported PDF file appears. It will be saved in the same location as the Markdown file with different file extension (`.pdf`). This is also the case for iCloud documents which is a little inconvenient.

Pandoc and **iA Writer Export** support more than iA Writer does. Check out the [Pandoc's Markdown][11]. Use links, source code highlighting, footnotes, images, tables, definitions, math equations, raw Latex, citations and more.

[1]:	http://www.iawriter.com/
[2]:	http://www.ulyssesapp.com
[3]:	http://daringfireball.net/projects/markdown/
[4]:	http://latex-project.org
[5]:	http://www.iawriter.com/
[6]:	http://johnmacfarlane.net/pandoc/
[7]:	https://code.google.com/p/pandoc/downloads/list
[8]:	http://www.tug.org/mactex
[9]:	https://github.com/lukaskubanek/iA-Writer-Export/archive/master.zip
[10]:	http://www.makeuseof.com/tag/how-to-create-your-own-services-menus-mac/
[11]:	http://johnmacfarlane.net/pandoc/demo/example9/pandocs-markdown.html

[image-1]:	Screenshot.png