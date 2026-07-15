<div align="center">

<!-- Animated Name Banner -->
<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&color=0:0f2027,50:203a43,100:2c5364&height=200&section=header&text=Jairus%20Samraj%20Solomon&fontSize=50&fontColor=ffffff&fontAlignY=38&desc=ASIC%20%2F%20VLSI%20Design%20Engineer%20•%20RTL-to-GDSII%20•%20RISC-V&descAlignY=60&descSize=17&animation=fadeIn" />

<!-- Typing SVG -->
<a href="https://git.io/typing-svg">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=22&pause=1000&color=38BDF8&center=true&vCenter=true&width=650&lines=RTL-to-GDSII+%7C+RISC-V+%7C+Timing+Closure+%E2%9A%A1;Design-for-Testability+(DFT)+%F0%9F%A7%A9;Physical+Design+%7C+Scan+%7C+ATPG+%F0%9F%94%8C;VIT+Chennai+%F0%9F%8F%AB;Lead+Engineer+%40+NoEtherX+Labs" alt="Typing SVG" />
</a>

<br/>

<img src="https://komarev.com/ghpvc/?username=jairussolomon&style=for-the-badge&color=0EA5E9&label=PROFILE+VIEWS" />
&nbsp;
<a href="https://github.com/jairussolomon?tab=followers">
  <img src="https://img.shields.io/github/followers/jairussolomon?style=for-the-badge&color=0EA5E9&labelColor=0f2027&label=FOLLOWERS" />
</a>

<br/><br/>

![Focus](https://img.shields.io/badge/PRIMARY_FOCUS-Design--for--Testability_(DFT)-CE1126?style=for-the-badge)
&nbsp;
![Currently](https://img.shields.io/badge/Currently-NoEtherX_Labs_(Remote_Intern)-1a1a2e?style=for-the-badge&labelColor=2c5364)

</div>

---

## ⚡ About Me

```verilog
module jairus_samraj_solomon (
    input  wire clk,
    input  wire rst_n
);

    // ---- Identity ----
    parameter NAME     = "Jairus Samraj Solomon";
    parameter COLLEGE   = "VIT Chennai, India";
    parameter DEGREE    = "B.Tech ECE - VLSI Design";
    parameter ROLE      = "DFT / ASIC Design Engineer";
    parameter FOCUS     = "Scan Insertion | ATPG | LBIST/MBIST | Secure Scan";
    parameter FLOW      = "RTL -> Synthesis -> DFT -> PD -> GDSII";
    parameter TOOLS     = "Cadence Genus/Modus, Innovus, Xcelium, Tempus";
    parameter PDK       = "SkyWater130 (sky130A/sky130B)";
    parameter AVAILABLE = 1'b1;

    // ---- DFT scan chain (metaphorically speaking) ----
    reg  scan_enable;
    wire test_mode;

    assign test_mode = AVAILABLE;

    always @(posedge clk or negedge rst_n) begin
        if (!rst_n)
            scan_enable <= 1'b0;
        else
            scan_enable <= test_mode;
    end

    initial begin
        $display("Thanks for dropping by -- let's insert some scan chains.");
    end

endmodule
```

---

## 🧬 Engineering Specialization

<div align="center">

**Primary Focus**
![Scan Insertion](https://img.shields.io/badge/Scan_Insertion-CE1126?style=for-the-badge)
![ATPG](https://img.shields.io/badge/ATPG-CE1126?style=for-the-badge)
![LBIST](https://img.shields.io/badge/LBIST-CE1126?style=for-the-badge)
![MBIST](https://img.shields.io/badge/MBIST-CE1126?style=for-the-badge)
![Secure_Scan](https://img.shields.io/badge/Secure_Scan-CE1126?style=for-the-badge)
![Boundary_Scan](https://img.shields.io/badge/Boundary_Scan-CE1126?style=for-the-badge)
![OPCG](https://img.shields.io/badge/OPCG_At--Speed_Test-CE1126?style=for-the-badge)
![Test_Compression](https://img.shields.io/badge/Test_Compression-CE1126?style=for-the-badge)

**Also Skilled In**
![RTL Design](https://img.shields.io/badge/RTL_Design-0EA5E9?style=for-the-badge)
![Synthesis](https://img.shields.io/badge/Synthesis-0EA5E9?style=for-the-badge)
![Floorplanning](https://img.shields.io/badge/Floorplanning-0EA5E9?style=for-the-badge)
![Placement_Routing](https://img.shields.io/badge/Placement_%26_Routing-0EA5E9?style=for-the-badge)
![CTS](https://img.shields.io/badge/Clock_Tree_Synthesis-0EA5E9?style=for-the-badge)
![STA_Signoff](https://img.shields.io/badge/STA_%26_Timing_Signoff-0EA5E9?style=for-the-badge)
![DRC_LVS](https://img.shields.io/badge/DRC_%2F_LVS_Signoff-0EA5E9?style=for-the-badge)
![PDN](https://img.shields.io/badge/Power_Delivery_(PDN)-0EA5E9?style=for-the-badge)

</div>

```
🔍  DFT (Primary Focus)
     └─ Scan chain insertion & test signal definition (Cadence Genus DFT)
     └─ DFT rule checking + ATPG readiness for manufacturing test
     └─ Power-aware ATPG, test compression, chiplet-level DFT
     └─ On-chip clock generation (OPCG) across TestMAX, Modus DFT, Tessent
     └─ Secure scan architectures, LBIST/MBIST integration

🧱  ASIC Front-End
     └─ RTL design & elaboration in Verilog/SystemVerilog
     └─ RTL-to-gate synthesis, technology mapping, retiming (Cadence Genus)
     └─ Gate-level simulation with SDF back-annotation (Cadence Xcelium)

🏗️  Physical Design
     └─ Hierarchical floorplanning, macro planning, PDN design (Innovus)
     └─ Placement, CTS, routing with congestion-driven optimization
     └─ Macro-based hierarchical integration (Caravel/OpenLane)

⏱️  Timing & Signoff
     └─ Post-CTS/post-route timing debug (Cadence Tempus)
     └─ Setup/hold closure, DRC/LVS verification (Netgen, KLayout)
     └─ Full RTL-to-GDSII tapeout signoff
```

---

## 🛠️ Tech Arsenal

<div align="center">

### 🧩 DFT & Test
![Cadence Modus](https://img.shields.io/badge/Cadence_Modus_DFT-CE1126?style=for-the-badge)
![Synopsys TestMAX](https://img.shields.io/badge/Synopsys_TestMAX-0EA5E9?style=for-the-badge)
![Siemens Tessent](https://img.shields.io/badge/Siemens_Tessent-0EA5E9?style=for-the-badge)
![Cadence Genus](https://img.shields.io/badge/Cadence_Genus-CE1126?style=for-the-badge)

### 🔩 ASIC / Physical Design Flow
![Verilog](https://img.shields.io/badge/Verilog-000000?style=for-the-badge&logo=v&logoColor=white)
![SystemVerilog](https://img.shields.io/badge/SystemVerilog-black?style=for-the-badge)
![Cadence Innovus](https://img.shields.io/badge/Cadence_Innovus-CE1126?style=for-the-badge)
![Cadence Xcelium](https://img.shields.io/badge/Cadence_Xcelium-CE1126?style=for-the-badge)
![Cadence Tempus](https://img.shields.io/badge/Cadence_Tempus-CE1126?style=for-the-badge)
![Cadence Virtuoso](https://img.shields.io/badge/Cadence_Virtuoso-CE1126?style=for-the-badge)

### 🖥️ Open Source EDA
![OpenLane](https://img.shields.io/badge/OpenLane-2C5364?style=for-the-badge)
![OpenROAD](https://img.shields.io/badge/OpenROAD-2C5364?style=for-the-badge)
![Magic](https://img.shields.io/badge/Magic_VLSI-2C5364?style=for-the-badge)
![Netgen](https://img.shields.io/badge/Netgen-2C5364?style=for-the-badge)
![KLayout](https://img.shields.io/badge/KLayout-2C5364?style=for-the-badge)
![Sky130](https://img.shields.io/badge/SkyWater130_PDK-0EA5E9?style=for-the-badge)

### 🐍 Programming & Scripting
![Python](https://img.shields.io/badge/Python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)
![C](https://img.shields.io/badge/C-A8B9CC?style=for-the-badge&logo=c&logoColor=white)
![Tcl](https://img.shields.io/badge/Tcl-3E6E93?style=for-the-badge)
![Perl](https://img.shields.io/badge/Perl-39457E?style=for-the-badge&logo=perl&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black)

</div>

---

## 📜 Certifications

<div align="center">

![Cadence DFT](https://img.shields.io/badge/Cadence_Design_for_Test_Fundamentals_v25.1-CE1126?style=flat-square)
![Cadence RTL2GDSII](https://img.shields.io/badge/Cadence_RTL--to--GDSII_Flow_v5.0-0EA5E9?style=flat-square)
![Cadence STA](https://img.shields.io/badge/Cadence_Basic_STA_v2.0-0EA5E9?style=flat-square)
![Digital IP](https://img.shields.io/badge/Digital_IP_Overview_%E2%80%93_Design_%26_Verification-2C5364?style=flat-square)
![Functional Verification DFT](https://img.shields.io/badge/Functional_Verification_%26_DFT-CE1126?style=flat-square)
![PD Flow](https://img.shields.io/badge/Physical_Design_Flow%2C_Synthesis_%26_STA_Basics-0EA5E9?style=flat-square)
![SRAM ROM](https://img.shields.io/badge/SRAM%2FROM_Architecture_%26_Design-2C5364?style=flat-square)
![Systems Architecture](https://img.shields.io/badge/Systems_Architecture_%26_Frontend_Engineering-2C5364?style=flat-square)

</div>

---

## 📊 GitHub Stats

<div align="center">

<img height="180em" src="https://github-readme-stats.vercel.app/api?username=jairussolomon&show_icons=true&theme=midnight-purple&include_all_commits=true&count_private=true&hide_border=true&bg_color=0d1117"/>
&nbsp;
<img height="180em" src="https://github-readme-stats.vercel.app/api/top-langs/?username=jairussolomon&layout=compact&langs_count=8&theme=midnight-purple&hide_border=true&bg_color=0d1117"/>

</div>

<div align="center">
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=jairussolomon&theme=midnight-purple&hide_border=true&background=0d1117" />
</div>

<br/>

<div align="center">
  <img src="https://github-readme-activity-graph.vercel.app/graph?username=jairussolomon&bg_color=0d1117&color=0ea5e9&line=38bdf8&point=ffffff&area=true&hide_border=true" width="95%"/>
</div>

---

## 📌 Featured Repositories

<div align="center">

<a href="https://github.com/jairussolomon/Synthera">
  <img width="48%" src="https://github-readme-stats.vercel.app/api/pin/?username=jairussolomon&repo=Synthera&theme=midnight-purple&bg_color=0d1117&title_color=CE1126&description=RTL-to-Gate+Synthesis+%2B+DFT+Scan+Insertion+(Cadence+Genus)" />
</a>
<a href="https://github.com/jairussolomon/Solthera">
  <img width="48%" src="https://github-readme-stats.vercel.app/api/pin/?username=jairussolomon&repo=Solthera&theme=midnight-purple&bg_color=0d1117&title_color=0EA5E9&description=Physical+Design+%26+Timing+Closure+Flow+(Cadence+Innovus)" />
</a>

<a href="https://github.com/jairussolomon/Nythera">
  <img width="48%" src="https://github-readme-stats.vercel.app/api/pin/?username=jairussolomon&repo=Nythera&theme=midnight-purple&bg_color=0d1117&title_color=0EA5E9&description=Global+Timing+Debug+%26+Signoff+Analysis+(Cadence+Tempus)" />
</a>
<a href="https://github.com/jairussolomon/Fluxera">
  <img width="48%" src="https://github-readme-stats.vercel.app/api/pin/?username=jairussolomon&repo=Fluxera&theme=midnight-purple&bg_color=0d1117&title_color=CE1126&description=Caravel-Integrated+RISC-V+SoC+%7C+OpenLane+%2B+Sky130" />
</a>

<a href="https://github.com/jairussolomon/Nexaris">
  <img width="48%" src="https://github-readme-stats.vercel.app/api/pin/?username=jairussolomon&repo=Nexaris&theme=midnight-purple&bg_color=0d1117&title_color=0EA5E9&description=Hierarchical+Floorplanning+%26+Power+Planning+(Innovus)" />
</a>
<a href="https://github.com/jairussolomon/Xytrix">
  <img width="48%" src="https://github-readme-stats.vercel.app/api/pin/?username=jairussolomon&repo=Xytrix&theme=midnight-purple&bg_color=0d1117&title_color=CE1126&description=Gate-Level+Simulation+%2B+SDF+Timing+Verification+(Xcelium)" />
</a>

</div>

---

## 🔬 What I'm Building

```
🧩  DFT-Integrated Front-End Flow — Synthera
     └─ Scan chain insertion, test signal definition, DFT rule checking (Genus)
     └─ Low-power DFT (UPF/CPF) + LEC formal equivalence

⏱️  Timing Closure & Physical Design — Nythera / Nexaris / Solthera
     └─ Post-CTS timing debug (Cadence Tempus)
     └─ Hierarchical floorplanning & PDN in Innovus
     └─ Congestion-driven routing, zero setup/hold violations

🔁  RISC-V SoC Tapeout — Abythera / Fluxera
     └─ Full RTL-to-GDSII flow on OpenLane + Sky130
     └─ Caravel-integrated wrapper, DRC/LVS clean, MPW-ready

🧪  Gate-Level Test Verification — Xytrix
     └─ SDF-based GLS with 100% path delay/timing check coverage
     └─ Zero Delay vs SDF comparison for post-synthesis timing validation
```

---

## 📄 Publications

```
📘 Reversible Quantum Digital Circuits and Quantum RNG Using Qiskit — IEEE ICDCS 2026
```

---

## 🌐 Connect with Me

<div align="center">

<a href="https://linkedin.com/in/jairus-samraj-solomon" target="_blank">
  <img src="https://img.shields.io/badge/LinkedIn-jairus--samraj--solomon-0077B5?style=for-the-badge&logo=linkedin&logoColor=white"/>
</a>
&nbsp;
<a href="https://github.com/jairussolomon" target="_blank">
  <img src="https://img.shields.io/badge/GitHub-jairussolomon-181717?style=for-the-badge&logo=github&logoColor=white"/>
</a>
&nbsp;
<a href="mailto:jairus.samraj.solomon@gmail.com" target="_blank">
  <img src="https://img.shields.io/badge/Email-jairus.samraj.solomon-D14836?style=for-the-badge&logo=gmail&logoColor=white"/>
</a>

</div>

---

## 🎸 Beyond the Chip

```
🧩  Rubik's Cube Solving (up to 11x11)
🎹  Playing Piano & Guitar
🏀  Basketball, Football, Volleyball (School/College Team)
💪  Fitness & Strength Training
```

---

<div align="center">

*"If it isn't testable, it isn't done."*

<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&color=0:2c5364,50:203a43,100:0f2027&height=120&section=footer&animation=fadeIn"/>

</div>
