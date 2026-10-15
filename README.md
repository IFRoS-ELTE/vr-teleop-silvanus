# Teleoperation of Silvanus

VR teleoperation for the Silvanus robot.

*Read the full [Project Proposal](PROJECT_PROPOSAL.md) here.*

---

## Milestones Tracker
- [ ] Lab Setup
- [ ] VR setup
- [ ] Robot Setup
- [ ] Teleoperation Setup
- [ ] VLA
- [ ] Data Recording

---

## Progress Log

### Lab Setup
* Bios and Windows update on the Lenovo PC - 10.06
* Installed Ubuntu 24.04 on M90s-gen6 - 10.06
* Testing 2 "funny" SSDs if they can be used as extra storage on Silvanus. (SSDs claim larger size tha what they actually have) - 1st done on 10.07
* Installed ROS2, Gazebo, Tailscale, Docker utilities etc. Set up of SSH. Tested ROS2 and Gazebo install. - 10.07.
* 2nd SSD testing - 10.08.
* Setting up advanced development tools; remote shut down and boot - 10.09.
* (Postponed the multi-user setup of the PC as others will not be using it this semester.) - 10.09.
*  SSH hardened: key-only login, password login disabled. - 10.13.
* Remote desktop over RDP: GNOME Remote Login and Desktop Sharing. Made .rdp profiles for laptop and external monitor, fixed the certificate and session-handover prompts. - 10.14.
* Firewall (ufw): remote desktop ports only reachable over Tailscale. Disabled sleep/suspend so the PC stays reachable 24/7. - 10.14.
* Remote Login account for a colleague. Fixed GPU access for remote sessions (`render` group), so Gazebo renders on the GPU instead of the CPU. - 10.15.
* Added a separate backup admin account. Renamed the main user `ifros-student` → `matyasp` (display name kept, old home path linked). - 10.15.

#### TODO
* Tailscale only authentication for SSH access. No Password or SSH key option.
* Disable Tailscale key expiry.
* BIOS: power on after power loss.
* Multi-user setup (when needed).
* Remote access to the Windows side for the professor.

### VR setup
* Ocolus Rift pick up - 10.14. 
* 

### Robot Setup
* 
* 

### Teleoperation Setup
* 
* 

### VLA
* Collected material (papers etc) on VLAs and other topics related to the project
* 

### Data Recording
* 
* 

---
