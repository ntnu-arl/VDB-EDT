# VDB-EDT: An Efficient Euclidean Distance Transform Algorithm Based on VDB Data Structure

VDB-EDT is an efficient and robust library for large-scale occupancy grid mapping and Euclidean distance transform.  Compared with the state-of-the-art method, VDB-EDT can provide high-quality and more complete mapping results, while consuming less memory and processing time. 

The video demonstration for ICRA-2021 paper can be found here https://youtu.be/Bojh6ylYUOo

## Installation

1.  This package is developed based on ROS Kinetic/Melodic and the Eigen3 library is also needed.

2.  Dependencies for OpenVDB and the Catkin wrapper

   `sudo apt-get install libglfw3-dev libblosc-dev libopenexr-dev`

   `sudo apt-get install liblog4cplus-dev`

3. Clone the package and cd to the vdb_edt folder

   `cd src`

   `catkin_init_workspace`

   `cd ..`

   `catkin build`    (no `catkin_make` command )

### Run

Make sure the current path is at vdb_edt folder, i.e., in the catkin workspace

   `soource devel/setup.bash`

   `roslaunch vdb_edt vdb_edt.launch`

### Testing

Ubuntu 18 + ROS Melodic

### Acknowledgement

The VDB Ros Wrapper inside this package is developed by Rohit Garg from Air Lab CMU based on the work of ETHZ ASL. We give our special acknowledgement to him. 
