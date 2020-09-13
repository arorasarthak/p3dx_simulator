# p3dx_simulator
Contains ROS packages for simulating the Pioneer 3DX robot using CoppeliaSim

## Installation and Usage

**Replace YOUR_WORKSPACE with the name of your workspace!**

#### Clone the repo in your src folder.
`cd YOUR_WORKSPACE/src && git clone --recursive https://github.com/arorasarthak/p3dx_simulator.git .`

#### Run catkin_make from your workspace.
`cd YOUR_WORKSPACE && catkin_make`

#### Source the workspace.
`source YOUR_WORKSPACE/devel/setup.bash`

#### Launch the simulation.
`roslaunch p3dx_sim simulation.launch`
