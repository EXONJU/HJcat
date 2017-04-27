# HJcat

Hand picked hot Jupiter Catalogue compiled from

| Source | Comment |
|:------:|:-------:|
|[.eu](http://exoplanets.eu/)         |   Lots of planets under debate      |
|[.org](http://exoplanets.org)        |   Haven't been updated for a while...      |
|[.nasa](http://exoplanetarchive.ipac.caltech.edu/)       |    Not yet 100 percent perfect     |
|[.open](http://openexoplanetcatalogue.com/)        |   A bit similiar like .eu except for data structure     |

**0 < Per[days] <= 10** AND **0.3 < Planet Mass[M_Jup] <= 13**

While merging those catalogues, I have to eye-inspect one by one because these nasty things:

+ Other names for the same objects like
    - `K2-31 b` <-> `EPIC 204129699 b` (simbad solution?)
    - `NGC 2682` <-> `M67`
    - `Kepler-426` <-> `KOI-195`
+ Name format issues like
    - spaces, dashes in between words
    - numbers with zero ahead
    - capitals, binary flags `AB` or planet name without `bcd`
    - `hat-p-27-wasp-40_b` in .eu (what?)
    - acronyms like `Ups And b` <-> `Upsilon Andromedae b`
+ Planets paper not even published like [EPIC 220504338b](https://arxiv.org/abs/1611.07614)
+ Binaries that can only be found on .open like `HD 189733 A b`
+ `mu Ara c` with unpaired planet and infomation
+ `Kepler-548 b` mass measurement?
+ etc. :joy:

> mengzy1989[at]gmail.com
