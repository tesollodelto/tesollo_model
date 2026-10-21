# TESOLLO Robot Models – URDF, USD, XML

Robot model resources for TESOLLO robotic grippers and dexterous robotic hands.

This repository provides robot model assets, including URDF, USD, and XML formats where available, to support robotics simulation, visualization, motion planning, and system integration.

## Repository Structure

The repository is organized by product series, containing model assets and physics configurations for each robotic gripper and hand.

| Model | Degrees of Freedom | Directory |
|---|---|---|
| DG-1F | 3 DoF | [dg1fm](./dg1fm) |
| DG-2F | 6 DoF | [dg2fm](./dg2fm) |
| DG-3F-M | 12 DoF | [dg3fm](./dg3fm) |
| DG-4F | 18 DoF | [dg4f](./dg4f) |
| DG-5F-M | 20 DoF | [dg5f](./dg5f) |
| DG-5F-S | 20 DoF / 15 DoF | [dg5fs](./dg5fs) |

## Applications

These robot models can be used for a variety of robotics development and research applications, including:

- **Robot Simulation:** Robot modeling and simulation environment setup.
- **Motion Planning:** Kinematic modeling and motion planning.
- **ROS 2 Integration:** Integration with ROS 2-based robotic systems.
- **Visualization:** Robot model visualization and configuration.
- **System Integration:** Integration with robotic arms and manipulation platforms.
- **Robotics Research:** Research and development in robotic manipulation and dexterous hands.

## Model Formats

Model assets may include the following formats, depending on the product:

- **URDF:** Robot descriptions for ROS-based applications.
- **USD:** Scene and robot model assets for compatible simulation environments.
- **XML:** Model configuration files for supported robotics frameworks.

Available formats and configurations may vary by model. Please refer to each product directory for details.

## Documentation & Resources

For additional documentation, software packages, and integration guides:

- [ROS 2 Integration Guide](https://tesollodelto.github.io/tesollo_ros2/)
- [ROS 2 Drivers & Packages](https://github.com/tesollodelto/tesollo_ros2)
- [Downloads & Developer Resources](https://www.tesollo.com/support/download)
- [TESOLLO Official Website](https://www.tesollo.com)

## License

This repository is distributed under the terms of the [BSD 3-Clause License](./LICENSE).

## Support

For technical inquiries and support:

**Email:** support@tesollo.com

**Website:** https://www.tesollo.com
