# Wifi-Networks-Planification

 Create an application prototype to help plan access points within a 2D environment (building, office, etc.). 
 The tool must be able to predict coverage areas relative to access points installed in fixed positions and coordinates. 
 The extent of the coverage areas relating to each access point will be displayed with colors. 
 This will help to identify uncovered areas and the boundaries of areas with poor performance.
 
 Steps : 
 
 
 1- Realization of a simple graphical tool that displays the circular coverage area from the coordinates entered from the access points.
 Depending on the signal strength setting (between 10 to 100mw) over which the coverage distance can vary from 100meters to 250meters.
 
 2- Realization of an extension which allows to check if a point of certain coordinates belongs to a coverage or not. 
 In the case of yes, it is indicated to which access point it matches and which is the closest access point. Access points are assumed to be numbered.
 
 3- Introduce the signal attenuation effect depending on the distance. 
 The signal attenuation will be reflected by color degradation: areas covered with color degradation which reflects the attenuation according to the equation.
 
 4- Obstacles are rectangular in shape defined by the coordinates of these four points. 
 Realization of a point by point display with verification if there is an obstacle between the access point and the point.
