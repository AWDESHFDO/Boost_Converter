Here’s your project write-up rewritten in a **clear, professional, and standard format** — suitable for a report, paper, or thesis section:

---

## **Design and Implementation of a Boost Converter**

### **Abstract**

This project focuses on the **design, simulation, and experimental implementation** of a DC–DC Boost Converter to evaluate its performance under various operating conditions. The main objectives were to study the behavior of key circuit waveforms, determine the converter’s **efficiency**, and measure the **Total Harmonic Distortion (THD)** in the hardware prototype.

### **Simulation Phase**

The initial stage involved simulating the boost converter circuit using **MATLAB/Simulink** and **PLECS** software to analyze its dynamic characteristics and validate the theoretical design parameters. An open-loop model was first developed to observe the switching behavior, inductor current, and output voltage characteristics. The simulation results guided the selection of appropriate component values and ensured optimized performance prior to hardware realization.

### **Hardware Implementation**

After successful simulation, a **hardware prototype** of the boost converter was developed. The **MOSFET gate pulses** were generated using a **Wavect controller**, which interfaced with a **custom-designed driver board**. The driver circuit was designed using **Altium Designer** and subsequently fabricated on a **PCB** through local PCB printing.

The experimental setup was initially tested in **open-loop configuration** using a **Chroma programmable power supply** to provide a variable input voltage ranging from **0–48 V**. An **electronic load** was employed to emulate different load conditions. Input and output voltage and current waveforms were recorded using a **power analyzer**, while the switching pulses were verified using an **oscilloscope**.

During testing, one of the gate pulse patterns was observed to be inconsistent. The issue was diagnosed and corrected by fine-tuning the pulse parameters in the Wavect controller configuration. After resolving this, the setup was operated in **closed-loop configuration** to achieve better voltage regulation and enhanced transient performance.

### **Analysis and Results**

The developed boost converter was analyzed based on the following parameters:

* Output voltage and current characteristics
* Switching performance of MOSFETs
* Efficiency under various input and load conditions
* THD of the output voltage

The experimental outcomes closely matched the simulation results, thereby validating the converter design and demonstrating efficient operation of the hardware system.


