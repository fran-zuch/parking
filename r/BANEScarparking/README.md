# BANEScarparking

Datasets of parking records from 8 car parks located in Bath, United Kingdom; datasets of potentially relevant information for predicting car park occupancy; and functions for obtaining and working with these datasets.

Data is open-source and is provided by Bath and North East Somerset Council in collaboration with Bath: Hacked.


## Package contents

### Data:

* All parking records from 2014-10-17 to 2016-12-27
* Parking records by month from 2014-10 to 2016-12
* Parking records by car park

* Daily weather summary from 2014-10-17 to 2016-12-27
* Dates and kick-off times for Bath Rugby home matches from 2014-09 to 2016-12
* Daily count of events advertised at [www.bath.co.uk/events] from 2014-10 to 2016-12

### Functions:

* `get_all_crude` (and `get_range_crude`) for retrieving the full dataset (or a subset) of records from Bath: Hacked datastore
* `refine` for processing the raw records
* `refuel` and `refuel_crude` for updating existing data frames with recent records
* `get_rugby` and `get_events` for obtaining information through web-scraping


## Installation

To install the package just run this command in the R console:
```
devtools::install_github("owenjonesuob/BANEScarparking")
```
(You'll need the `devtools` package to do this - you can install it with `install.packages("devtools")`!)

Then you can load the package with
```
library(BANEScarparking)
```
and you should be good to go!


**Version:** 0.1.2

**Contact:** Owen Jones (olj23@bath.ac.uk)
