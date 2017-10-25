# Task and Extension Install Guide

Simple guide that outlines how you can install tasks and extensions for ENVI. There are two different methods for installation depending on the software license that you have. This guide will talk about how to use each method.


## Installation Location

When installing extensions and tasks, there are two different locations that you can install them to. If you have administrator rights on your computer, then you will have access to ENVI's custom_code and extension folder. Using this directory will also install the tools for all other users of a computer.

If you don;t have administrator rights, then you can simply place the tasks and extensions in ENVI's user directories. This location does not require administrator rights, but the tasks and extensions installed here will not be aviable to other users.

Here is a link to the documentation for where to install tasks:

[http://www.harrisgeospatial.com/docs/deploytasks.html](http://www.harrisgeospatial.com/docs/deploytasks.html)

Here is a link and guide to the documentation how to write and deploy extensions:

[http://www.harrisgeospatial.com/docs/ToolboxExtensions.html](http://www.harrisgeospatial.com/docs/ToolboxExtensions.html)

Additionally, to view the folders where you can install without administrator rights you can also look at **File -> Preferences -> Directories** in ENVI.



## Installing Extensions

Here, when extension folder or custom code folder is referred to, you will need to pick a location from the section above that describes where tasks or extensions will be installed.

### ENVI + IDL License

If you have ENVI + IDL, then you can either:

1. Place the IDL code from a repository directly in ENVI's extension folder. This work's **ONLY** when you start ENVI + IDL at the same time so that ENVI can compile IDL code on the fly.

2. Build an IDL SAVE file and place that in ENVI's extension folder. This works with or without IDL, but you need a license to compile the code. To build the IDL SAVE file, there should be instructions on the main repository for how you can compile the code or a build script which will do that for you. Otherwise you can follow this generic help topic:

[http://www.harrisgeospatial.com/docs/ToolboxExtensions.html#Build](http://www.harrisgeospatial.com/docs/ToolboxExtensions.html#Build)


### Only ENVI License

If the repository does not contain an IDL SAVE file, you will need to have someone compile the code for you and then install in ENVI's extension folder. GitHub or other source control software is intended to store source code for the community to access, not necessarily precompiled code.


## Installing Tasks

Here, when extension folder or custom code folder is referred to, you will need to pick a location from the section above that describes where tasks or extensions will be installed.

### ENVI + IDL License

If you have ENVI + IDL, then you can either:

1. Place the IDL code and associated `.task` files from a repository directly in ENVI's custom code folder. This work's **ONLY** when you start ENVI + IDL at the same time so that ENVI can compile IDL code on the fly.

2. Build an IDL SAVE file and place that in ENVI's custom code folder. This works with or without IDL, but you need an IDL license to compile the code. To build the IDL SAVE file, there should be instructions on the main repository for how you can compile the code or a build script which will do that for you. Otherwise you can follow this generic help topic:

[http://www.harrisgeospatial.com/docs/ToolboxExtensions.html#Build](http://www.harrisgeospatial.com/docs/ToolboxExtensions.html#Build)


### Only ENVI License

If the repository does not contain an IDL SAVE file, you will need to have someone compile the code for you and then install the SAVE files and associated `.task` files in ENVI's extension folder. GitHub or other source control software is intended to store source code for the community to access, not necessarily precompiled code.
