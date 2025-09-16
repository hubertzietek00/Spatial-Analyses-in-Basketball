**Digital Court and Coordinate System**:

The layers are vector line geometries designed for use in GIS software.

The court is defined in a Cartesian 2D coordinate system (by default EPSG:3857, pseudo-Mercator), but it can be any other 2D Cartesian coordinate system with X and Y axes and units expressed in meters.

This digital basketball court model represents a standard court with dimensions of 28 by 15 meters. Field dimensions (in meters) range approximately from -7.5 to 7.5 on the X-axis (width) and from -14 to 14 on the Y-axis (length). The origin point (0,0) is located at the center (centroid) of the court. The fixed reference point for the basket is at coordinates (0, 12.425).

Shot coordinates undergo scaling and rotation transformations to fit the court model.

Included is a spatial grid overlay with individual grid cells sized 15 cm x 14 cm, facilitating detailed spatial segmentation and analysis on the court.

