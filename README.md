# EmpkinS Sync Board

Welcome to the EmpkinS Sync Board project, an open source framework for **hardware-based synchronization** of sensors in **multi-modal measurement scenarios**. The Empkins Sync Board (ESB) consists of a PCB which generates different synchronization signals for up to seven arbitrary outputs. THe PCB can be configured programmatically or using the corresponding graphical user interface. Here, we provide an overview of the repositories that belong to our project and are required to build your own ESB: 

- Schematic, PCB, 3D view and BOM of the ESB hardware: [https://365.altium.com/files/B8C35FA4-1EF4-416A-BC0A-35B06F024184](https://365.altium.com/files/B8C35FA4-1EF4-416A-BC0A-35B06F024184)
- Firmware code and flashing instructions: [https://github.com/empkins/empkins-sync-board-hardware](https://github.com/empkins/empkins-sync-board-hardware)
- Graphical User Interface for configuring and operating the PCB: [https://github.com/empkins/empkins-sync-board-gui](https://github.com/empkins/empkins-sync-board-gui)
- Python package to align recorded data based on the synchronization signal: [https://github.com/empkins/empkins-io/tree/main](https://github.com/empkins/empkins-io/tree/main)
- Examples on usage of the postprocessing module: [https://github.com/empkins/empkins-io/blob/main/examples/synchronization/Synchronization.ipynb](https://github.com/empkins/empkins-io/blob/main/examples/synchronization/Synchronization.ipynb)


<img src="./img/ESB_connected.png" width="400" alt="Picture of ESB with Connectors">
