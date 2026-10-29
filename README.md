## Tahsin Khan

Robotics engineer at the ERTS Lab (e-Yantra), IIT Bombay. BTech in Mechanical Engineering from NIT Karnataka, with a minor in Electronics and Communication.

I work on state estimation, SLAM and control for robots that run everything onboard, and on imitation learning for manipulation. I am interested in multi-robot systems and in combining model-based and learned methods.

[Website](https://tahsinop.github.io/) · [Google Scholar](https://scholar.google.com/citations?user=hTFoPnEAAAAJ) · [LinkedIn](https://www.linkedin.com/in/tahsin-khan-) · tahsinkhan6996@gmail.com

### Current work

**Grasp-anchored cooperative transport** (IIT Bombay, 2026 – present)
Two mobile manipulators built in-house (SO-101 arms on TurtleBot3 bases) carry one rigid payload using only wrist cameras and onboard compute: no motion capture, no shared map, no force/torque sensing. The shared grasp closes a kinematic chain, so each robot gets its partner's pose from its own arm encoders without drift. An SE(3) filter estimates the grasp and a 14-DoF whole-body QP does the control. [Project page](https://tahsinop.github.io/research/coop-manipulation/)

### Selected projects

- **Visual SLAM from scratch** (eYSIP 2025): Open3D and OpenCV front and back end, loop closure, pose-graph optimisation and bag-of-words relocalisation on a RealSense D455 and Orin NX. [Page](https://tahsinop.github.io/research/visual-slam-uav/)
- **Niti Vahan** (e-Yantra Robotics Competition 2026–27): electronics and a monocular perception and control stack for a miniature autonomous car on a Raspberry Pi; selected by 1500 teams. [Page](https://tahsinop.github.io/research/niti-vahan/)
- **Remote labs for robotics** (Krishi CoBot, eYRC 2025–26): remote access to a real UR5 and mobile robot for 649 teams; paper in preparation. [Page](https://tahsinop.github.io/research/remote-labs/)
- **LeHome Challenge, ICRA 2026**: bimanual garment folding in Isaac Sim with SmolVLA; rank 32 of 62. [Page](https://tahsinop.github.io/projects/lehome-icra-2026/)
- **Mentored, eYSIP 2026**: LiDAR-inertial SLAM on a UAV; ACT and SmolVLA on bimanual SO-101 arms; a UR5 teleoperation and LeRobot pipeline.
- **Earlier**: autonomous campus shuttle at NITK (Autoware, LIO-SAM), an Ackermann field vehicle at the ARMS Lab, IIT Bombay ([code](https://github.com/TahsinOP/eYSIP-24_Field_Exploration_ROS_Vehicles)), and a quadruped in MuJoCo and ROS 2 ([code](https://github.com/TahsinOP/Mujoco_Quadruped_ROS2_Simualation)).

### Publication

T. Khan and M. J. Thomas, "Soft autonomous mobile manipulators in agricultural automation: a review," *Industrial Robot*, vol. 53, no. 2, pp. 376–398, 2026. [doi:10.1108/IR-05-2025-0162](https://doi.org/10.1108/IR-05-2025-0162)

### Tools

ROS 2, Nav2, MoveIt, Autoware · MuJoCo, Isaac Sim, Gazebo · Open3D, OpenCV, OSQP · LeRobot · Python, C++ · NVIDIA Jetson, Raspberry Pi
