## 👋 DG5F-S

<p align="center">
  <img src="images/dg5fs.gif" width="1200" alt="DG5F-S Demo">
  <img src="images/dg5fs_w_15dof.png" width="1200" alt="DG5F-S with DG5F-S-15DOF">
</p>

> **⚠️ Notice**
> Please note that the detailed parameters of the currently uploaded models are subject to change in future updates.

This directory contains the 3D models and simulation configuration files for the **DG5F-S** and **DG5F-S-15DOF**. We provide various formats for both left and right hands, with variations including or excluding the base mount (`_w_mount`).

### 📁 Directory Structure & Supported Formats

#### 1. Meshes (`.stl`, `.dae`)
3D mesh files for visual rendering and collision detection.
* `meshes/dg5fs_left/*.stl, *.dae`
* `meshes/dg5fs_right/*.stl, *.dae`
* `meshes/dg5fs_15dof_left/*.stl, *.dae`
* `meshes/dg5fs_15dof_right/*.stl, *.dae`

#### 2. URDF (`.urdf`)
Standard robot model files for ROS and general-purpose robotics simulators.
* `dg5fs_left.urdf`
* `dg5fs_left_w_mount.urdf`
* `dg5fs_right.urdf`
* `dg5fs_right_w_mount.urdf`
* `dg5fs_15dof_left.urdf`
* `dg5fs_15dof_left_w_mount.urdf`
* `dg5fs_15dof_right.urdf`
* `dg5fs_15dof_right_w_mount.urdf`

#### 3. MJCF (`.xml`)
Model files optimized for the MuJoCo physics engine.
* `dg5fs_left.xml`
* `dg5fs_left_w_mount.xml`
* `dg5fs_right.xml`
* `dg5fs_right_w_mount.xml`
* `dg5fs_15dof_left.xml`
* `dg5fs_15dof_left_w_mount.xml`
* `dg5fs_15dof_right.xml`
* `dg5fs_15dof_right_w_mount.xml`

#### 4. USD (`.usd`)
Ready-to-use USD files specifically configured for NVIDIA Isaac Sim and Isaac Lab environments.
* `usd/dg5fs_left/dg5fs_left.usd`
* `usd/dg5fs_left_w_mount/dg5fs_left.usd`
* `usd/dg5fs_right/dg5fs_right.usd`
* `usd/dg5fs_right_w_mount/dg5fs_right.usd`
* `usd/dg5fs_15dof_left/dg5fs_15dof_left.usd`
* `usd/dg5fs_15dof_left_w_mount/dg5fs_15dof_left.usd`
* `usd/dg5fs_15dof_right/dg5fs_15dof_right.usd`
* `usd/dg5fs_15dof_right_w_mount/dg5fs_15dof_right.usd`
