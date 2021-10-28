## Reformatted GOTPO 30 - Topography of the World

The GTOPO30 Dataset is a global topography maintained by the [USGS](https://www.usgs.gov/centers/eros/science/usgs-eros-archive-digital-elevation-global-30-arc-second-elevation-gtopo30?qt-science_center_objects=0#qt-science_center_objects).  The original data consists of 16-bit big-endian elevation data split into multiple tiles.  Presently, these data are available as GeoTif files. 

This repo represents a reformatted version of the USGS data.  Instead of multiple tiles, the data is grouped into a single file.  The data format was also changed from big-endian to little endian.  The file contains no metadata and represents only raw data.