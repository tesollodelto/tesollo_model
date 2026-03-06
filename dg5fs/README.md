## 🦾 DG5F-S

> **⚠️ Notice**
> Please note that the detailed parameters of the currently uploaded models are subject to change in future updates.

This directory contains the 3D models and simulation configuration files for the **DG5F-S**. We provide various formats for both left and right hands, with variations including or excluding the base mount (`w_mount`).

### 📁 Directory Structure & Supported Formats

#### 1. Meshes (`.stl`, `.dae`)
3D mesh files for visual rendering and collision detection.
* `dg5fs/meshes/dg5fs_left/*.stl, *.dae`
* `dg5fs/meshes/dg5fs_right/*.stl, *.dae`

#### 2. URDF (`.urdf`)
Standard robot model files for ROS and general-purpose robotics simulators.
* `dg5fs/dg5fs_left.urdf`
* `dg5fs/dg5fs_left_w_mount.urdf`
* `dg5fs/dg5fs_right.urdf`
* `dg5fs/dg5fs_right_w_mount.urdf`

#### 3. MJCF (`.xml`)
Model files optimized for the MuJoCo physics engine.
* `dg5fs/dg5fs_left.xml`
* `dg5fs/dg5fs_left_w_mount.xml`
* `dg5fs/dg5fs_right.xml`
* `dg5fs/dg5fs_right_w_mount.xml`

#### 4. USD (`.usd`)
Ready-to-use USD files specifically configured for NVIDIA Isaac Sim and Isaac Lab environments.
* `dg5fs/usd/dg5fs_left/dg5fs_left.usd`
* `dg5fs/usd/dg5fs_left_w_mount/dg5fs_left.usd`
* `dg5fs/usd/dg5fs_right/dg5fs_right.usd`
* `dg5fs/usd/dg5fs_right_w_mount/dg5fs_right.usd`
