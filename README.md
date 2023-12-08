## Purpose

The aim of this part of the course project is the exploration and analysis of the database. 
Goal of the analysis is to understand how factors can be defined and assessed. 
We plan to identify the most important factors to then implement them in our simulations.

## Outcome

Result of this research contributes to the general course project report as well as laying foundation to the implementation of features and factors used in the simulations developed as a part of the course project.

# CDB90

This repository contains [Alvaro Radigales's version](https://github.com/doolanshire/CDB90) of the CDB90 Land Battle Database in CSV format, along with the original dataset created in the 1984 USACAA study *Analysis of Factors That Have Influenced Outcomes of Battles and Wars: A Data Base of Battles and Engagements*.

CSV files are compiled into a single SQLite database for ease of use. Also PDF scans for all six volumes of the original USACAA study are gathered.

## Files

* **data**: directory containing the CSV files, as cleaned up by jrnold.
* **src-data**: the original dataset also as presented by jrnold.
* **CDB90.db**: a unified SQLite database compiled by me from the CSV files, with the correct data type affinities assigned for each column. Keep in mind that in SQLite datetime is stored as string, and boolean as integer (0, 1).
* **originalpub**: the scanned PDF files for all six volumes of the USACAA study, describing the database and the conclusions of the initial analysis.

## License

The data in the *data* directory is released under the [odc-by](https://opendatacommons.org/licenses/by/) license as in the original release by [jrnold](https://github.com/jrnold/CDB90).

The SQLite database made by [doolanshire](https://github.com/doolanshire/CDB90) and is similarly released under the [odc-by](https://opendatacommons.org/licenses/by/) license.

The original CDB90 data in *src-data/M000121* is Public Domain.

Any programs and scripts are [MIT license](https://opensource.org/licenses/MIT) unless stated otherwise.
