```bash
echo "deb [trusted=yes] https://github.com/qiayuanl/unitree_buildfarm/raw/jammy-humble-arm64/ ./" | sudo tee /etc/apt/sources.list.d/qiayuanl_unitree_buildfarm.list
echo "yaml https://github.com/qiayuanl/unitree_buildfarm/raw/jammy-humble-arm64/local.yaml humble" | sudo tee /etc/ros/rosdep/sources.list.d/1-qiayuanl_unitree_buildfarm.list
```
