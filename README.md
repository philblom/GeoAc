# GeoAc
Infrasonic ray tracing code

GeoAc is a numerical package written in C++ which solves the equations governing acoustic 
propagation through the atmosphere in the geometric limit using a RK4 algorithm.  It contains
multiple instances of said equation system and is able to model propagation in an azimuthal 
plane using the effective motionless medium approximation as well as in three dimensions 
using an inhomogeneous moving background medium.  The three dimensional propagation scheme 
include methods to model propagation in a Cartesian coordinate system as well as a spherical 
coordinate system which incorporates the curvature of the earth. 

See manual for more information.

NOTE: GeoAc methods are no longer updated and have been replaced by the infraGA/GeoAc methods
that are available at https://github.com/LANL-Seismoacoustics/infraGA

___________________________________________
___________________________________________

References



Keys, Robert G. "Cubic convolution interpolation for digital image processing." Acoustics, Speech and Signal Processing, IEEE Transactions on 29.6 (1981): 1153-1160.

Blom, Philip, and Roger Waxler. "Impulse propagation in the nocturnal boundary layer: Analysis of the geometric component." The Journal of the Acoustical Society of America 131.5 (2012): 3680-3690.

Blom, Philip. Interaction of the cyclonic winds with the infrasonic signal generated by a large maritime storm. Dissertation, University of Mississippi, ProQuest/UMI, 2013. (UMI No. 3567512)

___________________________________________
___________________________________________

[LANL Seismoacoustics](https://lanl-seismoacoustics.github.io/)
