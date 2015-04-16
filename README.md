EarthSphere.jl
==============

A very simple Julia Library for measuring approximate distance and location given latitudes and longitudes


#Usage:
```
mylocation = Earth_LatLong_Coord(25,45,"SW")
#I am located on earth, latitude 25 degrees south, longitude 45 west

yourlocation = Earth_LatLong_Coord(65,10,"NE")
#You are located on Earth, latitude 65 degrees north, longitude 10 degrees east

distance = get_distance(mylocation,yourlocation)
```
# TODO:
- Refactor API, make names cleaner and clearer
- Allow choice of algorithm
