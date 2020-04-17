# Covid_19_Choropleth_Canada

## Goal

Generate choropleths of the spread of Covid-19 in Canada as of 2020/04/16 for educational purposes. There is no intention of distribution.

This repository included the working jupyter notebook as well as .csv files: mortality data, infection data, relational data for health regions, source .shp files and associated records.

## Results

Data on infections and deaths per health region was sourced (in a precompiled state) from Github. These two sources were combined, along with census information on population per health region to calculate mortality and infection rates, and an index of health region names and ids.

Goverment of Canada .shp file was sourced for creation of Choropleths.

Data was cleaned/munged and cleanup of text was required to align source data for matching with .shp region ids.

Current maximum infection rate was found to be 3.4/1000 persons, with a death rate of .18/1000 persons. Both infections and deaths were found to be concentrated in metropolitan areas of Vancouver, Toronto, as well as widely throughout the province of Quebec. Minimal infections and deaths are found in the more sparsely populated areas of central and western Canada.

## Issues

Reporting of cases for the 3 health regions of the Fraser Valley area, as well as the 3 Vancouver Island regions are not seperated into distinct health regions but reported as a whole. Without inspecting individual cases it is difficult to report these areas accurately. These areas represent a nominal volume of cases compared to the whole of Canada.

## Acknowledgements

Data was sourced from https://github.com/ishaberry/Covid19Canada (accessed 2020/04/15)
  
## Update 2020/04/17

Feature addition: Pull most recent case data from Github source, generate new cleansed combined file, auto-save local datestamped copy. Generated choropleths from most recent data, auto-save local datestamped copies.
