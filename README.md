<p align="center">
    <a href="https://git.io/typing-svg">
        <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&size=32&duration=1800&pause=600&color=11F732&background=000000&width=1000&height=110&lines=Welcome+-+where+2%C3%975090s+become+your+new+roommate." alt="Typing SVG" />
    </a>
</p>

<p align="center">
    <img src="Photos/8GPU/Preparing/EE/" width="700" style="border-radius: 12px; box-shadow: 0 4px 16px #11F73255;">
</p>

<div align="center">

<img src="https://img.shields.io/badge/License-MIT-yellow.svg" alt="License: MIT">
<img src="https://img.shields.io/github/stars/AutonomousOfficial/8xGPUs" alt="GitHub stars">
<img src="https://img.shields.io/badge/Status-In%20Development-blue" alt="Status">
<img src="https://img.shields.io/github/downloads/AutonomousOfficial/8xGPUs/total" alt="Downloads">
<img src="https://img.shields.io/github/v/release/AutonomousOfficial/8xGPUs" alt="Version">
<img src="https://img.shields.io/github/repo-size/AutonomousOfficial/8xGPUs" alt="Repo Size">
<img src="https://img.shields.io/github/issues/AutonomousOfficial/8xGPUs" alt="Open Issues">
<img src="https://img.shields.io/github/issues-pr/AutonomousOfficial/8xGPUs" alt="Open Pull Requests">

</div>

---

<div align="center">
    <b><i>
        This guide shows you how to build a cutting-edge AI server with 2x GPUs. From hardware selection to software setup, follow each step to create a high-performance platform for deep learning, data science, and GPU-intensive workloads.
    </i></b>
</div>

---

## 📚 Table of Contents
- 🏁 Introduction 
- 🛠️ Preparation 
- 🤖 Assembly 
- ⚙️ Setup
- 🧪 Testing 
- 📦 BOM
- 📝 License

---

# 🏁 Introduction &ensp; [🔝](#-table-of-contents)

<table>
    <tr>
        <td align="center" width="55%">
            <b><i>
                This tutorial guides you through building a high-performance AI server equipped with two GPUs. Whether you're a researcher, developer, or enthusiast, you'll learn everything from selecting and assembling the right hardware to configuring your system and performing initial tests. By the end, you'll have a powerful platform ready for demanding AI workloads.
            </i></b>
        </td>
        <td align="center" width="45%">
            <img src="Photos/2GPU/Introduction/introduction.png" width="350"  style="border-radius: 8px;">
        </td>
    </tr>
</table>

---

# 🛠️ Preparation &ensp; [🔝](#-table-of-contents)

### 1. [**Electronic & Electrical**](https://github.com/autonomous-AI-lab/2xGPUs/blob/main/Docs/Prepare_EE.md)

### 2. [**Mechanical & Housing**](https://github.com/autonomous-AI-lab/2xGPUs/tree/main/Step_Models)

---

# 🤖 Assembly &ensp; [🔝](#-table-of-contents)
[See detailed steps](https://github.com/autonomous-AI-lab/2xGPUs/blob/main/Docs/Assembly.md)

---

# ⚙️ Setup &ensp; [🔝](#-table-of-contents)
### BIOS Optimization for GPU Performance

> **Tip:** The default BIOS settings may not deliver optimal performance for multi-GPU workloads. Adjust these parameters for best results:


- **Above 4G Decoding** ![Static Badge](https://img.shields.io/badge/Important-8A2BE2)<br>
    🚨📢🔔⚠️
    Enable "Above 4G Decoding" to address large GPU memory.<br>
    ```
    Advanced -> PCI Subsystems Settings -> Enable Above 4G Decoding
    ```

- **Resizable BAR** ![Static Badge](https://img.shields.io/badge/Important-8A2BE2)<br>
    🚨📢🔔⚠️
    Activate "Resizable BAR" for improved CPU-GPU data transfer.<br>
    ```
    Advanced -> PCI Subsystems Settings -> Enable Re-size BAR support
    ```

- **Power Management**  
    Disable unnecessary power-saving features (C-states, ASPM) that may throttle GPU performance.<br>
    `Optional`

- **Memory Configuration**  
    Set RAM to rated speed and enable XMP/DOCP profiles for max bandwidth.<br>
    `Optional`

- **Fan and Thermal Controls**  
    Adjust fan curves and thermal limits for optimal cooling.<br>
    `Optional`

After saving changes, reboot and monitor GPU performance and stability.

**References:**  
- [Motherboard User Manual 💻🖱️](https://github.com/autonomous-AI-lab/2xGPUs/blob/main/Docs/UM_Motherboard.pdf)  
- [BMC Documents 🤖](https://github.com/autonomous-AI-lab/2xGPUs/blob/main/Docs/UM_BIOS.pdf)

<p align="center">
    <video src=""></video>
</p>

---

# 🧪 Testing &ensp; [🔝](#-table-of-contents)

Boot with WinPE from USB to verify hardware, or install Linux, NVIDIA drivers, and check with `nvidia-smi or nvtop`. Once confirmed, install your OS and start your AI work.

<table>
        <td align="center">
            <img src="Photos/2GPU/Testing/nvidia-smi.png" width="700"><br>
        </td>
</table>

<p align="center">
    <video src=""></video>
</p>

---

# 📦 Bill of Materials (BOM) &ensp; [🔝](#-table-of-contents)

- [𝄜 Bill of Materials](https://github.com/autonomous-AI-lab/2xGPUs/blob/main/BOM/BoM.md)

---

# 📝 License &ensp; [🔝](#-table-of-contents)

This project is open source under the [MIT License](https://github.com/autonomous-AI-lab/2xGPUs/blob/main/LICENSE).

---

<p align="center">
  <a href="https://git.io/typing-svg"><img src="https://readme-typing-svg.demolab.com?font=Fira+Code&duration=1800&pause=1000&color=11F732&width=840&lines=If+this+helped%2C+toss+us+a+%E2%AD%90.+Got+questions%3F+Email+brody%40autonomous.ai" alt="Typing SVG" /></a>
</p>
