### BRB! SLAM in practice 

Slam is exciting. Slam is fun. This repository is my personal practice board to implement classical slam algorithms.

Through this repository, I intend to keep a track of all the papers I read on slam and try to implement them. And if not the entire paper, then important concepts and data structures to store sensor data for practice and fun. 

#### File structure 

├── assets
│   └── ros_perception_tools
│       └── slam_gmapping
│           ├── gmapping
│           │   ├── CHANGELOG.rst
│           │   ├── CMakeLists.txt
│           │   ├── launch
│           │   │   └── slam_gmapping_pr2.launch
│           │   ├── nodelet_plugins.xml
│           │   ├── package.xml
│           │   ├── src
│           │   │   ├── main.cpp
│           │   │   ├── nodelet.cpp
│           │   │   ├── replay.cpp
│           │   │   ├── slam_gmapping.cpp
│           │   │   └── slam_gmapping.h
│           │   └── test
│           │       ├── basic_localization_laser_different_beamcount.test
│           │       ├── basic_localization_stage.launch
│           │       ├── basic_localization_stage_replay2.launch
│           │       ├── basic_localization_stage_replay.launch
│           │       ├── basic_localization_symmetry.launch
│           │       ├── basic_localization_upside_down.launch
│           │       ├── rtest.cpp
│           │       └── test_map.py
│           ├── README.md
│           └── slam_gmapping
│               ├── CHANGELOG.rst
│               ├── CMakeLists.txt
│               └── package.xml
├── data
└── README.md


