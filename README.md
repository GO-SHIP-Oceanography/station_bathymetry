## Station bathymetry
The purpose of the script is to check the bathymetry at a station in preparation of a CTD cast. The main concern is that the CTD might drift upgradient, into the topography, and hit the bottom. Knowing the bathymetry a priori helps avoiding such issue, and can help 
- informing the bridge about what direction to drift (the resolution of the bathymetry used here is often higher than the one of the nautical charts available onboard);
- deciding whether to stop the cast slightly before (e.g. 15m from the bottom);
- deciding whether to ask the whinch to recover the package faster than usual (e.g. 75 mpm rather than the standard 60 mpm);

This script returns a latitude vs longitude contour plot of the bathymetry around a station speficied by the user. It also plots the station position and a half-mile radius around the station, which is usually how much the ship will drift during a deep (~4000 m) station.

### Usage
Usage is allowed under the [MIT licence](https://github.com/GO-SHIP-Oceanography/station_bathymetry/blob/main/LICENSE). We encourage usage and welcome feature requests. It is appreciated if visible credit is given by any projects using the [GO-SHIP-Oceanography](https://github.com/GO-SHIP-Oceanography) code.


### Install instructions 

To install, clone the repository, navigate to `station_bathymetry`, and run:
	
	python3 -m pip install .

It is recommended to use a virtual environment.

### Getting started

The plotting tool takes the form of a jupyter notebook `plot_bathymetry_at_station.ipynb`.
This can be run using:

	pip install notebook

   	jupyter notebook plot_bathymetry_at_station.ipynb
   	

### Code Description
Please check the jupyter notebook for details about the code steps, input files and user-controlled parameters.
 


### Contributions
Contributions and collaborations are welcomed from anyone with an interest in [GO-SHIP](https://www.go-ship.org/), and more in general ship-based hydrographic observations and python.

For bugs, feature requests, and clear suggestions for improvement please [open an issue](https://github.com/GO-SHIP-Oceanography/station_bathymetry/issues).

### Authors and Acknowledgment
If you use this software in your work, please provide visible credit/citation.
