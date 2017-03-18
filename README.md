# MD5 Hasher (Alfred workflow)

[![Version](https://img.shields.io/badge/Version-1.0.1-green.svg)](https://github.com/nrozic/Alfred-md5-hasher-workflow)

This is simple Alfred 2 workflow for generating .htpasswd string, or simply to generate md5 hash from given string

# Installation

Detailed instructions on how to import and setup workflow can be found [here](http://blog.alfredapp.com/2014/04/02/tutorial-importing-and-setting-up-alfred-workflows/), but basicaly open up Alfred, go to settings and all you need to is drag&drop workflow file into Alfred

# How to use it

## Generating MD5 hashed string:

* Activate alfred (for me this is cmd+space)
* Enter **md5** keyword
* Enter desired string
* Done, alfred will copy md5 into your clipboard and try to paste it for you

## .Htpasswd generator:

If you need to password protect part of your web site using .htaccess, chances are that you will need this generator (Cpanel users have builtin GUI for this :) )

Sure, there are online generators that can solve this, but there is more elegant way - Alfred :)

To generate user that will have access to protected folder, you will need to define user and password in following format **user:password** and that is exactly what we will generate with this workflow

* Activate alfred (again, for me this is cmd+space)
* Enter **htpass** keyword
* Enter desired username and password **separated with space** and hit enter
* Done, alfred will copy md5 into your clipboard and try to paste it for you

Here is YouTube link to [see it in action](https://youtu.be/aNlTIbmhKpM)

## Changelog

* **Version 1.0**

 MD5 Hasher is born :)

* **Version 1.0.1**
 
 Fixed encryption bug that caused password mismatch while generating .htpasswd username:password string

## Final words
If you have any suggestions on how to improve this workflow, or you have suggestions for new workflows, drop me a line on info [at] trilium.io, or you can follow me on [twitter](https://twitter.com/nikolarozic)
