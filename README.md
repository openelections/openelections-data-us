[![Build Status](https://github.com/openelections/openelections-data-us/actions/workflows/data_tests.yml/badge.svg?branch=master)](https://github.com/openelections/openelections-data-us/actions/workflows/data_tests.yml?query=branch%3Amaster)

# openelections-data-us

This repository contains pre-processed election results for president from all states, so far for the 2016 general election only. Caveats and notes on specific types of files are below.

### County-level files

County-level files include results from every state except Alaska, which does not have county equivalents. The District of Columbia is included and is treated as a single "county" for the purposes of this file. For Connecticut, New Hampshire, Maine, Massachusetts, Rhode Island and Vermont, the results are at the town level instead of the county level. All results are from official certified results files published by the states and D.C. Wisconsin's 2016 results are from the state's post-election recount.

### Caveats

These files are collections of multiple states and as such they are not uniform in what they contain. Some states provide vote totals for each county and statewide, while others provide under votes and over votes. Some states provide write-in votes as a single bloc while others break them out by recipient. In addition, candidate and party names can differ across states for the same person or party, particularly for minor-party candidates. If you're going to do some sort of analysis or mapping of this data, you'll need to standardize the contents of the files first.  
