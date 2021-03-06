## ApiGen 2.4.0 ##

* TokenReflection library updated to version 1.0.0
* Fixed support for older PHP versions of the 5.3 branch
* Option ```templateConfig``` is relative to the config file (was relative to cwd)

## ApiGen 2.3.0 ##

* Added support for default configuration file
* Added link to download documentation as ZIP archive
* Added option ```--charset``` and autodetection of charsets
* Added support for @ignore annotation
* Added PHAR support
* Added support for ClassName[]
* Added memory usage reporting in progressbar
* Improved templates for small screens
* Changed option name ```--undocumented``` to ```--report```
* FSHL library updated to version 2.0.1

## ApiGen 2.2.1 ##

* Fixed processing of magic constants
* Fixed resize.png
* TokenReflection library updated to version 1.0.0RC2

## ApiGen 2.2.0 ##

* Added an option to check for updates
* Added an option to initially display elements in alphabetical order
* Added an option to generate the robots.txt file
* Added required extensions check
* Changed reporting of undocumented elements to the checkstyle format
* Improved deprecated elements highlighting
* Highlighting the linked source code line
* Unknown annotations are sorted alphabetically
* Fixed class parameter description parsing
* Fixed command line options parsing
* Fixed include path setting of the GitHub version
* Fixed frames template

## ApiGen 2.1.0 ##

* Experimental support of PHP 5.4 traits
* Added option ```--colors```
* Added template with frames
* Added templates option to make element details expanded by default

## ApiGen 2.0.3 ##

* @param, @return and @throw annotations are inherited

## ApiGen 2.0.2 ##

* Fixed inherited methods listing
* Interfaces are not labeled "Abstract interface"
* Fixed Google CSE ID validation
* Fixed filtering by ```--exclude``` and ```--skip-doc-path```
* Fixed exception output when using ```--debug```

## ApiGen 2.0.1 ##

* Updated TokenReflection library to 1.0.0beta5
* Requires FSHL 2.0.0RC
* Fixed url in footer
