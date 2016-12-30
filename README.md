# PHP Directory Statistics
A PHP page to give you statistics about your code and files in a given directory.

## What's New
* TODO Finder
* No longer searches gzipped files
* Fixed a PHP end() bug

## Supported Statistics
* File size
* Number of lines

## Supported file types
* PHP
* JavaScript
* HTML
* CSS

## Recommended Changes for Your Use
* Update $excludeFiles and $excludeDir arrays
* Update $dir path
* Add or remove file types
* Set $showTODOs

## Optional Changes
* Change units for file sizes (see the getFileInfo function)
* Change colors for diagrams (change hex values in the CSS inside the style tag)
