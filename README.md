# InflucenceOps: Tactical Pretexting - Student VM  
**Workshop Virtual Machine for InfluenceOps: Tactical Pretexting**

Welcome to the InflucenceOps Student VM — a lightweight Ubuntu-based virtual machine preloaded with everything you need for hands-on exercises in OSINT, persona building, and scenario development as part of the **InfluenceOps: Tactical Pretexting** workshop.

All tools are open source and pre-installed. The VM has been optimized for low-resource environments and includes Obsidian for structured note-taking with workshop-specific templates.

---

## VM Overview

- **OS:** Ubuntu 22.04 LTS (Minimal Install)
- **Preinstalled Tools:**
  - [The Ultimate OSINT Collection](https://start.me/p/DPYPMz/the-ultimate-osint-collection) – Super awesome collection of OSINT tools and other information! Thank you Hatless1der!
  - [Visual Studio Code (VSCode](https://code.visualstudio.com/) – For coding scripts
  - Search Engine Dorks Cheat sheet
  - `whois`, `dig` – Domain investigation tools
  - [Obsidian](https://obsidian.md/) – Note-taking and pretext template management
 
- **Workshop Materials:**
  - OSINT, Persona, and Scenario templates (Markdown in Obsidian)
  - Slide deck (PDF)
  - Sample reports
  - Cheat sheets

---

## Login Credentials

- **Username:** `student`  
- **Password:** `pass123`  

You will be automatically logged in as the `student` user.

---

## 📂 Vault Location (Obsidian)

When you open Obsidian, use the preloaded vault located at:

```
/home/student/Documents/Influence Ops/
```

This contains:
- Templates for OSINT, Personas, Scenarios, Reports, and Feedback
- Pre-written examples to guide your work
- A structured folder system to organize your research and activities

---

## Hashes for Verification

### **VirtualBox (.ova)**

- **Filename:** `PretextOps_VM_VirtualBox.ova`
- **SHA256:**  
  ```
  [INSERT SHA256 HASH HERE]
  ```

### **VMware (.ovf + .vmdk)**

- **Filename:** `PretextOps_VM_VMware.zip`  
- **SHA256:**  
  ```
  [INSERT SHA256 HASH HERE]
  ```

Use a tool like `sha256sum` or `shasum -a 256` to verify the integrity of your download before importing.

---

## Setup Instructions

1. **Download the appropriate VM file for your platform.**
2. **Verify the hash** (optional but recommended).
3. **Import the VM:**
   - **VirtualBox:**  
     Open VirtualBox → File → Import Appliance → Select `.ova` file
   - **VMware Player:**  
     Open VMware → File → Open → Select `.ovf` file
4. **Start the VM.**  
   Log in using the credentials above.

---

## Questions or Issues?

If you encounter issues with the VM or tools, please bring them up during the workshop or reach out to the instructor. All tools are open-source and documented online, and you're encouraged to explore!

---

###  Final Note

This VM was built for education, ethical testing, and professional development. Do **not** use any included tools or techniques for unauthorized activity. Always operate within the bounds of your legal and ethical scope.

Happy pretexting — and remember: **Always trust, but verify.**
```
- GFK
---
