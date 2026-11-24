The Inversion of the International NBA Pipeline 

This project analyzes international players in NBA from 1996-97 to 2026-27 seasons. Using Python and Pandas, the notebook processes roster data to find trends in the number of players coming to the league via NCAA versus directly from overseas. Additionally, the analysis looks into the historical data on the number of international players joining the league through draft versus undrafted players.

Context

In 2021, by allowing athletes to profit from their personal brand (Name, Image, and Likeness, or NIL), giving transfers the freedom to play immediately, and removing barriers for overseas players with professional backgrounds, the NCAA fundamentally redefined college sports.

Project Overview

The analysis processes primary datasets containing all the international players that saw action in each NBA season since 1996-97. We look for composition shifts and year-over-year changes:

- College vs. Non-College Analysis:

Evaluates player background by identifying whether a recorded `COLLEGE` entry is present versus missing (`NaN`), calculating seasonal counts/percentage shares

- Draft Status Analysis:

Evaluates player background by tracking drafted versus undrafted player seasonal counts/percentage shares

Finding:

In 2021, the same year NIL was introduced, international players entering the league via the NCAA outnumbered those arriving directly from overseas—an inverted ratio that has since become the league's new standard. 

Datasets Required

To run this notebook, ensure the following CSV files are in the same directory:

*Note: The script also exports processed data into csv files for visualization tools like Datawrapper.

Running the analysis yourself

You can run the analysis yourself. To do so, you'll need the following installed on your computer:

Python 3.11+
Pandas (Data manipulation, aggregation, and merging)

Licensing

All code in this repository is available under the MIT License. The data file in the output/ directory is available under the Creative Commons Attribution 4.0 International (CC BY 4.0) license. All files in the data/ directory are released into the public domain.

Feedback / Questions?

simon.galkevich36@journalism.cuny.edu
