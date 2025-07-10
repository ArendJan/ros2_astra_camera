```bash
echo "deb [trusted=yes] https://github.com/ArendJan/ros2_astra_camera/raw/ros_humble_jammy_amd64/ ./" | sudo tee /etc/apt/sources.list.d/ArendJan_ros2_astra_camera.list
echo "yaml https://github.com/ArendJan/ros2_astra_camera/raw/ros_humble_jammy_amd64/local.yaml humble" | sudo tee /etc/ros/rosdep/sources.list.d/1-ArendJan_ros2_astra_camera.list
```
