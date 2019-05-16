# navi_for_blind_people_pkgs

## Description
弱視の方を想定して開発している障害者サポートソフトウェア郡です。   
将来的にはLiDARとRGBDカメラをメインのセンサーとして障害物回避や段差検出などのサポートを提供する予定です。   

|パッケージ名 |概要|
|---|---|   
|laser_scan_obstacle_detection|LiDARを用いた障害物認識ソフトウェア|   

## Requirement
ROS(Kinetic KAME)   
もしくは互換性があるとされる物。

## Install
```
$ mkdir catkin_ws/src -p
$ cd catkin_ws/src
$ catkin_init_workspace
$ git clone https://github.com/yukimakura/navi_for_blind_people_pkgs.git
$ cd navi_for_blind_people_pkgs
$ wstool update
$ cd ../../
$ catkin_make
$ source ~/catkin_ws/devel/setup.bash
```

## Licence
MIT

## Author

[yukimakura](https://twitter.com/yukimakura86)
