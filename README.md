# InfluenceOps: Tactical Pretexting - Student Information  

<p align="center">
  <img src="https://github.com/user-attachments/assets/8654eed4-6544-4b1b-955e-55587f261889" alt="RTVIO" width="500"/>
</p>

## **Workshop Information for InfluenceOps: Tactical Pretexting**

Welcome to the InfluenceOps Student VM — a lightweight Ubuntu-based virtual machine preloaded with everything you need for hands-on exercises in OSINT, persona building, and scenario development as part of the **InfluenceOps: Tactical Pretexting** workshop.

All tools are open source and pre-installed. The VM has been optimized for low-resource environments and includes Obsidian for structured note-taking with workshop-specific templates.

---

## VM Overview

![image](https://github.com/user-attachments/assets/8a7ac5f4-513f-407f-879c-f8568a72479a)

---

### ⚠️ **VM Notice for Class**

There is currently a **temporary error with the VMware version** of the virtual machine.

✅ **Fix**:  
Download the **VirtualBox version** of the VM instead and import the **`.ovf` file** directly into VMware.

![image](https://github.com/user-attachments/assets/37a4edab-8dc0-4147-8e8a-9ebe3f5162a2)


We’ve tested this workaround and it **loads and runs successfully** in VMware.

---


- **OS:** Ubuntu 22.04 LTS (Minimal Install)
- **Preinstalled Tools:**
  - [The Ultimate OSINT Collection](https://start.me/p/DPYPMz/the-ultimate-osint-collection) – Super awesome collection of OSINT tools and other information! Thank you Hatless1der!
  - [Visual Studio Code (VSCode](https://code.visualstudio.com/) – For coding scripts
  - Search Engine Dorks Cheat sheet
  - `whois`, `dig` – Domain investigation tools
  - [Obsidian](https://obsidian.md/) – Note-taking and pretext template management
 
- **Workshop Materials:**
  - OSINT, Persona, and Scenario templates (Markdown in Obsidian)
  - Slide deck (PDF) (In Obsidian)
  - Cheat sheets

---

## Login Credentials

- **Username:** `student`  
- **Password:** `pass123`  

You will be automatically logged in as the `student` user.

---

## Vault Location (Obsidian)

When you open Obsidian, use the preloaded vault located at:

```
/home/student/Documents/Influence Ops/
```

This contains:
- Templates for OSINT, Personas, Scenarios, Reports, and Feedback
- Pre-written examples to guide your work
- A structured folder system to organize your research and activities

---

## Download 

 [Download VM Images Here](https://drive.proton.me/urls/J25YDT3SH0#zVwc7HcUoAQw)

 It is highly advised you use [7Zip](https://www.7-zip.org/) (Free) to unzip your files. 

 (Optional) Verify the integrity of your download before importing.

### **VirtualBox (.ovf)**

- **Filename:** `InfluenceOps_VM_VirtualBox.7z`
- **SHA256:** 4e807cd44db6095d20274c47c29f8e6aecdbc9763f9d3e6e84bc8fc3d02397e8  
  ```
  certutil -hashfile "C:\path\to\your\file.txt" SHA256
  ```

### **VMware (.iso)**

- **Filename:** `InfluenceOps_VM_VMware.7z`  
- **SHA256:** 2fdce58af1cd00ee99b00daba1dda250a71e423ea2b25f991a7c632e18858dc1
  ```
  certutil -hashfile "C:\path\to\your\file.txt" SHA256
  ```

---

## Setup Instructions

1. **Download the appropriate VM file for your platform.**
2. **Verify the hash** (optional but recommended).
3. **Import the VM:**
   - VirtualBox: Open the VirtualBox Manager, go to "File" > "Import Appliance," select the OVF/OVA file, and follow the wizard to configure the import settings.
   - VMware: "Create a new virtual machine" > Point it to the ISO file location.
5. **Start the VM.**  
   Log in using the credentials above.

---

## Questions or Issues?

If you encounter issues with the VM or tools, please bring them up during the workshop or reach out to the instructor. All tools are open-source and documented online, and you're encouraged to explore!

---

###  Final Note

This VM was built for education, ethical testing, and professional development. Do **not** use any included tools or techniques for unauthorized activity. Always operate within the bounds of your legal and ethical scope.

Happy pretexting — and remember: **Always trust, but verify.**


- GFK

![ghostball](https://github.com/user-attachments/assets/92538e0f-46b7-46b8-b4f6-69d43c1d3c68)
