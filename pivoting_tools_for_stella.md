Building a User Interface for Business analytics tool over Stella 
we are exploring some of the good pivoting tools for data analysis:

###Terminology (borrowed from crossfilters):
- Dimensions - A key in a your data row.
- Measure    - Count, Sum, Uniuq Values List, Percentage, Ratios
- Group      - A logical grouping of data, serves as fields on rows
- Filter     - Restricting the universe of data for groups

###Libraries
- Cross-Filters and DC.js -  beautiful co-ordinated named charts, change filter in any of the charts and see changes reflected over others.
- pivot ui -  jQuery UI plugin, fast with smaller datasets, filtering values not supported.
- Orb.js   -  Better looking than pivot-ui but lesser inbuilt charting feaures, good filtering support.
- druid    -  Backend and frontend, more scalable for handling than larger data-sets, more like an add on over your cached datasets.

Bit Twiddling hack needs:
Done in cross filters for building indexes over dimensions, good discussion is on stack-overflow. We are more inclides towards moving this to backend as a add on for Stella.

--todo: add links.
