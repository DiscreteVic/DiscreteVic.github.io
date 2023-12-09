
# MOS6507 Work diary
<link rel="stylesheet" type="text/css" href="/css/style.css">

Work progress by days.

## Day 1: [2/11/2023]

### Initial developments

- Ported 7 segment display controller to VHDL to debug any value with the DE10 board

## Day 2: [12/11/2023] 

### [Basic entities development](https://github.com/DiscreteVic/MOS6507-HDL-core/commit/d83a69c1b86c59c84be04b4f2dcdceae930be168)

- Generic Register Entity: Basic structure of a byte register.
Definition of the interface and the logic.

- ALU Entity: Basic structure.
Logic to add and substract with carry.

- Tested basic functionality of the entities

## Day 3: [12/11/2023] 

### [Basic entities development](https://github.com/DiscreteVic/MOS6507-HDL-core/commit/d83a69c1b86c59c84be04b4f2dcdceae930be168)

- Generic Register Entity: Basic structure of a byte register.
Definition of the interface and the logic.

- ALU Entity: Basic structure.
Logic to add and substract with carry.

- Tested basic functionality of the entities

## Day 4: [15/11/2023] 

### [General purpose registers (X, Y)](https://github.com/DiscreteVic/MOS6507-HDL-core/commit/3189cbc793c9d3d3e3154dc78ca9088a504627e1)

- General purpose register developed, including increment and decrement operation.

## Day 5: [16/11/2023] 


### Internal bus design

- Following the [datasheet](https://www.princeton.edu/~mae412/HANDOUTS/Datasheets/6502.pdf) from Synertek, the registers and the ALU are interconnected by a Internal Data Bus (three-state) with 8 bits width. The memory is accesed by a data bus buffer.

## Day 6: [21/11/2023] 


### Custom bus

- Following the specifications of the datasheet (from the day before). A custom bus specification needs to be defined. The definition, the specification and the implementation is covered at its specific section: [Internal Bus specification](/MOS6507_core/BusSpec/)

## Day 7: [09/12/2023] 


### Custom bus working following example

- Finished, bus specification and implementation.

- Basic test done. 

- Implementation based on oddek project ([link](https://github.com/oddek/8-bit-Computer/tree/master)).

