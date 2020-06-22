This is a collection of administrative boundaries for all NRC country field operations. Each country has varying levels of administrative boundaries. 

This was compiled from various sources including: [GADM](https://gadm.org), [GeoBoundaries](https://www.geoboundaries.org/), and [UN sources](https://data.humdata.org/).<sup>1</sup>

 Administrative boundaries are organized by:
 * NRC Region
 * Country (ISO 3166 Alpha 3)
 * Levels of granularity (i.e ADM 0-4)
 * Data formats (.geojson, .shp, .csv)

> <sup>1</sup> The main source of data is from Runfola, D., Seitz, L., Hobbs, L., Panginaban, J., Oberman, R. et al. geoBoundaries Global Administrative Database. http://www.geoboundaries.org.

# How the data is organized

The collection uses the following folder structure:

- [RO-NAME]
    - [3-LETTER-ISO-CODE]
        - [ADM-LEVEL]
            - [FILE-FORMAT]

# Region

Under the `Region` folder, a .geojson file can be found for each NRC region. These are made up of a series of country boundaries (ADM0) that were appended together for easy visualization purposes.