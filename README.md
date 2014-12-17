agency-regions
==============

This is a collection of data about how federal agencies divide their agency coverage geospatially.

The reason why this was created is because feederal agencies have different regional divisions and naming conventions. This is an attempt to codify these variations.

The ```region-maps``` folder will be populated with images of the regional maps. The ```region_maps.csv``` is file of basic info where that piece of information was acquired.

Initially, much of the work will be manually curation. After a little data is collected hopefully, patterns will become clear.

As this develops, this will be matched against the (usa.gov contacts api)[http://www.usa.gov/About/developer-resources/federal-agency-directory/] to normalize and narrow down what is missing.

#### Adding regional info to the repo

If you would like to help, please take a look at the issues to see if there are any to pick off or add regional maps manually by following these steps:

* Take screenshot of the map at the url
* Rename to use agency + sub-agency. Example "dot-faa.png" ... if no sub-agency, then just top level, ie "dot.png"
* Add them to the region-maps folder
* Add a line item to the csv that includes the source from where you got it.

(Please reach out if you have questions.)

