```bash
echo "deb [trusted=yes] https://github.com/qiayuanl/unitree_buildfarm/raw/noble-jazzy-arm64/ ./" | sudo tee /etc/apt/sources.list.d/qiayuanl_unitree_buildfarm.list
echo "yaml https://github.com/qiayuanl/unitree_buildfarm/raw/noble-jazzy-arm64/local.yaml jazzy" | sudo tee /etc/ros/rosdep/sources.list.d/1-qiayuanl_unitree_buildfarm.list
```
