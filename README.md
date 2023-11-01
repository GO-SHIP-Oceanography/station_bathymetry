<<<<<<< HEAD
# Station bathymetry
The purpose of the script is to check the bathymetry at a station in preparation of a CTD cast. The main concern is that the CTD might drift upgradient, into the topography, and hit the bottom. Knowing the bathymetry a priori helps avoiding such issue, and can help 
- informing the bridge about what direction to drift (the resolution of the bathymetry used here is often higher than the one of the nautical charts available onboard);
- deciding whether to stop the cast slightly before (e.g. 15m from the bottom)
- deciding whether to ask the whinch to recover the package faster than usual (e.g. 75 mpm rather than the standard 60 mpm)

This script returns a latitude vs longitude contour plot of the bathymetry around a station speficied by the user (within a 6nm radius from the selected station). It also plots the station position (as a red triangle) and a half-mile radius around the station, which is usually how much the ship can drift during a deep (~4000 m) station.

## Usage
Usage is allowe under the MIT licence. We encourage usage and welcome feature requests.


## Install instructions 

To install, clone the repository, navigate to `station_bathymetry`, and run:
	
	python3 -m pip install .

It is recommended to use a virtual environment.

## Getting started

The plotting tool takes the form of a jupyter notebook `plot_bathymetry_at_station.ipynb`.
This can be run using:

	pip install notebook

   	 jupyter notebook plot_bathymetry_at_station.ipynb


## Contributions
=======
# station_bathymetry
Plot lat/lon bathymetry at station

## Installation

To install, clone the repository, navigate to `station_bathymetry`, and run:

    python3 -m pip install .

It is recommended to use a virtual environment.

## Getting Started

The plotting tool takes the form of a jupyter notebook
`plot_bathymetry_at_station.ipynb`.
This can be run using:

    jupyter notebook plot_bathymetry_at_station.ipynb
>>>>>>> 438001da2f9f0a213543dc3534711ed5bae22a87
