# Samba Active Directory Domain Controller Lab
This project automates the deployment of a **Samba Active Directory Domain Controller (AD DC)** on a Linux environment using **Vagrant** and **Ansible**. It is designed for students and IT professionals to practice network identity management.

## 🏗️ Project Architecture
* **Identity Provider:** Samba 4 (Active Directory Mode)
* **Operating System:** Ubuntu 22.04 / Debian 12 (via Vagrant)
* **Automation:** Ansible (Provisioning and DNS Configuration)
* **Key Features:** * Automated Domain Provisioning (FSMO Roles)
    * Integrated DNS Management
    * Kerberos Authentication Setup

## 🚀 How to Deploy
1. **Prerequisites:** Install [Vagrant](https://www.vagrantup.com/) and [VirtualBox](https://www.virtualbox.org/).
2. **Clone the Repo:**
   ```bash
   git clone [https://github.com/muhammadkamrankabeer-oss/samba-ad-lab.git](https://github.com/muhammadkamrankabeer-oss/samba-ad-lab.git)
   cd samba-ad-lab
