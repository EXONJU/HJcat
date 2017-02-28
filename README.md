# HJcat

Hand picked hot Jupiter Catalogue compiled from

| Source | Comment |
|:------:|:-------:|
|[.eu](http://exoplanets.eu/)         |   Lots of planets under debate      |
|[.org](http://exoplanets.org)        |   Haven't been updated for a while...      |
|[.nasa](http://exoplanetarchive.ipac.caltech.edu/)       |    Not yet 100 percent perfect     |
|[.open](http://openexoplanetcatalogue.com/)        |   A bit similiar like .eu except for data structure     |
 
While merging those catalogues, I have to eye-inspect one by one because these nasty things:
+ Other names for the same objects like
    1 `K2-31 b` <-> `EPIC 204129699 b` (simbad solution?)
    2 `NGC 2682` <-> `M67`
    3 `Kepler-426` <-> `KOI-195`
+ Name format issues like
    1 spaces, dashes in between words
    2 numbers with zero ahead
    3 capitals, binary flags `AB` or planet name without `bcd`
    4 `hat-p-27-wasp-40_b` in .eu (what?)
    5 acronyms like `Ups And b` <-> `Upsilon Andromedae b`
+ Planets paper not even published like (EPIC 220504338b)[https://arxiv.org/abs/1611.07614]
+ Binaries that can only be found on .open like `HD 189733 A b`
+ etc.

> mengzy1989[at]gmail.com
