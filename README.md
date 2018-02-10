This tutorial contains a controller example which exploits [WB-Toolbox](https://github.com/robotology/WB-Toolbox).

It implements a PD plus gravity compensation (which in its nature is quite generic), but references are targeted to the iCub robot.

### Running the example

1. Open Matlab, browse the directory containing this repository, open the `impedance_control.mdl` file.
2. Execute `yarpserver`
3. Open `gazebo -s libgazebo_yarp_clock.so` and drop the `iCubGazeboV2_5 fixed` model.
4. On Simulink, press Play.

The controller is now launched and the robot get controlled in torque for all the time the controller is running.
