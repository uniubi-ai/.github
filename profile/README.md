<p align="center">
  <img src="./assets/uniubi-ai-standard-logo-horizontal-black.png" alt="UniUbi AI" width="560">
</p>

<h3 align="center">Open robotics software for UniUbi robots</h3>

<p align="center">
  SDKs, ROS2 integration, robot models, x86 simulation, examples, and learning workflows for building with UniUbi quadruped robots.
</p>

<p align="center">
  <a href="https://github.com/uniubi-ai/uniubi-docs">Docs</a>
  ·
  <a href="https://github.com/uniubi-ai/uniubi_robot_sdk">C++ SDK</a>
  ·
  <a href="https://github.com/uniubi-ai/uniubi_robot_sdk_py">Python SDK</a>
  ·
  <a href="https://github.com/uniubi-ai/uniubi_robot_mock">Robot Mock</a>
  ·
  <a href="https://github.com/uniubi-ai/uniubi_rl_lab">RL Lab</a>
</p>

<p align="center">
  <a href="https://github.com/uniubi-ai?tab=repositories">
    <img alt="Core repositories" src="https://img.shields.io/badge/core%20repositories-10-111111?style=flat-square">
  </a>
  <a href="https://github.com/uniubi-ai/uniubi_robot_sdk">
    <img alt="C++ SDK" src="https://img.shields.io/badge/sdk-C%2B%2B-00599C?style=flat-square">
  </a>
  <a href="https://github.com/uniubi-ai/uniubi_robot_sdk_py">
    <img alt="Python SDK" src="https://img.shields.io/badge/sdk-Python-3776AB?style=flat-square">
  </a>
  <a href="https://github.com/uniubi-ai/uniubi_ros2">
    <img alt="ROS2" src="https://img.shields.io/badge/ROS2-supported-22314E?style=flat-square">
  </a>
</p>

## About UniUbi AI

UniUbi AI is building an open developer ecosystem for quadruped robots. The organization focuses on practical robot software: stable message definitions, real-robot SDKs, ROS2 packages, robot descriptions, simulation and mock environments, runnable examples, and reinforcement learning workflows.

The goal is to make robot development easier to start, safer to test, and clearer to extend from first connection to real-world deployment.

## Documentation Model

[`uniubi-docs`](https://github.com/uniubi-ai/uniubi-docs) is the documentation hub for cross-repository guides, recommended paths, safety notes, support matrices, and troubleshooting.

Each code repository keeps version-aligned local documentation: installation or build steps, the smallest runnable example, compatibility notes, and repository-specific safety limits. The hub helps developers choose the right path; each repository README helps them run the checked-out version reliably.

## Open Source Projects

<table>
  <thead>
    <tr>
      <th>Area</th>
      <th>Repository</th>
      <th>Purpose</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td rowspan="2"><strong>Getting Started</strong></td>
      <td><a href="https://github.com/uniubi-ai/uniubi-docs"><code>uniubi-docs</code></a></td>
      <td>Developer documentation, quick starts, support matrix, safety notes, and troubleshooting.</td>
    </tr>
    <tr>
      <td><a href="https://github.com/uniubi-ai/uniubi_examples"><code>uniubi_examples</code></a></td>
      <td>Minimal examples and cookbook-style workflows for first-time developers.</td>
    </tr>
    <tr>
      <td rowspan="3"><strong>Robot SDK</strong></td>
      <td><a href="https://github.com/uniubi-ai/uniubi_robot_msgs"><code>uniubi_robot_msgs</code></a></td>
      <td>Common DDS, IDL, ROS2, and schema definitions shared across the ecosystem.</td>
    </tr>
    <tr>
      <td><a href="https://github.com/uniubi-ai/uniubi_robot_sdk"><code>uniubi_robot_sdk</code></a></td>
      <td>C++ SDK for communicating with and controlling UniUbi robots in real environments.</td>
    </tr>
    <tr>
      <td><a href="https://github.com/uniubi-ai/uniubi_robot_sdk_py"><code>uniubi_robot_sdk_py</code></a></td>
      <td>Python SDK for rapid prototyping, data collection, and AI workflows.</td>
    </tr>
    <tr>
      <td><strong>ROS2</strong></td>
      <td><a href="https://github.com/uniubi-ai/uniubi_ros2"><code>uniubi_ros2</code></a></td>
      <td>ROS2 support packages, drivers, bringup, RViz, bag tools, and example nodes.</td>
    </tr>
    <tr>
      <td><strong>Robot Models</strong></td>
      <td><a href="https://github.com/uniubi-ai/uniubi_robot_description"><code>uniubi_robot_description</code></a></td>
      <td>URDF, MJCF, USD, meshes, and visualization assets for UniUbi robots.</td>
    </tr>
    <tr>
      <td><strong>Simulation</strong></td>
      <td><a href="https://github.com/uniubi-ai/uniubi_robot_mock"><code>uniubi_robot_mock</code></a></td>
      <td>x86 robot simulation and mock server for testing SDK integrations without hardware, including high-level and low-level modes.</td>
    </tr>
    <tr>
      <td><strong>Learning</strong></td>
      <td><a href="https://github.com/uniubi-ai/uniubi_rl_lab"><code>uniubi_rl_lab</code></a></td>
      <td>Reinforcement learning environments, training workflows, policy export, and sim-to-real checks.</td>
    </tr>
  </tbody>
</table>

## Recommended Path

| Step | Repository | What to do |
| --- | --- | --- |
| 1 | [`uniubi-docs`](https://github.com/uniubi-ai/uniubi-docs) | Read the quick start, support matrix, and safety notes. |
| 2 | [`uniubi_robot_msgs`](https://github.com/uniubi-ai/uniubi_robot_msgs) | Understand shared message, IDL, ROS2, and schema definitions. |
| 3 | [`uniubi_robot_sdk`](https://github.com/uniubi-ai/uniubi_robot_sdk) or [`uniubi_robot_sdk_py`](https://github.com/uniubi-ai/uniubi_robot_sdk_py) | Choose the C++ or Python SDK for your application. |
| 4 | [`uniubi_robot_mock`](https://github.com/uniubi-ai/uniubi_robot_mock) | Test high-level and low-level control flows on x86 before touching hardware. |
| 5 | [`uniubi_examples`](https://github.com/uniubi-ai/uniubi_examples) | Run focused examples and adapt them to your workflow. |
| 6 | [`uniubi_ros2`](https://github.com/uniubi-ai/uniubi_ros2) or [`uniubi_rl_lab`](https://github.com/uniubi-ai/uniubi_rl_lab) | Move into ROS2 integration or learning workflows when ready. |

## Safety

Robot software can command real motion. Start with mock or simulation workflows, read repository-specific safety notes, and keep emergency stop access available before running commands on hardware.

## Community

Use GitHub Issues for bug reports, feature requests, and project discussions. Please report security-sensitive issues privately according to each repository's security policy.
