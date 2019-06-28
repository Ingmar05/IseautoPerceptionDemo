# IseautoPerceptionDemo

ROS workspace to demonstrate the perception of a self driving on a down scale model.

## Run demo

* `sudo apt update`
* `git clone https://github.com/Ingmar05/IseautoPerceptionDemo.git`
* `cd IseautoPerceptionDemo`
* `rosdep install --from-paths src --ignore-src --rosdistro=melodic -y`
* `catkin_make -DCMAKE_BUILD_TYPE=Release`
* `source devel/setup.bash`
* `roslaunch iseauto_preception preception.launch`
