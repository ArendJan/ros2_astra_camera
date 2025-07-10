```bash
echo "deb [trusted=yes] https://github.com/ArendJan/ros2_astra_camera/raw/ros_jazzy_noble_arm64/ ./" | sudo tee /etc/apt/sources.list.d/ArendJan_ros2_astra_camera.list
echo "yaml https://github.com/ArendJan/ros2_astra_camera/raw/ros_jazzy_noble_arm64/local.yaml jazzy" | sudo tee /etc/ros/rosdep/sources.list.d/1-ArendJan_ros2_astra_camera.list
```
