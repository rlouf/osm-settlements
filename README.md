# OSM Locations

Parse the OSM planet.osm to get a list of cities with their coordinates.

## Dependencies

* Python 2.7
* lxml

## Use

Open your console, go to the directory where you cloned the repository and type

```
make 
```

This will download the current planet.osm file, parse it to find all nodes
marked as a city, a town or a village and their coordinates, and save as a csv
file.

Once the data extracted and **transfered to another folder** type 

```
make clean
``` 

to delete **all** data (goes back to the initial state).

## How long does it take?

Testing, will let you know as soon as it is done parsing :) 

## License and author

Author: Rémi Louf <remi.louf@sciti.es>  
Website: www.sciti.es  
License: GPL v2
