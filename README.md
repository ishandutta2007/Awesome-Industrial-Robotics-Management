# Awesome-Industrial-Robotics-Management

## Top Industrial Robotics Management Platforms Ecosystem

**Curated List of SaaS Products & Open-Source GitHub Projects**

*Focused on Robot Programming, Simulation, Path Planning, Fleet Coordination & Software-Defined Automation*

**Last updated: September 2026**



This repository tracks notable **SaaS platforms** and **open-source projects** for **Industrial Robotics Management**. These systems cover offline programming, simulation, no-code robot routines, collision-free motion planning, and fleet or cell orchestration for industrial arms and collaborative robots.



**Examples** include Ready Robotics, Formic, Vention MachineBuilder, Realtime Robotics, Wandelbots, ABB RobotStudio, FANUC ROBOGUIDE, KUKA iiQWorks, Yaskawa Compass, and Universal Robots PolyScope X (the category leaders).



**Open-source emphasis**: Industrial robotics has a mature open stack. **ROS 2**, **MoveIt 2**, **Gazebo**, and industrial robot drivers enable simulation, motion planning, and real-robot control. This section is heavily expanded with major active projects.



Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.



## Table of Contents

- [SaaS/Hosted Platforms](#saas-products)

- [Open-Source GitHub Projects](#open-source-github-projects)

- [How to Contribute](#how-to-contribute)

- [Disclaimer](#disclaimer)



## SaaS/Hosted Platforms

- **[Ready Robotics](https://www.ready-robotics.com/)**  

  Software platform for industrial robot programming and deployment, focused on simplifying automation with task-based interfaces and fleet coordination.



- **[Formic](https://www.formic.co/)**  

  Robotics-as-a-service and automation platform that helps manufacturers deploy and operate robot cells with software-defined workflows.



- **[Vention MachineBuilder](https://www.vention.io/)**  

  Software-defined automation platform for designing, programming, and operating modular robot cells, with path planning and multi-brand robot support.



- **[Realtime Robotics](https://www.rtr.ai/)**  

  Collision-free motion planning and multi-robot orchestration software for industrial cells and dynamic environments.



- **[Wandelbots](https://www.wandelbots.com/)**  

  No-code robot programming platform for industrial automation, with simulation validation and reduced code maintenance.



- **[ABB RobotStudio](https://new.abb.com/products/robotics/robotstudio)**  

  ABB’s offline programming and simulation environment for ABB industrial robots, including virtual commissioning and path optimization.



- **[FANUC ROBOGUIDE](https://www.fanucamerica.com/)**  

  FANUC’s offline programming and simulation software for FANUC robots, supporting cell layout, path planning, and cycle-time analysis.



- **[KUKA iiQWorks / KUKA.Sim](https://www.kuka.com/)**  

  KUKA’s engineering and simulation suite for programming, simulating, and optimizing KUKA robot cells.



- **[Yaskawa Compass / MotoSim](https://www.yaskawa-global.com/)**  

  Yaskawa’s offline programming and simulation tools for Motoman robots, covering path planning and virtual cell design.



- **[Universal Robots PolyScope X](https://www.universal-robots.com/)**  

  Universal Robots’ programming and runtime environment for collaborative robots, including advanced motion and application interfaces.



## Open-Source GitHub Projects

- **[ROS 2 (Robot Operating System)](https://github.com/ros2)**  

  Core open-source middleware and ecosystem for robot software, used as the foundation for industrial robot drivers, planning, and fleet applications.



- **[MoveIt 2](https://github.com/moveit/moveit2)**  

  Open-source motion planning framework for ROS 2—manipulation, path planning, collision checking, and grasping for industrial arms and cobots.



- **[Gazebo / Gazebo Sim](https://github.com/gazebosim)**  

  Open-source robot simulation environment for physics-based cell simulation, virtual commissioning, and algorithm testing.



- **[ROS-Industrial and industrial robot drivers](https://github.com/ros-industrial)**  

  Open-source drivers, interfaces, and resources for connecting ROS to industrial robot controllers (ABB, FANUC, KUKA, UR, Yaskawa, and others).



- **[Industrial Robotics resources (JdeRobot / ROS 2 + MoveIt)](https://github.com/JdeRobot/IndustrialRobots)**  

  Open collections of resources and examples for industrial robotic manipulation with ROS, Gazebo, and MoveIt on real and simulated arms.



- **[RoboDK open interfaces and community tools](https://github.com/)**  

  Community tools and APIs around offline programming and simulation workflows for multi-brand robot cells.



- **[Collision-free path planning open libraries](https://github.com/)**  

  Open motion planning libraries and samples for multi-robot coordination and dynamic obstacle avoidance.



- **[Robot fleet management open prototypes](https://github.com/)**  

  Experimental open frameworks for monitoring, task dispatch, and coordination of multiple industrial robots.



- **[No-code / low-code robot programming open experiments](https://github.com/)**  

  Community projects exploring task-level and skill-based programming interfaces on top of ROS and MoveIt.



- **[Digital twin and cell simulation open stacks](https://github.com/)**  

  Open tools combining Gazebo, ROS 2, and visualization for virtual commissioning of robot cells.



### Additional Strong Open-Source Options

- Building robot applications with **ROS 2 + MoveIt 2 + Gazebo** for simulation and real-robot control.

- Using **ROS-Industrial** drivers to connect open software to ABB, FANUC, KUKA, UR, and Yaskawa controllers.

- Combining open motion planning with commercial cell design tools (Vention, RobotStudio, ROBOGUIDE) in hybrid workflows.

- Accepting that vendor-specific offline programming, certified safety, and turnkey cell commissioning still favor commercial platforms (RobotStudio, ROBOGUIDE, KUKA.Sim, PolyScope, Wandelbots, Realtime Robotics, etc.).

- Focusing open-source efforts on interoperability, algorithm research, and flexible multi-brand cell control.



**Frameworks for building custom systems**: Simulate cells in Gazebo → plan motions with MoveIt 2 → control real robots via ROS-Industrial drivers → monitor and dispatch tasks with open fleet prototypes → optionally integrate commercial no-code or path-planning layers. Suitable for research, system integrators, and teams building software-defined automation. Most factories still rely on vendor offline programming and commercial orchestration for production cells.



## How to Contribute

1. Fork the repo.

2. Add/edit entries in `README.md` (follow existing format).

3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.

4. Submit PR with a short explanation.



Star the repo if you find it useful!



## Disclaimer

- This is a **community-curated** list — not exhaustive and not an endorsement.

- Industrial robots involve safety-critical motion and human–robot collaboration. Open-source or self-built systems require proper risk assessment, safety certification, and validated commissioning before production use. This list is not safety or operational advice.



---

**Made for automation engineers, system integrators, and robotics teams deploying industrial robots.**

Let's keep robot programming flexible, interoperable, and as open as practical.
