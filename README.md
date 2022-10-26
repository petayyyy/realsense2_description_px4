## Realsense gazebo simulation with px4
Установка пакетов:
```bash
cd ~/catkin_ws/src
git clone https://github.com/petayyyy/realsense2_description_px4
git clone https://github.com/issaiass/realsense_gazebo_plugin
```
## Установка зависимостей на дрон:
Для запуска realsense на дроне необходимо заменить папку:
```bash
cd ~/catkin_ws/src/realsense2_description_px4
sudo mv clover_description ~/catkin_ws/src/clover
```

