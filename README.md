<link rel="stylesheet" href="markdown.css">

## A collection of licenses

This is a repository with all kinds of original and modified licenses.

### File Structure

`.gitignore`: ignores the sass cache in `themes/`
`README.md`: this file
`build.py`: Automatically generates all files in `page/` and index files from the templates in `templates/`.  
`markdown.css`: Stylesheet for this file. ([Air](http://markdowncss.github.io/air/)) (Not shown in GitHub)  
`meta.ini`: Contains metadata about the licenses (used by `build.py`)  

`html/`: contains HTML files for the licenses (These aren't full pages they're just a \<small> element)
`html/`: contains HTML documents for the licenses (These are full pages they're a \<html> element)
`templates/`: contains templates ([PEP 292](https://www.python.org/dev/peps/pep-0292/)) used by `build.py`
`themes/`: contains stylesheets that are automatically included in every *page* but it can also manually applied to *html*.
`txt/`: contains the licenses in textual representation