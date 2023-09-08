Electronics
################################################################################

.. note::

   This project is under active development!

This page contains resources for many topics regarding electronics and the control system in FTC. They are separated by category, use the navigation panel on the left to find what you need!

General Resources
********************************************************************************

The resources below each cover a wide range of topics related to electronics and the control system.

* `FTC Docs - Control System Introduction <https://ftc-docs.firstinspires.org/en/latest/programming_resources/shared/control_system_intro/The-FTC-Control-System.html>`_

  * Official information from FTC regarding the control system and various electrical components.

* `Game Manual 1 <https://www.firstinspires.org/sites/default/files/uploads/resource_library/ftc/game-manual-part-1-traditional-events.pdf>`_

  * Official rules from Game Manul 1, which outlines the rules regarding robot electronics in section 7.3.3, and the Driver Station in 7.3.4.

* `Game Manual Zero <https://gm0.org/en/latest/docs/power-and-electronics/index.html>`_

  * Electronics and wiring information from GM0.

Control System
********************************************************************************

The control system includes the core components used to control a robot. In FTC, the 2 primary components of the control system include a Robot Controller and Driver Station. These are Android devices that communicate with each other wirelessly.

* `FTC Docs - Control System Introduction <https://ftc-docs.firstinspires.org/en/latest/programming_resources/shared/control_system_intro/The-FTC-Control-System.html>`_

  * Official control system information from FTC.

* `Rev Docs <https://docs.revrobotics.com/duo-control/>`_

  * Official control system information from Rev Robotics.

* `Game Manual Zero - Control Systems <https://gm0.org/en/latest/docs/power-and-electronics/control-system.html>`_

  * Control system information from GM0.

Robot Controller
================================================================================

The Robot Controller is an Android device on the robot that runs all the team code, and interacts with all the other electronics. Rev Control Hubs and/or Expansion Hubs are the only legal components for interfacing with other electronics, in addition to an Android phone (if used).

.. warning:: 
  According to a note in `Game Manual 1 <https://www.firstinspires.org/sites/default/files/uploads/resource_library/ftc/game-manual-part-1-traditional-events.pdf>`_ (<RE06> in section 7.3.3), Android phones will no longer be legal for the 2024-2025 season; only the `Rev Control Hubs <https://www.revrobotics.com/rev-31-1595/>`_ will be legal. Teams may still use Android phones for CENTERSTAGE, but it is recommended that teams do not purchae any new Android phones since they won't be legel in the future.

* `FTC Docs - Robot Controller Overview <https://ftc-docs.firstinspires.org/en/latest/control_hard_compon/rc_components/index.html>`_

  * Official Robot Controller information from FTC.

* Rev Product Pages (`Control Hub <https://www.revrobotics.com/rev-31-1595/>`_) (`Expansion Hub <https://www.revrobotics.com/rev-31-1153/>`_)

  * Rev's product pages for their Control/Expansion Hubs. Scroll down to Documentation section for official manuals and guides from Rev.

* `Game Manual Zero - Control Systems <https://gm0.org/en/latest/docs/power-and-electronics/control-system.html>`_

  * Robot Controller information from GM0.

* `Game Manual Zero - Control System Electronics <https://gm0.org/en/latest/docs/software/adv-control-system/control-system-internals.html>`_

  * Detailed information about the Rev Control/Expansion Hub internals from GM0.

Driver Station
================================================================================

The Driver Station is an Android device that drivers use to remotely control the robot. USB gamepad controllers are connected to it for drivers to control the robot during TeleOp.

* `FTC Docs - Driver Station Overview <https://ftc-docs.firstinspires.org/en/latest/control_hard_compon/ds_components/index.html>`_

  * Official Driver Station information from FTC.

* `Rev Driver Hub Product Page <https://www.revrobotics.com/rev-31-1596/>`_

  * Rev's product page for their Driver Hubs. Scroll down to Documentation section for official manuals and guides from Rev.

* `Game Manual Zero - Driver Station Guide <https://gm0.org/en/latest/docs/power-and-electronics/driver-station-guide.html>`_

  * Driver Station information from GM0.

Rev Hardware Client
================================================================================

The Rev Hardware Client is a software tool installed onto a computer that helps with managing Robot Controllers and Driver Stations (inlcuding Android phones). It is recommended that teams use it to keep the control system software updated, since there is a minimum software version required for each season.

* `Rev Hardware Client <https://docs.revrobotics.com/rev-hardware-client/>`_

  * Official download page and documentation for the Rev Hardware Client.

Robot Power
================================================================================

* `FTC Docs - Power Distribution <https://ftc-docs.firstinspires.org/en/latest/control_hard_compon/rc_components/power_distr/power-distr.html>`_

  * Official information from FTC regarding legal robot power components (eg. batteries and switches).

.. TODO - Add resources about battery health

Hardware Configuration
================================================================================

The Robot Controller needs to know what components have been connected to which ports in order to control them correctly. This is done through a configuration process on the Driver Station.

* `FTC Docs - Configuring Your Hardware <https://ftc-docs.firstinspires.org/en/latest/hardware_and_software_configuration/configuring/index.html>`_

  * Official hardware configuration information from FTC.

Control/Expansion Hub Ports
================================================================================

The Control Hubs and Expansion Hubs include several different ports for connecting various devices.

* `Rev Docs - Port Pinouts <https://docs.revrobotics.com/duo-control/control-system-overview/port-pinouts>`_

  * Official information about Control/Expansion Hub port pinouts from Rev.

* `Rev Docs - Digital Sensors <https://docs.revrobotics.com/duo-control/sensors/digital>`_

  * Official digital port information from Rev.

* `Rev Docs - Analog Sensors <https://docs.revrobotics.com/duo-control/sensors/analog>`_

  * Official analog port information from Rev.

* `Rev Docs - I2C Sensors <https://docs.revrobotics.com/duo-control/sensors/i2c>`_

  * Official I2C port information from Rev.

* `Rev Docs - Using 3rd Party Sensors <https://docs.revrobotics.com/duo-control/sensors/5v-sensors>`_

  * Official information from Rev regarding usage of other sensors, especially those that use a different voltage. It describes the use of logic level converters to safely use 5V sensors with the 3.3V Control/Expansion Hubs.

Actuators
********************************************************************************

Actuators are devices that manipulate mechanisms and objects, with common examples including motors and servos. Resources for various actuator types have been separated below.

Motors
================================================================================

* `FTC Docs - Motors <https://ftc-docs.firstinspires.org/en/latest/control_hard_compon/rc_components/motors/motors.html>`_

  * Official motor information from FTC.

* `Game Manual Zero - Motor Guide <https://gm0.org/en/latest/docs/power-and-electronics/motor-guide/index.html>`_

  * Motor guide from GM0. Includes guide on choosing motors, information about gearboxes, recommendatiosn for wiring and mounting motors, and motor performance information.

Servos
================================================================================

* `FTC Docs - Servos <https://ftc-docs.firstinspires.org/en/latest/control_hard_compon/rc_components/servos/servos.html>`_

  * Official servo information from FTC.

* `Game Manual Zero - Servo Guide <https://gm0.org/en/latest/docs/power-and-electronics/servo-guide/index.html>`_

  * Servo guide from GM0. Includes guide on choosing servos, and recommendatiosn for best performance.

Sensors
********************************************************************************

Sensors are devices that measure physical properties of an environment, with common examples including encoders and limit switches. Resources for various sensor types have been separated below.

* `FTC Docs - Sensors <https://ftc-docs.firstinspires.org/en/latest/control_hard_compon/rc_components/sensors/sensors.html>`_

  * Official sensor information from FTC.

* `Rev Docs - Introduction to Sensors <https://docs.revrobotics.com/duo-control/sensors/intro-to-sensors>`_

  * Official sensor information from Rev.

* `Game Manual Zero - Sensor Glossary <https://gm0.org/en/latest/docs/power-and-electronics/sensor-glossary.html>`_

  * List of popular sensors from GM0.

Touch Sensors / Limit Switches
================================================================================

Touch sensors and limit switches are digital sensors that complete a circuit when closed. Typical applications include detecting when the robot has hit a wall, or detecting when an actuator has reached the end of its motion.

* `Rev Docs - Touch Sensor <https://docs.revrobotics.com/touch-sensor/>`_

  * Official information from Rev about their Touch Sensor. Information is specific to that product, but general ideas still apply to other sensors.

* `Rev Docs - Magnetic Limit Switch <https://docs.revrobotics.com/magnetic-limit-switch/>`_

  * Official information from Rev about their Magnetic Limit Switch. Information is specific to that product, but general ideas still apply to other sensors.

Potentiometers
================================================================================

Potentiometers are analog sensors that measure a fixed range of motion. They usually measure rotation, but some can also measure linear motion.

* `Rev Docs - Potentiometer <https://docs.revrobotics.com/potentiometer/>`_

  * Official information from Rev about their Potentiometer. Information is specific to that product, but general ideas still apply to other sensors.

Encoders
================================================================================

Encoders are digital sensors that measure rotation, and are often built into motors. Encoders can measure rotation continuously, there is no limit to how far they can rotate.

* `Rev Docs - Encoders <https://docs.revrobotics.com/duo-control/sensors/encoders>`_

  * Official information about encoders from Rev.

* `FTC Docs - Encoders <https://ftc-docs.firstinspires.org/en/latest/control_hard_compon/rc_components/encoders/encoders.html>`_

  * Official encoder information from FTC.

Distance Sensors
================================================================================

Distance sensors measure the distance to an object or surface in front of it. Distacne sensors typically have analog or I2C interfaces. Distances are typically measured with sound or light, both of which have their own pros and cons.

* `Rev Docs - 2m Distance Sensor <https://docs.revrobotics.com/2m-distance-sensor/>`_

  * Official information from Rev about their 2m Distance Sensor. Information is specific to that product, but general ideas still apply to other sensors.

Color / Light Sensors
================================================================================

Light sensors measure the amount of light hitting them. Color sensors are similar to light sensors, but separate colors by wavelength, and typically return RGB measurements.

* `Rev Docs - Color Sensor V3 <https://docs.revrobotics.com/color-sensor/>`_

  * Official information from Rev about their Color Sensor V3, which is also an optical distance sensor. Information is specific to that product, but general ideas still apply to other sensors.

IMUs (Inertial Measurement Units)
================================================================================

IMUs are sensors that measure motion, and typically include a 3-axis accelerometer, 3-xis gyroscope, and 3-axis magnetometer. The Control Hubs include an internal IMU, so it's uncommon to need additional IMUs.

* `Rev Docs - Control Hub IMU <https://docs.revrobotics.com/duo-control/sensors/i2c/imu>`_

  * Official wiring guide from FTC.

Cameras
================================================================================

Cameras are devices that take images, and require advanced image processing algorithms. Cameras are typically used in FTC to detect AprilTags and identify objects with TensorFlow.

* `FTC Docs - UVC Webcam <https://ftc-docs.firstinspires.org/en/latest/control_hard_compon/rc_components/uvc/uvc.html>`_

  * Official camera information from FTC.

Wiring
********************************************************************************

Electrical components are connected by wires and cables. Poor wiring practices can lead to numerous issues with robot performance and reliability.

General Wiring Guides
================================================================================

The resources below offer advice and recommendations on best practices for robot wiring.

* `Robot Wiring Guide <https://www.firstinspires.org/sites/default/files/uploads/resource_library/ftc/robot-wiring-guide.pdf>`_

  * Official wiring guide from FTC.

* `Game Manual Zero - Wiring Guide <https://gm0.org/en/latest/docs/power-and-electronics/wiring.html>`_

  * Wiring guide from GM0.

* `Robot Reliability Presentation <https://docs.google.com/presentation/d/1fNDJIuv1K3r_V4g7HSfeLnxhyyCjW_kpP241qzNwDpM/edit?usp=sharing>`_

  * Presentation made by Rami that summarizes wiring guides into a quick and easy resource

ESD (Electrostatic Discharge)
================================================================================

ESD is a spark between 2 objects. Robots can build up a charge as they drive around and discharge to other objects or robots, which can cause robots to exhibit odd behavior or stop working. ESD is more common in dry climates.

* `ESD Mitigation for FTC <https://www.firstinspires.org/sites/default/files/uploads/resource_library/ftc/analysis-esd-mitigation-echin.pdf>`_

  * Official guide for ESD mitigation
