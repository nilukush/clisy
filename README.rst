======
clisy
======

A command line utility to open browser for when you want to search something across various search options

Description
============

This is a simple utility to open browser from command line when you want to search something from various search options. Currently, it supports DuckDuckGo. But quickly, will plan to add the following options as well :

* DuckDuckGo ("ddg")
* GOOGLE ("g")
* WIKIPEDIA ("w")
* WIRECUTTER ("wc")
* AMAZON ("a")
* CREATIVE_COMMONS ("cc")
* IMDB ("imdb")
* SWIGGY ("sw")

Installation
=============
Run the following command to install clisy
::

    pip install clisy

Once ``clisy`` is installed, you get a command line utility called ``clisycp``.

Usage
=====
It is simple command line utility. To see the usage, you can type the following
::

    clisycp -h

Alternatively, here is the usage from version ``0.0.3`` so far
::

    usage: clisycp [-h]
               [--ddg <query_string> | -g <query_string> | -w <query_string> | --wc <query_string> | -a <query_string> | --cci <query_string> | --imdb <query_string> | --sw <query_string>]
               [-v] [-vv]

    CLI Search

    optional arguments:
      -h, --help            show this help message and exit
      --ddg <query_string>, --duck-duck-go <query_string>
                            Search in DuckDuckGo
      -g <query_string>, --google <query_string>
                            Search in Google
      -w <query_string>, --wikipedia <query_string>
                            Search in Wikipedia
      --wc <query_string>, --wirecutter <query_string>
                            Search in Wirecutter
      -a <query_string>, --amazon <query_string>
                            Search in Amazon
      --cci <query_string>, --creative-commons-image <query_string>
                            Image Search in Creative Commons
      --imdb <query_string>
                            Search in IMDb
      --sw <query_string>, --swiggy <query_string>
                            Search in Swiggy
      -v, --verbose         set loglevel to INFO
      -vv, --very-verbose   set loglevel to DEBUG

.. _pyscaffold-notes:

Note
====

This project has been set up using PyScaffold 4.0.2. For details and usage
information on PyScaffold see https://pyscaffold.org/.
