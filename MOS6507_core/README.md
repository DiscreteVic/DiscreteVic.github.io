# MOS6507 core
<link rel="stylesheet" type="text/css" href="/css/style.css">

Progress about the design and development of the MOS6507 (Atari 2600) core for a FPGA. Using VHDL for the implementation. [Project sources](https://github.com/DiscreteVic/MOS6507-HDL-core)

## Previous work:

The basic project was created using my previous project of the [VGA Controller](https://github.com/DiscreteVic/VGAController) as template. 

### Development enviorment

- [DE10-Lite Board](https://www.terasic.com.tw/cgi-bin/page/archive.pl?Language=English&No=1021): As fpga board to implement the hardware design.

- Quartus lite IDE: The core is going to be implemented with VHDL, and the intel application is for the syntetization and deployment tasks. 

In my previous project [7SegController](https://github.com/DiscreteVic/7SegController) is explained how to set up the enviroment.


### Day 1: [2/11/2023]

### Initial developments

- Ported 7 segment display controller to VHDL to debug any value with the DE10 board

### Day 1: [12/11/2023] 

### [Basic entities development](https://github.com/DiscreteVic/MOS6507-HDL-core/commit/d83a69c1b86c59c84be04b4f2dcdceae930be168)

- Generic Register Entity: Basic structure of a byte register.
    Definition of the interface and the logic.

- ALU Entity: Basic structure .
    Logic to add and substract with carry.

- Tested basic functionality of the entities
