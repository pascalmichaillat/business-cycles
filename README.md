# Eleven Papers on Business Cycles

This repository contains lecture slides covering eleven papers on business cycles, with a focus on unemployment and stabilization policy. The papers covered are the following:

1. Do Matching Frictions Explain Unemployment? Not in Bad Times [(Michaillat 2012)](https://www.pascalmichaillat.org/1.html)
2. A Theory of Countercyclical Government Multiplier [(Michaillat 2014)](https://www.pascalmichaillat.org/2.html)
3. Aggregate Demand, Idle Time, and Unemployment [(Michaillat & Saez 2015)](https://www.pascalmichaillat.org/3.html)
4. A Macroeconomic Approach to Optimal Unemployment Insurance: Theory [(Landais, Michaillat, & Saez 2018)](https://www.pascalmichaillat.org/4.html)
5. A Macroeconomic Approach to Optimal Unemployment Insurance: Applications [(Landais, Michaillat, & Saez 2018)](https://www.pascalmichaillat.org/5.html)
6. Optimal Public Expenditure with Inefficient Unemployment [(Michaillat & Saez 2019)](https://www.pascalmichaillat.org/6.html)
7. Resolving New Keynesian Anomalies with Wealth in the Utility Function [(Michaillat & Saez 2021)](https://www.pascalmichaillat.org/11.html)
8. Pricing under Fairness Concerns [(Eyster, Madarasz, & Michaillat 2021)](https://www.pascalmichaillat.org/8.html)
9. Beveridgean Unemployment Gap [(Michaillat & Saez 2021)](https://www.pascalmichaillat.org/9.html)
10. An Economical Business-Cycle Model [(Michaillat & Saez 2022)](https://www.pascalmichaillat.org/7.html)
11. u* = √uv [(Michaillat & Saez 2022)](https://www.pascalmichaillat.org/13.html)

## Webpage

The lecture slides are posted at https://www.pascalmichaillat.org/t4.html.

## Overview and Bibliographic Information

An overview of the papers is presented in `overview.md`.

The bibliographic information for the papers is contained in the LaTeX bibiography file `bibliography.bib`.

## Folder Organization

The material is organized in ten folders, each associated with separate papers:

* `rationing` - lecture slides for "Do Matching Frictions Explain Unemployment? Not in Bad Times"
* `multiplier` - lecture slides for "A Theory of Countercyclical Government Multiplier"
* `ad` - lecture slides for "Aggregate Demand, Idle Time, and Unemployment"
* `ui` - lecture slides for "A Macroeconomic Approach to Optimal Unemployment Insurance: Theory" and "A Macroeconomic Approach to Optimal Unemployment Insurance: Applications"
* `stimulus` - lecture slides for "Optimal Public Expenditure with Inefficient Unemployment"
* `wunk` - lecture slides for "Resolving New Keynesian Anomalies with Wealth in the Utility Function"
* `fairness` - lecture slides for "Pricing under Fairness Concerns"
* `gap` - lecture slides for "Beveridgean Unemployment Gap"
* `economical` - lecture slides for "An Economical Business-Cycle Model"
* `squareroot` - lecture slides for "u* = √uv"

## Folder Content

Each folder contains both source files and PDF file for a deck of lecture slides. A folder `folder` contains six files:

* `folder.tex` - LaTeX file for the slide deck
* `folder.pdf` - PDF file for the slide deck, compiled from `folder.tex`
* `presentation.sty` - LaTeX style file for slides made with Beamer, used by `folder.tex`
* `math.sty` - LaTeX style file containing mathematical formatting and shortcuts, used by `folder.tex`
* `folder.key` - Keynote file containing all the graphics included in the slide deck
* `xfolder.pdf` - PDF version of `folder.key`, used by `folder.tex`

## Software

The lecture slides were produced on a Mac (macOS Monterey 12.2.1) with the MacTeX-2021 distribution. The LaTeX files should be compiled with pdfTeX. The graphics were produced with Keynote (version 11.2).

## Author

This material was developed by [Pascal Michaillat](https://www.pascalmichaillat.org), with help from [Emmanuel Saez](https://eml.berkeley.edu/~saez/), [Erik Eyster](https://econ.ucsb.edu/people/faculty/erik-eyster), [Camille Landais](https://www.lse.ac.uk/economics/people/faculty/camille-landais), and [Kristof Madarasz](https://www.lse.ac.uk/management/people/academic-staff/kmadarasz).

## License

The content of this repository is licensed under the terms of the Creative Commons Attribution 4.0 International License [(CC BY 4.0)](http://creativecommons.org/licenses/by/4.0/).
