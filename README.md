# CIRGmd Template

### Purpose

This repository contains an example of how the [CIRG MSc dissertation template](http://cirg.cs.up.ac.za/visitPage.php?pageID=1706) can be integrated with R and RStudio so that R code outputs can be included inline into the dissertation. Furthermore, the chapters in the dissertation can be written in markdown which is somewhat less verbose than LaTeX and is supported by a range of editors and IDEs. The third benefit is that in RStudio this template will compile on either Windows, Linux, or (I am assuming) Mac OSX.


Currently the features in the LaTeX version which aren't in the Rmd version are:

* The bold blocks for naming supervisors (TODO fix) and
* Line spacing is slightly off for some reason (TODO fix).
* RefManageR numeric reference links are not working (TODO fix).

### Details

The main file is /MSc/MSc.Rmd. This file contains the preamble which will allow you to load any LaTeX packages you want to use in your thesis. This also allows you to specify a few things about the document including:

* Where the bibliograph (bibtex file) is located.
* Link and URL colours, font sizes, line spacing, etc.
* The LaTeX document class and document geometry. 
* Whether or not to keep the compiled .tex, and
* Other stuff. HTML output is not working (yet).

References in this template are managed by a package called RefManageR, please install this. Multiple types of references are supported for more information please consult RefManageR's help documentation.