# awesome-vacuum with stars

A curated list of free and open source software and hardware projects which can be used to build and control a robot vacuum.

***

* [awesome-vacuum](#awesome-vacuum)
* [Hardware](#hardware)
  * [IMU](#imu)
  * [LIDAR](#lidar)
  * [Projects](#projects)
* [Software](#software)
  * [Frameworks](#frameworks)
  * [SLAM](#slam)
* [Other Awesome Lists](#other-awesome-lists)
* [Contributing](#contributing)

***

# Hardware

**[`^        back to top        ^`](#)**

## IMU

**[`^        back to top        ^`](#)**

A IMU helps to make localization much more stable by providing accelerometer, gyroscope and some even magnetometer data.
[cartographer](https://github.com/cartographer-project/cartographer) ⭐ 8,012 | 🐛 241 | 🌐 C++ | 📅 2024-01-05 can easily be setup with IMU to improve localization.

* [MPU6050](https://playground.arduino.cc/Main/MPU-6050/) - IMU sensor combining a MEMS accelerometer and a MEMS gyro on a single chip.

## LIDAR

**[`^        back to top        ^`](#)**

A LIDAR (Light Detection and Ranging) can create an accurate representation of its surroundings by utilizing a laser and a light sensor to measure TOF (Time of Flight). Devices are available as 2D and 3D variants, although the 3D variants are still pretty expensive and do not add much value to the "robot vacuum" use case.

* [kaiaai LDS](https://github.com/kaiaai/LDS) ⭐ 238 | 🐛 1 | 🌐 C++ | 📅 2026-08-25 - Arduino library with a single API for 20+ low-cost 2D LiDARs, including ones salvaged from robot vacuums (Xiaomi LDS02RR, Neato XV11, Camsense X1, YDLIDAR, ...). `Apache-2.0` `C++`
* [camsense-X1](https://github.com/Vidicon/camsense-X1) ⭐ 74 | 🐛 1 | 📅 2020-10-03 - Unofficial reverse engineering of a Chinese LiDAR. `GPL-3.0`
* [RPLIDAR A Series](https://www.slamtec.com/en/Lidar/A1) - 360 Degree Laser Scanner with ROS integration and up to 16K samples per second.

## Projects

**[`^        back to top        ^`](#)**

A list of full blown projects to create a robot vacuum.

* [OOMWOO](https://github.com/makerspet/oomwoo) ⭐ 13,165 | 🐛 4 | 🌐 Python | 📅 2026-11-19 - Open source robot vacuum you build yourself, using a Raspberry Pi, 3D printing, ROS 2 and Home Assistant. `Apache-2.0` `Python`
* [OOMWOO PCB](https://github.com/makerspet/oomwoo-pcb) ⭐ 58 | 🐛 2 | 🌐 Python | 📅 2026-11-19 - I/O board (STM32 with motor drivers and sensor inputs) for the OOMWOO robot vacuum. `Apache-2.0`
* [CleanBOT](https://www.instructables.com/CleanBOT/) - DIY bluetooth controlled robot vacuum built from wood and scrap electronics.
* [DIY Vacuum Robot by CesNieto](https://www.instructables.com/Build-Your-Own-Vacuum-Robot/) - DIY robot vacuum built using 3D printing and an Arduino Uno.
* [DIY Robot Vacuum by Mr. Cookie](https://hackaday.io/project/182176-diy-robot-vacuum) - DIY robot vacuum built from an Arduino, MDF and widely available parts, without custom PCBs. Laser-cut files for the frame are provided.
* [Robot Vacuum Cleaner MK2](https://www.myminifactory.com/object/3d-print-101108) - DIY robot vacuum built using 3D printing and an Arduino Nano. `BY-NC-SA`

# Software

**[`^        back to top        ^`](#)**

* [Valetudo](https://github.com/Hypfer/Valetudo) ⭐ 10,029 | 🐛 0 | 🌐 JavaScript | 📅 2026-11-18 - Cloud-free control webinterface for vacuum robots. `Apache-2.0` `JavaScript`
* [python-miio](https://github.com/rytilahti/python-miio) ⭐ 4,344 | 🐛 321 | 🌐 Python | 📅 2026-07-25 - Python library and console tool for controlling Xiaomi smart appliances, including vacuums. `GPL-3.0` `Python`
* [Dreame Vacuum](https://github.com/Tasshack/dreame-vacuum) ⭐ 2,308 | 🐛 16 | 🌐 Python | 📅 2026-11-03 - Home Assistant integration for Dreame robot vacuums with map support. `MIT` `Python`
* [Dustcloud](https://github.com/dgiese/dustcloud) ⭐ 2,282 | 🐛 85 | 🌐 C | 📅 2024-02-16 - Xiaomi Smart Home Device Reverse Engineering and Hacking. `GPL-3.0` `Various`
* [Xiaomi Vacuum Map Card](https://github.com/PiotrMachowski/lovelace-xiaomi-vacuum-map-card) ⭐ 1,957 | 🐛 74 | 🌐 TypeScript | 📅 2026-06-24 - Home Assistant Lovelace card to control map-based vacuums (Xiaomi, Valetudo, Neato, Roomba, Ecovacs, ...). `MIT` `TypeScript`
* [Xiaomi Cloud Map Extractor](https://github.com/PiotrMachowski/Home-Assistant-custom-components-Xiaomi-Cloud-Map-Extractor) ⭐ 1,437 | 🐛 169 | 🌐 Python | 📅 2026-02-20 - Home Assistant integration showing a live map for Xiaomi, Roborock, Viomi, Roidmi and Dreame vacuums without rooting. `MIT` `Python`
* [dorita980](https://github.com/koalazak/dorita980) ⭐ 1,210 | 🐛 14 | 🌐 JavaScript | 📅 2026-02-27 - Unofficial SDK to control iRobot Roomba and Braava robots over the local network. `MIT` `JavaScript`
* [Valetudo RE](https://github.com/rand256/valetudo) ⭐ 711 | 🐛 37 | 🌐 JavaScript | 📅 2025-08-19 - Experimental vacuum software, cloud free (Valetudo Fork) `Apache-2.0` `JavaScript`
* [Bumper](https://github.com/bmartin5692/bumper) ⭐ 402 | 🐛 61 | 🌐 Python | 📅 2024-08-05 - A standalone and self-hosted implementation of the central server used by Ecovacs vacuum robot. `GPL-3.0` `Python`
* [CleanIt](https://github.com/Sollimann/CleanIt) ⭐ 327 | 🐛 4 | 🌐 Rust | 📅 2025-11-19 - Open-source autonomy software using gRPC for the Roomba series robot vacuum cleaners. Under development. `MIT` `Rust`
* [python-roborock](https://github.com/python-roborock/python-roborock) ⭐ 251 | 🐛 80 | 🌐 Python | 📅 2026-11-19 - Python library and console tool for controlling Roborock vacuums. `Apache-2.0` `Python`
* [Roborock Oucher](https://github.com/porech/roborock-oucher) ⭐ 215 | 🐛 3 | 🌐 Go | 📅 2025-07-08 - An utility to make the Roborock / Xiaomi MI Vacuum Cleaner scream "Ouch!" (or everything else) everytime it bumps into something `MIT` `golang`
* [MQTT Vacuum Camera](https://github.com/sca075/mqtt_vacuum_camera) ⭐ 185 | 🐛 0 | 🌐 Python | 📅 2026-11-20 - Home Assistant camera integration to render the maps of vacuums connected via MQTT (Valetudo, Valetudo RE, Congatudo). `Apache-2.0` `Python`
* [vacuum (zvldz)](https://github.com/zvldz/vacuum) ⭐ 158 | 🐛 1 | 🌐 Shell | 📅 2026-10-13 - Firmware builder for first and second generation Roborock vacuums. `GPL-3.0` `Shell`
* [I can't belive it's not Valetudo](https://github.com/Hypfer/ICantBelieveItsNotValetudo) ⚠️ Archived - Valetudo companion service (Map Rendering) `Apache-2.0` `JavaScript`
* [valetudo mapper](https://github.com/rand256/valetudo-mapper) ⭐ 74 | 🐛 0 | 🌐 JavaScript | 📅 2023-09-15 - Valetudo companion service (Map Rendering, ICantBelieveItsNotValetudo Fork) `Apache-2.0` `JavaScript`
* [Congatudo](https://github.com/freeconga/congatudo-add-on) ⭐ 43 | 🐛 2 | 🌐 Shell | 📅 2025-07-16 Freecon.ga project to have Valetudo in the Home Assistant as addon intead of use standalone installation into the vacuum. `GPL-3.0` `Shell`
* [VacuumTiger](https://github.com/codetiger/VacuumTiger) ⭐ 42 | 🐛 1 | 🌐 Rust | 📅 2026-09-20 - Modular, configuration-driven open source firmware for robot vacuums, with a generic TCP protocol for SLAM applications. `MIT` `Rust`
* [Xiaomi Vacuum](https://github.com/matteocelani/xiaomi-vacuum) ⭐ 0 | 🐛 0 | 🌐 Python | 📅 2026-11-17 - Home Assistant integration for Xiaomi and Dreame robot vacuums with map support, a maintained fork of Dreame Vacuum. `MIT` `Python`
* [Robot Info](https://robotinfo.dev/) - Overview of robot vacuums with hardware details and information on which models can be rooted.
* [FreeCong.ga](https://freecon.ga) - Valetudo implementation for Cecotec Conga Vacuums. [Freeconga Organization](https://github.com/freeconga) in Github. `Apache-2.0`, `GPL-3.0`
* [OpenDoñita](https://gitlab.com/rastersoft/opendonita) - Add local support for previous Congas 1490. `GPL-3.0` `Python`

## Frameworks

**[`^        back to top        ^`](#)**

* [Gobot](https://github.com/hybridgroup/gobot/) ⭐ 9,497 | 🐛 102 | 🌐 Go | 📅 2026-01-07 - Golang framework for robotics, drones, and the Internet of Things (IoT).  `Apache-2.0` `golang`
* [ROS (Robot Operating System)](https://wiki.ros.org/) - Provides libraries and tools to help software developers create robot applications. It provides hardware abstraction, device drivers, libraries, visualizers, message-passing, package management, and more. `BSD` `Various`

## SLAM

**[`^        back to top        ^`](#)**

SLAM (Simultaneous Localization and Mapping) is used to build a map by repeatedly scanning surrounding area and through that enable the robot to localize itself within that environment.

* [cartographer](https://github.com/cartographer-project/cartographer) ⭐ 8,012 | 🐛 241 | 🌐 C++ | 📅 2024-01-05 - A system that provides real-time simultaneous localization and mapping (SLAM) in 2D and 3D across multiple platforms and sensor configurations. `Apache-2.0` `C++`
* [OpenVSLAM](https://github.com/xdspacelab/openvslam) ⚠️ Archived - A Versatile Visual SLAM Framework. `2-Clause BSD` `C++`
* [BreezySLAM](https://github.com/simondlevy/BreezySLAM) ⭐ 818 | 🐛 57 | 🌐 C | 📅 2026-02-05 - Simple, efficient, open-source package for Simultaneous Localization and Mapping. `LGPLv3` `Various`
* [ROS SLAM](https://github.com/ros-perception/slam_gmapping) ⭐ 737 | 🐛 44 | 🌐 C++ | 📅 2024-08-21 - A ROS wrapper for OpenSlam's Gmapping. `BSD` `C++`

***

# Other Awesome Lists

* [Awesome Robotic Tooling](https://github.com/protontypes/awesome-robotic-tooling) ⭐ 3,924 | 🐛 14 | 📅 2023-11-20

# Contributing

You know a software or hardware project that is not on this list yet? Contributions are very much welcome! Have a look at the [Contribution Guidelines](.github/CONTRIBUTING.md) to learn how you can add projects to this list.

***

> _Enhansomed by [enhansome](https://github.com/enhansome) on 2026-11-20._
