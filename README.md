# STAT-386-Data-Acquisition-Code

## scrape_script.py
This file contains the code used for scraping the Guilty Gear Strive and Guilty Gear Xrd Revelator 2 pages from the Dustloop wiki. It gathers the links for both games, scrapes the move data according to those links, fixes the move data for characters whose move data is displayed irregularly, and then writes all of that data to two separate .csv files in `\data`.

## analysis.ipynb
This file gathers the Strive and Xrd DataFrames from `scrape_script.py` and reformats all of the data into a single, large DataFrame. It then cleans the columns of the new DataFrame and runs some basic EDA on the information within it.