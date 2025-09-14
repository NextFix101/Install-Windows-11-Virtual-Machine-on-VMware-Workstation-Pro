# 🖥️ Windows 11 Virtual Machine on VMware Workstation Pro

A **step-by-step guide and tutorial project** for creating a **Windows 11 Virtual Machine (VM)** using **VMware Workstation Pro**.  
This repository documents the entire process with instructions, explanations, and best practices — making it beginner-friendly yet professional enough to showcase homelab skills.

---

## 🔹 Why This Project?
As an **IT Support / System Administrator**, hands-on experience with virtualization is essential.  
This project demonstrates my ability to:
- Configure and manage **virtual machines**.
- Work with **Windows 11, VMware, TPM 2.0, and Secure Boot**.
- Write **clear, detailed technical documentation**.
- Build a **homelab environment** for training, testing, and troubleshooting.

---

## 🔹 Features of This Repository
- ✅ **Step-by-step installation guide** for Windows 11 on VMware.  
- ✅ Explanation of **TPM 2.0, Secure Boot, and encryption options**.  
- ✅ Optimized for **IT homelabs and practice environments**.  
- ✅ Includes **YouTube tutorial script** and **short-form script** for content creation.  
- ✅ **SEO-friendly documentation** to help others find and follow the guide easily.  

---

## 🔹 Prerequisites
Before setting up your VM, make sure you have:
- **VMware Workstation Pro / Player** installed.
- **Windows 11 ISO** (download from Microsoft).
- **8GB+ RAM** (16GB recommended).
- **60GB+ disk space**.
- CPU with **Intel VT-x / AMD-V enabled** in BIOS.

---

## 🔹 Step-by-Step Installation Guide

### 1. Create a New Virtual Machine
- Open VMware → **Create a New Virtual Machine** → choose **Typical**.

### 2. Select Installation Media
- Browse for your **Windows 11 ISO file**.

### 3. Enter Windows Details
- Enter product key (optional), edition, username, password.

### 4. Name & Location
- Name your VM (e.g., `Windows11-Lab`), choose storage folder.

### 5. Encryption & TPM Setup
- Required for Windows 11 installation.
- Choose **Encrypt only the files needed to support TPM** (recommended for homelab).
- Set a password and save it.
- VMware automatically enables **TPM 2.0**.

### 6. Specify Disk Size
- Set **60GB+**, store as single file (better performance).

### 7. Customize Hardware
- Memory: 8–12GB.  
- Processors: 2–4 cores.  
- Firmware: UEFI + Enable Secure Boot.  
- Network: NAT.  
- Display: Enable 3D acceleration.  

### 8. Install Windows 11
- Power on VM → follow installation wizard.

### 9. Install VMware Tools
- Go to **VM → Install VMware Tools** → install inside Windows → restart.

---

## 🔹 Best Practices
- Take **snapshots** after clean install.  
- Keep **backups** of VM folders.  
- Leave enough RAM/CPU for host OS.  
- Use VM for safe **testing, labs, troubleshooting, and coding**.  

---
