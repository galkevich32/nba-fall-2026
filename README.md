## The Inversion of the International NBA Pipeline 

This project analyzes international players in NBA from 1996-97 to 2026-27 seasons. Using Python and Pandas, the notebook processes roster data to find trends in the number of players coming to the league via NCAA versus directly from overseas. Additionally, the analysis looks into the historical data on the number of international players joining the league through draft versus undrafted players.

## Context

In 2021, by allowing athletes to profit from their personal brand (Name, Image, and Likeness, or NIL), giving transfers the freedom to play immediately, and removing barriers for overseas players with professional backgrounds, the NCAA fundamentally redefined college sports.

## Project Overview

The analysis processes primary datasets containing all the international players that saw action in each NBA season since 1996-97. We look for composition shifts and year-over-year changes:

* **College vs. Non-College Analysis:**

Evaluates player background by identifying whether a recorded `COLLEGE` entry is present versus missing (`NaN`), calculating seasonal counts/percentage shares

* **Draft Status Analysis:**

Evaluates player background by tracking drafted versus undrafted player seasonal counts/percentage shares

## Finding:

In 2021, the same year NIL was introduced, international players entering the league via the NCAA outnumbered those arriving directly from overseas—an inverted ratio that has since become the league's new standard. 

## Datasets Required

To run this notebook, ensure the following CSV files are in the same directory:

- `'202627.csv'`
- `'202526.csv'`
- `'202425.csv'`
- `'202324.csv'`
- `'202223.csv'`
- `'202122.csv'`
- `'202021.csv'`
- `'201920.csv'`
- `'201819.csv'`
- `'201718.csv'`
- `'201617.csv'`
- `'201516.csv'`
- `'201415.csv'`
- `'201314.csv'`
- `'201213.csv'`
- `'201112.csv'`
- `'201011.csv'`
- `'200910.csv'`
- `'200809.csv'`
- `'200708.csv'`
- `'200607.csv'`
- `'200506.csv'`
- `'200405.csv'`
- `'200304.csv'`
- `'200203.csv'`
- `'200102.csv'`
- `'200001.csv'`
- `'199900.csv'`
- `'199899.csv'`
- `'199798.csv'`
- `'199697.csv'`

*Note: The script also exports processed data into csv files for visualization tools like Datawrapper.

## Running the analysis yourself

You can run the analysis yourself. To do so, you'll need the following installed on your computer:

Python 3.11+
Pandas (Data manipulation, aggregation, and merging)

## Licensing

All code in this repository is available under the MIT License. The data file in the output/ directory is available under the Creative Commons Attribution 4.0 International (CC BY 4.0) license. All files in the data/ directory are released into the public domain.

## Feedback / Questions?

simon.galkevich36@journalism.cuny.edu
