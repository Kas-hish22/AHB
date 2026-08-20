# AHB Lab

This repository contains the work completed for the AHB-Lite and AHB bus architecture laboratory tasks.

## Lab Tasks

### Task 1 – AHB-Lite Interface in Logisim

Designed and simulated a simplified AHB-Lite single-master bus interface in Logisim.

The design demonstrates:

* Single-master AHB-Lite communication
* Read and write transfers
* Address and data transfer
* Wait-state insertion
* Basic AHB-Lite control and response behavior

The Logisim circuit file is included in the **Task 1** folder.

---

### Task 2 – AHB-Lite Master-Slave SystemVerilog

Analyzed and debugged the provided buggy AHB-Lite master-slave SystemVerilog implementation.

Five comprehensive test cases were developed and simulated individually:

1. Single Write Transfer – No Wait-state
2. Single Read Transfer – No Wait-state
3. Write with Wait-state Insertion
4. Burst Transfer – INCR4
5. Invalid Address with Error Response

The SystemVerilog source files, testbench files, simulation results, and screenshots are included in the **Task 2** folder.

The debugging process focused on identifying protocol violations, incorrect signal timing, transfer control issues, wait-state handling, burst-transfer behavior, and error-response handling. The identified issues were fixed to achieve correct AHB protocol operation.

---

### Task 3 – AHB System with Four Slaves

Developed a comprehensive block diagram and architectural description of an AHB system containing one master and four slaves.

The task covers:

* AHB system architecture
* Master-slave interconnection
* Address decoding
* Slave selection
* Read-data multiplexing
* Response handling
* AHB signal interconnections
* Operational flow of read and write transactions

The detailed documentation is provided in the **Task 3** folder.

---

### Task 4 – SoC Peripherals

Identified and described five high-speed and five low-speed peripherals commonly used in System-on-Chip designs.

### High-Speed Peripherals

* Ethernet
* USB
* DDR Memory Controller
* PCI Express (PCIe)
* SD/eMMC Controller

### Low-Speed Peripherals

* UART
* SPI
* I2C
* GPIO
* PWM

For each peripheral, the documentation includes its typical data rate, bus/interface requirements, and common applications.

The detailed documentation is provided in the **Task 4** folder.

---

## Repository Structure

```text
AHB/
│
├── Task 1/
│   └── Logisim Circuit (.circ)
│
├── Task 2/
│   ├── SystemVerilog Files (.sv)
│   ├── Test Cases
│   └── Simulation Screenshots
│
├── Task 3/
│   └── AHB System with 4 Slaves (PDF)
│
├── Task 4/
│   └── SoC Peripherals (PDF)
│
└── README.md
```

## Technologies and Tools

* AHB-Lite
* SystemVerilog
* Logisim
* Digital Design and Verification
* SoC Bus Architecture

## Conclusion

This laboratory provided practical experience with AHB-Lite bus communication, master-slave interfaces, wait-state handling, burst transfers, error responses, address decoding, and SoC peripheral architectures.
