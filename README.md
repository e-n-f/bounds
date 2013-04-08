bounds
======

Bounding boxes I have used for a lot of maps.

More for the sake of documentation than as a recommendation for what
anybody else should be doing.


The "flickr-picasa" files specify a series of 15-mile squares based on
clusters of photos separated by gaps of less than 200 feet.
These are the ones I used for the "Geotaggers' World Atlas" and
"Locals and Tourists" sets.

The "twitter" files, similarly, specify a series of 20-mile squares
based on clusters of tweets separated by gaps of less than 200 feet.
These are the ones I used for the "See Something or Say Something"
and "Paths Through…" sets and many other miscellaneous maps.

The place names in these files come from finding the smallest bounding
box in the "flickr-localities" file that contains the center of gravity
of the cluster.  That file, meanwhile, is simplified from
flickr_shapefiles_public_dataset_1.0.1.xml.gz, as released in
http://code.flickr.net/2009/05/21/flickr-shapefiles-public-dataset-10/

The "misc" files specify other areas that I have needed to make images
for for one reason or another.
