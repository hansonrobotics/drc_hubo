# drc_hubo

## To run simulation

Run PODOLauncher:
```bash
cd drc_hubo/podo/Execute\ Daemon/
./PODOLauncher
```

Choose the correct Daemon directory and click Start Daemon.

Run PODOGUI
```bash
cd drc_hubo/podo/PODOGUIBuild
./PODOGUI
```

Export the Gazebo models path:
```bash
export GAZEBO_MODEL_PATH=~/catkin_ws/src/drc_hubo/ros/drc_plugin/models/:$GAZEBO_MODEL_PATH
```

Launch the simulation with the following command:
```bash
roslaunch drc_podo_connector drc_hubo.launch
```