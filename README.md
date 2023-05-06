# PhoenixRover
PhoenixRover - A Mars Rover Inspired Robot for Human Rescue

PhoenixRover is a robot designed to help rescue people who are stuck in hazardous situations such as earthquake, fire, or other disasters. This robot is inspired by the Mars rovers that are designed to explore rough terrains and difficult environments. PhoenixRover can navigate through rubble, debris, and other obstacles that humans may find difficult to traverse.

The robot's body is made of hard plastic that can withstand the harsh conditions of rescue operations. It is powered by six strong DC motors that are manually controlled via an RF controller. The robot is equipped with a camera that serves as a viewfinder and helps the ML model to identify any part of the human body for quick rescue.

OpenCV is used for the detection of humans. The HOG algorithm is used in this regard. The camera captures the frame, which is then processed. After that, the HOG model locates the bounding box for the detected objects and creates bounding boxes around them with labels. All of these can be monitored remotely via IoT.

The robot is also equipped with a claw that can be equipped with drills for remote rescue missions. It can also supply emergency food and medicines to the stuck personnel. This feature is especially useful in cases where the rescue operation may take a long time.

In addition, there was a plan to map out the surrounding area with a 3D lidar and SLAM. This would help in locating important targets faster. However, this feature was due to be implemented later.

PhoenixRover is designed to be a reliable and efficient tool for rescue operations. It can be used in various scenarios, such as collapsed buildings, mines, or other hazardous environments. With its ability to navigate through difficult terrains and detect humans quickly, it can potentially save many lives. The project team is committed to continuing development and improving the robot's capabilities to provide even better support in rescue operations in the future.
