# Progressive Voter Index (PVI)
This repo includes data on PVI scores for San Francisco precincts, based on a Chronicle analysis done in December 2021.

The Progressive Voter Index estimates the progressivity of voters in each S.F. precinct based on how the electorate voted on recent local ballot measures. The metric was originally created by San Francisco State University Professor Emeritus Richard DeLeon in 1999 (and kept up-to-date by former political consultant David Latterman), but The Chronicle [updated it in 2021](https://www.sfchronicle.com/projects/2021/sf-progressive-voter-index/) using results from 14 local ballot measures from the 2018, 2019 and 2020 elections that cover fiscal, social, land use and governmental issues.

For details on the methodology, read our [story](https://www.sfchronicle.com/projects/2021/sf-progressive-voter-index/).

## Data dictionary
* `PREC_2019`: Precinct ID, based on the [2019 precinct map](https://sfelections.sfgov.org/sites/default/files/Documents/Maps/CitywidePctMap2019.pdf). Precinct boundaries are fairly consistent between elections and decennial censuses, but the Department of Elections sometimes add or combine precincts based on population changes.
* `NeighRep`: Neighborhood that the precinct is in. These neighborhoods are defined by the [Department of Elections](https://sfelections.sfgov.org/sites/default/files/Documents/Maps/NeighborhoodPctMap2019.pdf).
* `pvi`: PVI score for the precinct

## S.F. Chronicle stories using PVI
* [Critics claim S.F.'s proposed redistricting map favors moderates. Here's what the data shows](https://www.sfchronicle.com/sf/article/sf-redistricting-map-17076075.php)
* [How progressive is S.F.? This data shows clear divides emerge along racial and ethnic lines](https://www.sfchronicle.com/sf/article/How-do-the-politics-of-San-Francisco-differ-by-16738961.php)
* [This map shows which areas of San Francisco are most progressive](https://www.sfchronicle.com/projects/2021/sf-progressive-voter-index/)
