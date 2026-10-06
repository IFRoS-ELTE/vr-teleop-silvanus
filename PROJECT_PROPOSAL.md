# Project Proposal: VR Teleoperation and Data Collection

**Authors:** Levente Vajda | Matyas Patacsi

**Objective:** Set up a VR teleoperation and data recording system for the Silvanus robot so we can collect data for VLA models.

## Milestones

* **Lab Setup:** Prepare the physical lab space and computers for the project.
  * **PC Setup:** Physically install and wire the two workstation computers in the lab.
  * **Robot Hardware:** Install the VLA base camera onto the Silvanus robot.
  * **Networking:** Set up a fast local network so the PCs and the Silvanus robot can talk to each other (test Etherenet, Wifi, and 4G).
    * **4G Setup:** *(Optional)* Silvanus could use celullar connection instead of Wifi. Set it up and document it for other teams to use.
  * **Software Install:** Install Ubuntu, ROS 2, etc on the new computers.
* **VR setup:** Acquire the hardware and connect it to the robot's network.
  * **Requirements & Selection:** Figure out the technical requirements and choose the right VR headset for the project (source it from either another dept. or new).
  * **ROS 2:** Connect the VR headset to the ROS 2 system so we can read the controller positions and buttons.
* **Robot Setup:** Figure out what hardware requirements are posted at Silvanus and implement them.
  * Try not to break ROS1 on Silvanuss
* **Teleoperation Setup:** Make the robot arm and base follow the human's hand movements and inputs from the VR controllers.
* **VLA:** Study Vision-Language-Action (VLA) models to understand how they work and what is needed in this stage of the work.
* **Data Recording:** Set up the required measurment / data collection process.

## List of Hardware needs:
* High-end PC (4070ti super or above)
* Wifi card / Wifi dongle
* VR camera + Controller
* Camera to mount on Silvanus (Base Camera)
* Long Ethernet Cable
