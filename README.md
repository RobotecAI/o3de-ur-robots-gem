[![Apache License, Version 2.0][apache_shield]][apache]

# UR10 and UR20 Robots Gem for Open 3D Engine (O3DE)

## A bit of context

* [Open 3D Engine](https:://o3de.org) - an open source game & simulation engine. O3DE is extendable through modules
  called Gems. This is one of such Gems.
* [Robot Operating System (ROS)](https://docs.ros.org/en/rolling/index.html) - an open source middleware and de facto
  standard for robotics.
* [ROS2 Gem](https://github.com/o3de/o3de-extras/tree/development/Gems/ROS2) - an open source module for O3DE which
  enables simulation for robotics using modern ROS.
* [Universal Robots](https://www.universal-robots.com/) - Universal Robots provides duty industrial collaborative robotic arms for manufacturing facilities and warehouses.

## Requirements
- Any O3DE project with the [O3DE ROS2 Gem](https://github.com/o3de/o3de-extras/tree/development/Gems/ROS2) enabled.

## Description
This gem contains the following assets:
- [UR10](https://www.universal-robots.com/products/ur10-robot/)
- [UR20](https://www.universal-robots.com/products/ur20-robot/)
- pneumatic vacuum end effector

## UR10 and UR20 sample images
![](docs/images/front.png)
![](docs/images/back.png)

## O3DE 
Robots are delivered as prefabs, containing models and physics, along with the following ROS components:
- ROS2 Frame
- ROS2 Robot Control

---

This work is licensed under [Apache License, Version 2.0][apache]. You may elect at your option to use the [MIT License][mit] instead. Contributions must be made under both licenses.

[apache]: https://opensource.org/licenses/Apache-2.0
[mit]: https://opensource.org/licenses/MIT
[apache_shield]: https://img.shields.io/badge/License-Apache_2.0-blue.svg
