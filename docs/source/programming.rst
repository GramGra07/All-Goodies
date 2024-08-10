Programming
################################################################################

.. note::

   This project is under active development!

This page contains resources for many topics regarding programming in FTC. They are separated by category, use the navigation panel on the left to find what you need!

General Resources
********************************************************************************

The resources below each cover a wide range of topics.

* `FTC Docs - Programming Resources <https://ftc-docs.firstinspires.org/en/latest/programming_resources/index.html>`_

  * Official programming information from FTC.

* `FTC SDK Repository <https://github.com/FIRST-Tech-Challenge/FtcRobotController/>`_

  * Official repository for the FTC Robot Controller app. Teams using Android Studio should fork this repo for development.

* `Game Manual Zero (GM0) - Software <https://gm0.org/en/latest/docs/software/index.html>`_

  * Programming information and tutorials from GM0

* `Westside Robotics <https://github.com/WestsideRobotics?tab=repositories>`_

  * Information on various programming topics, which are split into separate repositories. Click the Wiki tab in each repo for the information.

* `Code Training Module - Graden <https://gentrified-apps.gitbook.io/whs-ftc-code_training_module>`_ 
  
  * A great way built by our own Graden to teach teams how to get started on Android Studio! 

* `FTC Simulator - <https://ftcsim.org/>`_ 

  * FTC simulator to be able to learn and test and drive code! Amazing resource 

.. TODO - Are these relevant to include in this section?
.. * `ACME Robotics <https://github.com/acmerobotics>`_

..   * FTC Team #8367, who have created a number of tools and resources for FTC teams.

.. * `OpenFTC <https://github.com/OpenFTC>`_

..   * A group who make tools and resources for FTC teams.

Programming Tools
********************************************************************************

FTC has 3 main programming tools for teams: Blocks, OnBot Java, and Android Studio. Resources for each have been separated below.

Blocks
================================================================================

Blocks is a visual programming interface that runs in a web browser. It is targetted towards rookies who prefer to create code visually.

* `FTC Docs - Blocks Tutorial <https://ftc-docs.firstinspires.org/en/latest/programming_resources/blocks/Blocks-Tutorial.html>`_

  * Official Blocks tutorial from FTC.

* `Blocks YouTube Tutorial Playlist  <https://www.youtube.com/playlist?list=PLEuGrYl8iBm4A4yrRcatGcK7q0od0LYov>`_

  * Official Blocks video tutorials from FTC.

OnBot Java
================================================================================

OnBot Java is a text-based programming interface that runs in a web browser.  It is targetted towards rookies who prefer to create code using Java.

* `FTC Docs - OnBot Java Tutorial <https://ftc-docs.firstinspires.org/en/latest/programming_resources/onbot_java/OnBot-Java-Tutorial.html>`_

  * Official OnBot Java tutorial from FTC.

* `FTC SDK - Java Example OpModes <https://github.com/FIRST-Tech-Challenge/FtcRobotController/tree/master/FtcRobotController/src/main/java/org/firstinspires/ftc/robotcontroller/external/samples>`_

  * Official example OpModes from FTC.

Android Studio
================================================================================

`Android Studio <https://developer.android.com/studio>`_ is an integrated development environment (IDE) that runs on a computer. It is targetted towards those who prefer to create code using Java, and benefit from the advanced features offered by a professional IDE.

* `FTC Docs - Android Studio Tutorial <https://ftc-docs.firstinspires.org/en/latest/programming_resources/android_studio_java/Android-Studio-Tutorial.html>`_

  * Official Android Studio tutorial from FTC.

* `FTC SDK - Java Example OpModes <https://github.com/FIRST-Tech-Challenge/FtcRobotController/tree/master/FtcRobotController/src/main/java/org/firstinspires/ftc/robotcontroller/external/samples>`_

  * Official example OpModes from FTC.

Control System
********************************************************************************

Resources for various core components of the Control System have been separated below.

Telemetry
================================================================================

Telemetry is used to send information from the Robot Controller to the Driver Station.

* `GM0 - Using Telemetry <https://gm0.org/en/latest/docs/software/tutorials/using-telemetry.html>`_

  * Information from GM0 about telemtry.

Gamepads
================================================================================

Gamepads are controllers that plug into the Driver Station, and are typically used to control the robot during TeleOp.

* `GM0 - Gamepad Usage <https://gm0.org/en/latest/docs/software/tutorials/gamepad.html>`_

  * Information from GM0 about gamepads.

Motors
================================================================================

Motors are electromechanical devices that spin when powered. They're typically used to drive wheels or move actuators.

* FTC Docs - Motor Tutorials (`Blocks <https://ftc-docs.firstinspires.org/en/latest/programming_resources/tutorial_specific/blocks/creating_op_modes/Writing-an-Op-Mode-with-FTC-Blocks.html#controlling-a-dc-motor>`_) (`OnBot Java <https://ftc-docs.firstinspires.org/en/latest/programming_resources/tutorial_specific/onbot_java/creating_op_modes/Creating-and-Running-an-Op-Mode-%28OnBot-Java%29.html#modifying-your-op-mode-to-control-a-motor>`_) (`Android Studio <https://ftc-docs.firstinspires.org/en/latest/programming_resources/tutorial_specific/android_studio/creating_op_modes/Creating-and-Running-an-Op-Mode-%28Android-Studio%29.html#modifying-your-op-mode-to-control-a-motor>`_)

  * Official information from FTC about motors.

* `GM0 - DC Motors <https://gm0.org/en/latest/docs/software/getting-started/common-hardware-components.html#dc-motor>`_

  * Information from GM0 about motors.

Servos
================================================================================

Servos are electromechanical devices that spin when powered. In contrast to motors, they usually have positional feedback control built-in, and are typically used for smaller actuators.

* FTC Docs - Servo Tutorials (`Blocks <https://ftc-docs.firstinspires.org/en/latest/programming_resources/tutorial_specific/blocks/controlling_a_servo/Controlling-a-Servo-%28Blocks%29.html>`_) (`OnBot Java <https://ftc-docs.firstinspires.org/en/latest/programming_resources/tutorial_specific/onbot_java/controlling_a_servo/Controlling-a-Servo-%28OnBot-Java%29.html>`_) (`Android Studio <https://ftc-docs.firstinspires.org/en/latest/programming_resources/tutorial_specific/android_studio/controlling_a_servo/Controlling-a-Servo-%28Android-Studio%29.html>`_)

  * Official information from FTC about servos.

* `GM0 - Servos <https://gm0.org/en/latest/docs/software/getting-started/common-hardware-components.html#servo>`_

  * Information from GM0 about servos.

Sensors
********************************************************************************

Sensors are devices that measure physical properties of an environment. Resources for various sensor types have been separated below.

Encoders
================================================================================

* `GM0 - Encoders <https://gm0.org/en/latest/docs/software/getting-started/common-hardware-components.html#encoders>`_

  * Information from GM0 about encoders.

IMU
================================================================================

Inertial measurement units (IMU) are sensors that measure motion. They typically (but not always) include an accelerometer, gyroscope, and magnetometer. The Control Hubs (and older Expansion Hubs) have IMUs built-in

* `FTC Docs - Universal IMU Interface <https://ftc-docs.firstinspires.org/en/latest/programming_resources/imu/imu.html>`_

  * Official information from FTC about IMUs.

.. TODO - Find resources for these
.. Touch Sensors and Switches
.. ================================================================================

.. Touch sensors and switches are sensors that simply close a circuit when pressed.

.. Light and Color Sensors
.. ================================================================================

.. Light sensors measure the amount of light hitting them. Color sensors include mulitple light sensors that separate the light by color.

Vision
********************************************************************************

Cameras may be attached to robots for more advanced sensing capabilities. General vision resources are linked below, followed by resources for specific vision  tools.

.. warning:: 
  The 2024-2025 season has a lot of changes to vision! It appears that Vuforia and TensorFlow has been removed, and is effectively replaced by EasyOpenCV and AprilTags. The resources below all contain current information, but other resources you find may be outdated or incorrect!

* `FTC Docs - VisionPortal Overview <https://ftc-docs.firstinspires.org/en/latest/apriltag/vision_portal/visionportal_overview/visionportal-overview.html>`_

  * Official information from FTC about vision.

* `Vision Processing with SDK v8.2+ <https://docs.google.com/presentation/d/1KKlYTDN4WyL9vDXlfunLhxbBkZV-hXTvc2ahiO8EnWc/edit?usp=sharing>`_

  * Presentation by Dryw Wade on vision processing with the latest updates for the CENTERSTAGE season.

* `LimeLight! <https://limelightvision.io/>`_
  
  * Limelight is a plug-and-play smart camera purpose-built for the FIRST. No experience is required - Limelight is easy enough for teams with no vision experience or expert mentors, and powerful enough for experienced teams who need a reliable, competition-ready vision solution.


.. TODO - Add back once updated with latest vision updates: https://github.com/gamemanual0/gm0/issues/370
.. * `Game Manual Zero <https://gm0.org/en/latest/docs/software/tutorials/vision.html>`_

AprilTags
================================================================================

`AprilTags <https://april.eecs.umich.edu/software/apriltag>`_ are images that can be used for identificaiton and navigation. Software on the Robot Controller automatically identifies the AprilTags, and provides information about them.

* `FTC Docs - AprilTag Introduction <https://ftc-docs.firstinspires.org/en/latest/apriltag/vision_portal/apriltag_intro/apriltag-intro.html>`_

  * Official information from FTC about AprilTags.

OpenCV
================================================================================

`OpenCV <https://opencv.org/>`_ is a software library used for processing images.

* `EasyOpenCV <https://github.com/OpenFTC/EasyOpenCV>`_

  * An implementation of OpenCV for FTC created by OpenFTC. It's included in the official SDK (v8.2 and later), so there's no need to install it separately. The ReadMe file contains links to documentation on how to use it.

.. TODO - check whether this is still relevant
.. * `SkyStone Guide <https://gist.github.com/oakrc/12a7b5223df0cb55d7c1288ce96a6ab7>`_

Camera Controls
================================================================================

Cameras usually include various controls, such as gain and exposure. The resources below include information on how to use these controls.

* `FTC Docs - VisionPortal Camera Controls <https://ftc-docs.firstinspires.org/en/latest/apriltag/vision_portal/visionportal_camera_controls/visionportal-camera-controls.html>`_

  * Official information from FTC about camera controls.

.. TODO - check whether this is still relevant
.. * `Westside Robotics <https://github.com/WestsideRobotics/FTC-Webcam/wiki>`_

Other Topics
********************************************************************************

The resources below are for various topics that don't fit into any of the above categories.

GitHub
================================================================================

GitHub is a website for storing and managing projects using Git, an industry standard version control tool.

* `FTC Docs - Fork and Clone from GitHub <https://ftc-docs.firstinspires.org/en/latest/programming_resources/tutorial_specific/android_studio/fork_and_clone_github_repository/Fork-and-Clone-From-GitHub.html>`_

  * Official GitHub tutorial from FTC.

* `GitHub for FTC <https://docs.google.com/presentation/d/11RdAygfw98YmKc6gS-EA5yM0k_ny_Q1GNnq1rbWOgJo/edit?usp=sharing>`_

  * Presentation by Dryw Wade on how to use GitHub, tailored towards FTC teams.

Dashboard
================================================================================

Dashboards are applications that can be used to monitor and control robots from a computer.

* `FTC Dashboard <https://acmerobotics.github.io/ftc-dashboard/>`_

  * A dashboard created by ACME Robotics. Major features include: dynamically changing variables; exporting telemetry to CSV files; plotting telemtry values on graphs; plotting robot location on field graphics; camera streaming; limited OpMode controls and gamepad support.

Odometry, Control Theory, and Motion Planning
================================================================================

`Odometry <https://en.wikipedia.org/wiki/Odometry>`_ is using sensor data to estimate the location of a robot. `Control theory <https://en.wikipedia.org/wiki/Control_theory>`_ is using motors and other actuators to control the location of a robot. `Motion planning <https://en.wikipedia.org/wiki/Motion_planning>`_ is generating a path for a robot to follow. These 3 concepts are often used together to navigate a robot through the field.

* `Game Manual Zero - Odometry <https://gm0.org/en/latest/docs/software/concepts/odometry.html>`_

  * Information from GM0 about odometry.

* `Game Manual Zero - Control Loops <https://gm0.org/en/latest/docs/software/concepts/control-loops.html>`_

  * Information from GM0 about control theory.

* `CTRL ALT FTC <https://www.ctrlaltftc.com/>`_

  * Information from CTRL ALT FTC about control theory.

* `Controls Engineering in FRC <https://file.tavsys.net/control/controls-engineering-in-frc.pdf>`_

  * A control theory textbook written by Tyler Veness. "Graduate-level control theory for high schoolers". The title says FRC, but it's still very relevant for FTC.

* `Road Runner <https://learnroadrunner.com/>`_

  * A software library created by ACME Robotics for FTC teams that implements odometry, control theory, and motion planning all in one package. It is typically used for navigation around the field during autonomous.

Optical Tracking
********************************************************************************
* New Module thanks to Dryw! For a new range of sensors

* `SparkFun Optical Tracking - Thanks Dryw! <https://www.sparkfun.com/products/24904/>`_

  * Empowers you to elevate your robot's navigation capabilities with exceptional precision and streamlined integration. This compact, all-in-one sensor leverages the power of the PAA5160E1 chip from PixArt Imaging Inc., delivering accurate dual-axis motion data across various hard floor surfaces. But that's not all! This sensor boasts a powerful built-in 6-axis Inertial Measurement Unit (IMU) and an onboard microcontroller that performs real-time sensor fusion and tracking algorithms

Power Monitoring
================================================================================

The Rev Control/Expansion Hubs contains several power monitoring features, such as battery voltage and current consumption. The resources below provide information on how to use these features.

* `Westside Robotics - Power Monitoring <https://github.com/WestsideRobotics/FTC-Power-Monitoring/wiki>`_

  * Information from Westside Robotics about power monitoring with the Rev Control/Expansion Hubs.
