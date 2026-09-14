---
name: Bug report
about: Create a report to help us improve
title: ''
labels: ''
assignees: ''

---

# RPCS3 Bug Report — Desktop & ARMx3

## **Describe the Bug**
Provide a clear, concise description of the issue observed in RPCS3.  
Include visible symptoms such as crashes, freezes, incorrect RSX/SPU behavior, bad memory values, translation faults, or repeated log errors.

Specify whether the issue occurs on:
- **Desktop (Windows/macOS/Linux)**
- **ARMx3 / ARMv8 builds**
- **Both**

---

## **To Reproduce**
Steps to reproduce the issue:

1. Launch RPCS3 using build: **[insert build number / commit hash]**
2. Platform tested: **[Windows / Linux / macOS / ARMx3 / ARMv8]**
3. Load game: **[title + region]**
4. Perform the following action(s): **[exact steps that trigger the issue]**
5. Observe the incorrect behavior or log output: **[describe the error]**

If the issue requires specific patches, settings, or a certain number of frames before appearing, note that here.

---

## **Expected Behavior**
Describe what should happen instead.  
Examples:
- Game should progress past a certain point  
- RSX/SPU logs should remain stable  
- No ARM translation faults should occur  
- Graphics or memory values should behave correctly  
- Behavior should match Desktop builds if the issue is ARM‑only

---

## **Logs / Evidence**
Attach or reference the following:

- **rpcs3.log** (required)  
- **TTY log** (if relevant)  
- **Screenshots or video** showing the issue  
- **Patch Manager / NetCheat codes used** (if the issue is related to cheats or memory edits)

If the log shows repeating errors (SPU, RSX, LLVM, ARM translation faults, etc.), mention them here.

---

## **System Information**

### **Desktop**
**OS:** [Windows 10/11, macOS version, Linux distro]  
**RPCS3 Version:** [build number]  
**CPU:** [model]  
**GPU:** [model]  
**RAM:** [amount]  

### **ARMx3 / ARMv8**
**Device:** [ARMx3 board / ARM device model]  
**OS:** [Ubuntu ARM, Android, macOS ARM, etc.]  
**RPCS3 Version:** [build number]  
**CPU:** [ARM model]  
**GPU:** [Mali / Adreno / Apple GPU / etc.]  
**RAM:** [amount]

If using custom patches or experimental ARM builds, list them here.

---

## **Additional Context**
Add any extra details that help developers reproduce or understand the issue:

- Whether the issue started after a specific RPCS3 update  
- Whether it only occurs with certain patches or cheats  
- Whether it appears only on ARMx3 but not Desktop  
- Any relevant memory addresses, breakpoints, or PPC behavior observed  
- Differences between Desktop vs ARM behavior (if
