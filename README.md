![SUPERSMART](http://www.supersmart-project.org/images/logo200x480.png "SUPERSMART")

INFO
----
This is the source code repository of the Self-Updating Platform for the Estimation 
of Rates of Speciation, Migration, And Relationships of Taxa (SUPERSMART), a 
pipeline for estimating time-calibrated species trees from public data. Constantly 
updated information about the pipeline can be retrieved from the project website at 
www.supersmart-project.org.

INSTALLATION
------------
Installation depends on vagrant and Virtualbox, see INSTALL.md and the project website.

COMMANDS
--------
The functionality of the pipeline is exposed via the 'smrt' command located in app/.
The 'smrt' command offers twelve subcommands, representing each step of the pipeline. 

CONFIGURATION
-------------
Basic configuration is done via options passed to the 'smrt' command. 
Advanced configuration of the pipeline API is possible in the conf/supersmart.ini file.
The app/smrt-config command provides an interface for changing the configuration file.

EXAMPLES
--------
The examples/* directories contain instructional examples to demonstrate the input
file formats.

BUILD STATUS
------------
Currently, the build status at Travis is:

[![Build Status](https://travis-ci.org/naturalis/supersmart.svg?branch=master)](https://travis-ci.org/naturalis/supersmart)
