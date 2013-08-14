taipeitravel-scraper
====================

`generate-map` is a script that scrapes the site http://www.taipeitravel.net/
and creates a map with a pin for each point of interest. The main purpose is to
get an overview of the distance between those locations. Open the generated
`index.html` in a browser to see the map.

As it is, the map shows the locations of hiking trails in Taipei. It should be
trivial to adapt the script to map other things (museums, temples, libraries
etc.).

If you use this, please remember that after all, it's a scraper. Be nice to the
site owner. The script doesn't generate much trafic, so it shouldn't be a
problem. There is also a one second delay for each URL, which should lighten
the load even further.
