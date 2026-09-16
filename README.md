# Keerthana Krishnamurthi

### Embedded Systems & Robotics Engineer

VIT Vellore · Electronics & Communication Engineering

---

I build across the full hardware-software stack — from multi-layer PCB design and low-level firmware to ROS 2 control architectures.

---

### Technical Focus

* **Hardware & Firmware:** Schematic capture, multi-layer board layout, motor drivers, ESP32, FreeRTOS, and protocols (UART, SPI, I2C, PWM).
* **Control & Actuation:** Closed-loop PID control, encoder feedback, stepper motor timing optimization, and driver integration.
* **Robotics Stack:** ROS 2 (Nav2, SLAM Toolbox), Gazebo simulation, and multi-MCU serial telemetry pipelines.

---

### Key Repositories

- **[robArm_ros2](./robArm_ros2) / [robArm_esp32](./robArm_esp32)** — Complete hardware-software architecture developed for Team Vyadh's 2026 Mars Rover arm (former team member). `robArm_ros2` houses high-level ROS 2 kinematics packages, while `robArm_esp32` manages low-level MCU firmware, joint actuation, multi-sensor/driver PCB integration, and serial telemetry.
- **[autonomous_rover](./autonomous_rover)** — Autonomous differential-drive mobile robot navigation stack. SLAM Toolbox integration complete; currently implementing Nav2 in simulation prior to hardware deployment with ToF sensors.
- **[babyArm](./babyArm)** — Vision-controlled 4-DOF robotic arm featuring joint actuation, closed-loop feedback experiments, and multi-MCU serial communication over UART.
- **[PyroBot](./PyroBot)** — Legacy robotics project implementing differential-drive traversal, flame sensor trigger detection, and 2D grid mapping to a web server.
