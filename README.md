# final-task

Using hector slam:
I followed the steps mentioned on this website: 
http://wiki.ros.org/hector_slam/Tutorials/MappingUsingLoggedData


And got the following output:
<img width="1440" alt="Screenshot 2023-04-21 at 12 31 30 PM" src="https://user-images.githubusercontent.com/128273933/233590367-be06ccdb-9312-4e89-aa6d-5a6e35020df7.png">

For the second task, I have the entire code. of what has to be done, I'm just not able to execute the previous commands:
roscd mobile_manipulator_body/urdf/
wget https://github.com/sr14051/final-task/commit/2eb5931f1286729dac43f3130b855c2772ad9819

cd ~/catkin_ws/
catkin_make
source devel/setup.bash
roscd mobile_manipulator_body/urdf/
roslaunch urdf_tutorial display.launch model:= Create sterecamera.urdf



