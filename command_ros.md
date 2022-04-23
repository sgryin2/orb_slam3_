## first run 
roscore
## go to download,run
rosbag play PATH/TO/BAG
for example,
rosbag play MH_03_medium.bag
## go to ORB_SLAM3, run
rosrun ORB_SLAM3 Mono Vocabulary/ORBvoc.txt Example/Monocular/EuRoc.yaml
