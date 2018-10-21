# Installation

Clone this repo into your ros catkin `src/` folder. Build the package with `catkin_make`. <br>
After building it for the first time go into the `devel` folder and locate `config_keys.h`. Search for `ULTRASOUND` and
then change the value `ADC_CMD_SELECT_ULTRASOUND_25Hz` to 9 (this will change the default ultrasound_freq to 9 and 8 will
be accepted from roslaunch). Be sure to always specify ultrasound in your launch file!

# Dependencies

`sudo apt install libsdl1.2-dev` <br>
On how to install ros see: `https://github.com/F-WuTS/pv_aerial/blob/master/INSTALL.md`

# ardrone_autonomy 

[ROS](http://ros.org) Driver for [Parrot AR-Drone](http://ardrone2.parrot.com/) 1.0 & 2.0 Quadrocopters

* Documentation: http://ardrone-autonomy.readthedocs.org/
* ROS wiki page: http://wiki.ros.org/ardrone_autonomy
* Code API: http://docs.ros.org/indigo/api/ardrone_autonomy/html
* Patched _ARDroneLib_ repository: https://github.com/AutonomyLab/ardronelib
* Author: [Mani Monajjemi](http://mani.im) ([Autonomy Lab](http://autonomylab.org), [Simon Fraser University](http://www.sfu.ca)) + [other contributers](http://ardrone-autonomy.readthedocs.org/en/latest/contributers.html)

## Build Status

* ROS Build farm (_Jade_): [![Build Status](http://build.ros.org/buildStatus/icon?job=Jdev__ardrone_autonomy__ubuntu_trusty_amd64)](http://build.ros.org/job/Jdev__ardrone_autonomy__ubuntu_trusty_amd64/)
* ROS Build farm (_Indigo_): [![Build Status](http://build.ros.org/buildStatus/icon?job=Idev__ardrone_autonomy__ubuntu_trusty_amd64)](http://build.ros.org/job/Idev__ardrone_autonomy__ubuntu_trusty_amd64/)
* Travis (_Jade_/_Indigo_): [![Build Status](https://travis-ci.org/AutonomyLab/ardrone_autonomy.svg?branch=indigo-devel)](https://travis-ci.org/AutonomyLab/ardrone_autonomy)

