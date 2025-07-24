# **Installation and Setup Guide for Kali Linux**

## **Introduction**
Kali Linux is a Debian-based Linux distribution designed for digital forensics and penetration testing. Developed and maintained by Offensive Security, it offers a wide range of tools for ethical hacking, network security, and cybersecurity research.

---

## **System Requirements**
Before installing Kali Linux, ensure that your system meets the following minimum requirements:

- **RAM:** 2 GB minimum, 4 GB or more recommended  
- **Disk Space:** At least 20 GB of free space  
- **Processor:** Intel Core i3 or higher (64-bit preferred)  
- **USB/DVD:** For bootable media if installing on hardware

---

## **Installation Methods**
Kali Linux can be installed or run in several ways:

### 1. **Virtual Machine (Recommended for Beginners)**
- **Software Required:** [VMware Workstation Player](https://www.vmware.com/in/products/workstation-player.html) or [Oracle VM VirtualBox](https://www.virtualbox.org/)
- **Steps:**
  1. Download the Kali Linux ISO or pre-built VM image from the [official website](https://www.kali.org/get-kali/).
  2. Import the image or create a new VM using the ISO.
  3. Allocate required resources (RAM, CPU, Storage).
  4. Boot the VM and follow the on-screen installation prompts.

### 2. **Dual Boot Installation**
- Use this method to install Kali alongside an existing operating system (e.g., Windows).
- **Warning:** This may overwrite your data if done incorrectly.
- **Tools Required:** [Rufus](https://rufus.ie/en/) to create a bootable USB.
- **Steps:**
  1. Download the ISO file.
  2. Create a bootable USB using Rufus.
  3. Boot into BIOS and change the boot order.
  4. Boot from USB and follow the installation wizard.
  5. Create partitions and complete the setup.

### 3. **Live Boot (Without Installation)**
- Enables users to run Kali Linux directly from a USB without installing.
- Useful for quick access or testing.
- Create a bootable USB and choose **"Live"** from the boot menu.

---

## **Post-Installation Steps**
After installation:

- Update package repositories:
  ```bash
  sudo apt update && sudo apt upgrade
