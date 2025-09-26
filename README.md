# drinking-water
Locations of Drinking Water


# query
```
area
  [place=county]
  ["wikidata"="Q188376"]
  ["name"="Hamilton County"]->.a;

nwr["amenity"="drinking_water"](area.a);

out geom;
```
