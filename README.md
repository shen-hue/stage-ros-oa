# stage-ros-oa
## 1. Installation
## 2. Start
### 2.1 Create docker container
### 2.2 Activate virtualenvironments
```
workon stageros
```
### 2.3 Start planners
* CrowdNav
```
roslaunch crowdnav cdnv.launch
```
* rl-collision
```
roslaunch rl_collision_avoidance rlca.launch
```
* teb
```
roslaunch teb_local_planner_tutorials dyn_obst_corridor_scenario.launch
```
launch file will start obstacles first, then start the planners
### 2.4 Change obstacles
Start 13 obstacles through move_obstacle.py
You can change the number and velocity of obstacles in launch file
