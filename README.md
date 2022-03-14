### A small data portfolio

This is a small collection of shareable data investigations and data wrangling
that I've done.

The first is `Council Districts.ipynb`, which was done as part of a push to get
ICE out of the NY State court system. In order to build political pressure, we
wanted to show city council members how many of their constituents were being
targeted by ICE. The investigation used Google Maps geocoder API to map client
addresses (lines 1-23), then `geopandas` and `shapely` to find how many clients lived in each
council member's district (lines 24-end). This investigation was one part of the most
mapping-heavy project I did while at New York County Defender Services.

The second is `MOCJ Monthly Reports.ipynb`. As a city-funded public defender,
our organization was required to submit monthly reports on case counts by charge
categories and intake type, as well as reporting on outflow type. We were also
required to report on post-disposition cases (ie a client coming in on a
probation violation). Initially, the report took several days to compile because
of how much cleaning and manual tabulation was required; this Python notebook
allowed us to automate most of the cleaning, letting us complete the report in a
fraction of the time.

The final file is `Survey Sample.ipynb`. This was done as part of an annual
survey of client experience. After pulling a sample frame in SQL ("Finding
eligible cases and people")\*, I check to make sure the sample is roughly similar
to the full population. The file shows how I approach learning new
datasets, as well as how I communicate findings to my audience.

\* You can see more about our sample frame [here](https://github.com/rcackerman/data-portfolio/blob/main/methodology.md)!
