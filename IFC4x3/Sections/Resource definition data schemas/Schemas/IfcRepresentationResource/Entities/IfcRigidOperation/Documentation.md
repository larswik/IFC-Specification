A rigid operation specifies an offset in the coordinate reference system. It does not specify any conversion or distortion. It is a coordinate operation that tells that the whole virtual model is translated in the same way. For example, using lengths to translate along x,y,z; or using angles for a 2D translation (e.g., lambda, phi), plus a change in height.

>EXAMPLE If data is in truncated map coordinates (i.e., the map coordinates have the leading digits removed in x and y), then IfcRigidOperation simply translates the data in x and y to replace the ignored leading digits. This is also known as subtraction.

>HISTORY New entity in IFC4X3_ADD1

