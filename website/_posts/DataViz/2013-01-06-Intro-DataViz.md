---
title: "Introduction to the Data Visualization Tutorial"
layout: post.html
tags: [dataviz, file I/O, import, data structures, docstrings, iterators, generators, licensing, shell, packages]
url: "/dataviz/intro/"
---

Data visualization is quite fun. Perhaps when you think of data visualization, you think of ugly Microsoft Excel spreadsheets with half-a$$ed graphs.

This tutorial is meant to push you out of the Excel mindset just a little bit, and introduce you to the popular Python library, [matplotlib](http://matplotlib.org/). 

### The Project

The project we will create takes the sample data from the repository that you will download (a.k.a. clone) in [Part 0: Setup]( {{ get_url("Part-0-Setup-for-DataViz")}}), parse the sample data from columns and rows to a list of dictionaries, then render that data in two different graphs and in [GitHub](http://gist.github.com) as a map.

The sample data that is included is a snapshot of public crime filings from the San Francisco police. Once you’ve gone through this tutorial, feel free to find other data that interests you, and rework our visualization functions.

### Goals

Understand how to:

* run a Python file from the command line
* import a Python file
* take a raw file and parse its data with Python’s data structures
* make a simple graph
* produce a GeoJSON file for mapping

What else you will be exposed to:

* Importing Python’s standard library as well as your own module
* Installing and importing third party packages
* Licensing & copyrights when using third-party packages
* File Input/Output
* Counter data structure from the `collections` module
* Global variables, docstrings, list comprehensions
* Python’s interactive shell in the terminal
* Iterators versus Generators

### Intro to NumPy and matplotlib

[NumPy](http://www.numpy.org/) (pronounced num-pie) is a popular scientific library for Python that gives a developer, academic, or scientist tools to work with high-level mathematical functions as well as multi-dimensional arrays and matrices. 

We won't be using much of NumPy, but it is required that we install this library before we can install and use `matplotlib`.

[matplotlib](http://matplotlib.org/) is another popular scientific library that gives the developer tools to produce 2D figures. No longer do you need your [TI-89](http://www.amazon.com/Texas-Instruments-Titanium-Calculator-Packaging/dp/B0001EMLZ2) calculator where you must punch in long lines of formulas, waiting precious seconds for it to render a graph that may be too zoomed in to realize you are missing an important axis point. Packed with detailed [examples](http://matplotlib.org/examples/index.html), you are able to make publication/presentation-quality graphs from the comfort of your keyboard.

### Intro to GeoJSON

[GeoJSON](http://en.wikipedia.org/wiki/GeoJSON) is a derivative of [JSON](http://en.wikipedia.org/wiki/JSON), and very similar to [TopoJSON](http://en.wikipedia.org/wiki/Topojson).  It’s a data format for simple geological feature, including coordinate points.

We’ll be using a third-party module to help us in creating GeoJSON files: [`geojson`](https://pypi.python.org/pypi/geojson/1.0).  

[GitHub](https://github.com) has an awesome feature that allows folks to paste GeoJSON files into [Gists](https://gist.github.com), and it automatically renders as a map.

[Continue on to the Setup for DataViz &rarr;]( {{ get_url("dataviz/part-0")}})