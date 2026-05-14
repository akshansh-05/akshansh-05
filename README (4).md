<h1 align="center">Hi there, I'm Akshansh Chaurasia 👋</h1>

<p align="center">
  <b>VLSI Enthusiast · RTL Design · Functional Verification · Physical Design</b><br/>
  B.Tech ECE (Nanoelectronics) · Shiv Nadar University Delhi-NCR · Class of 2027
</p>

<p align="center">
  <a href="mailto:akshansh439@gmail.com"><img src="https://img.shields.io/badge/Gmail-D14836?style=for-the-badge&logo=gmail&logoColor=white"/></a>
  <a href="https://linkedin.com/in/akshansh-chaurasia"><img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white"/></a>
  <a href="https://github.com/akshansh-05"><img src="https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white"/></a>
</p>

---

## 🧑‍💻 About Me

I'm a passionate **VLSI engineer-in-training** with a strong focus on **Frontend Design**, actively building expertise in **RTL Design** and **Design Verification Methodologies**. I have hands-on experience with the complete **RTL-to-GDSII** flow and love working at the intersection of hardware and software.

- 🔍 Seeking training opportunities: **25th May – 24th July**
- 📍 Based in **New Delhi, India**
- ⚡ Fun fact: I built an AI-powered smart dustbin that sends WhatsApp alerts!

---

## 🛠️ Technical Skills

| Category | Skills |
|---|---|
| **HDL Languages** | Verilog, SystemVerilog |
| **Programming** | Python, C/C++ |
| **Verification** | UVM (Universal Verification Methodology) |
| **EDA Tools** | Cadence Virtuoso, Synopsys Design Compiler, Xilinx Vivado, EDA Playground |
| **Scripting** | TCL |
| **Hardware** | Nexys A7 FPGA, ESP32, Raspberry Pi, STM32, Arduino |

---

## 🚀 Projects

### 🔁 Deterministic Multi-GPU Reduction via Custom NoC Accelerator
`Verilog` `SystemVerilog` `RTL Design` `Pipelined Architecture` `NoC`
- Architected a HW-SW co-design system using a Binary Tree-based reduction order ensuring numerical determinism in multi-GPU floating-point operations, with a 3-stage pipelined compute node, 5-instruction ISA, and credit-based flow control routers.
- Built a static scheduling compiler with a cycle-accurate simulator; verified via a layered testbench covering ISA functionality, packet switching, and deadlock-freedom assertions.

---

### ✅ Functional Verification of Data Aligner IP Block
`SystemVerilog` `UVM` `RAL` `APB` `Functional Coverage`
- Developed a full UVM testbench with reusable agents, custom MD protocol driver/monitor, and RAL model to verify data alignment across RX/TX interfaces over an AMBA 3 APB bus.
- Designed a scoreboard and functional coverage model validating alignment across SIZE/OFFSET configurations, FIFO flow control, interrupt generation, and illegal transfer drop-counter scenarios.

---

### 🏗️ Physical Design & RTL-to-GDSII of Synchronous FIFO
`Synopsys DC` `SystemVerilog` `SAED 32nm EDK` `TCL`
- Designed and verified FIFO RTL; synthesized with Synopsys Design Compiler and executed the full PD flow — floorplanning, power planning, placement, CTS, routing — with timing, power, and DRC/LVS signoff.
- Automated the RTL-to-GDSII flow via TCL scripting, reducing manual intervention across synthesis and physical design stages.

---

### ⏱️ Analysis of Register-to-Register Timing Path
`Cadence Virtuoso` `ADE XL` `45nm PDK` `Monte Carlo` `STA`
- Designed a TSPC D Flip-Flop at 45nm; extracted Setup Time (10ps), Hold Time (50ps), and Clock-to-Q Delay (110ps); validated a register-to-register timing path against setup constraints.
- Performed Monte Carlo analysis in ADE XL to study process variation impact on tCKQ; conducted NMOS parametric sweeps on width and length.

---

### 🗑️ AI-Based Smart Dustbin – Sensor Fusion & Predictive Analytics
`IoT` `ESP32` `FastAPI` `Edge Analytics` `Twilio`
- Built an intelligent waste bin using ESP32, dual ultrasonic sensors, and HX711 load cell for real-time volume/weight fusion with hysteresis-controlled servo automation.
- Developed a cloud analytics pipeline via Google Apps Script and Sheets for fill-rate prediction, with automated WhatsApp alerts via FastAPI/Twilio for high-fill events and daily reports.

---

## 📊 GitHub Stats

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=akshansh-05&show_icons=true&theme=tokyonight&hide_border=true" height="165"/>
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=akshansh-05&layout=compact&theme=tokyonight&hide_border=true" height="165"/>
</p>

<p align="center">
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=akshansh-05&theme=tokyonight&hide_border=true"/>
</p>

---

<p align="center">💬 Always open to collaborating on VLSI, verification, or embedded systems projects!</p>
