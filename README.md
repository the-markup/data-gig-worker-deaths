# Gig Worker Deaths

This repository contains data from our story, "[More Than 50 U.S. Gig Workers Murdered on the Job in Five Years](https://themarkup.org/working-for-an-algorithm/2022/04/06/more-than-50-u-s-gig-workers-murdered-on-the-job-in-five-years)."


## Data

`data/gig-worker-deaths.csv` catalogs instances of gig workers being murdered on the job. This data was collected by the organization [Gig Workers Rising](https://gigworkersrising.org/), which used "publicly available information, including news reports, police documents, legal filings and family accounts obtained through searches of GoFundMe fundraisers, Google, Reddit, LexisNexis, and [The Markup’s database of carjackings of ride-hail drivers around the country](https://github.com/the-markup/investigation-gig-carjacking)." It was then verified by The Markup.

Data in the file is arranged as follows:

| Column    | Description |
|---------|-------------|
| **`City`** |    City where incident took place.
| **`State`**    | State where incident took place.
| **`Date`** |    Date incident took place.
| **`Year`** |    Year incident took place.
| **`Gig Corporation`** |    App that gig worker was using at time of incident.
| **`Worker name`** |    Name of the worker killed.
| **`Fundraiser`** |    Link to fundraiser for the worker, if available.
| **`Source 1`** |    Where information was gathered to confirm incident.
| **`Source 2`** |    Additional confirmation of the incident.
| **`Source 3`** |    Additional confirmation of the incident.
| **`Source 4`** |    Additional confirmation of the incident.
| **`Note`**| Further details about the incident.
