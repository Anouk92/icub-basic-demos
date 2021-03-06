icub-basic-demos
===

This repository bundles a set of basic demos showing some of the iCub capabilities.
- The well known Red-Ball demo.
- The Yoga demo.
- The Force Control demo.
- The Force Imitation demo.

## Installation

##### Dependencies
- [YARP](https://github.com/robotology/yarp)
- [iCub](https://github.com/robotology/icub-main)
- [icub-contrib-common](https://github.com/robotology/icub-contrib-common)
- GTK2 (for Force Control demo).

##### Compilation
Demos can be compiled independently or altogether as a bundle. For the former
method go inside the directory corresponding to the demo you want to compile and
cmake the project; for the latter method, just cmake from the root directory.

## Documentation

Online documentation is available here: [http://robotology.github.com/icub-basic-demos](http://robotology.github.com/icub-basic-demos).

#### CI Build
- Linux: [![Build Status](https://travis-ci.org/robotology/icub-basic-demos.svg?branch=master)](https://travis-ci.org/robotology/icub-basic-demos)

## License

Material included here is Copyright of _iCub Facility - Istituto Italiano di Tecnologia_ and is released under the terms of the GPL v2.0 or later. See the file LICENSE for details.
