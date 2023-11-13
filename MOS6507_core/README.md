# MOS6507 core
<link rel="stylesheet" type="text/css" href="/css/style.css">

Progress about the design and development of the MOS6507 (Atari 2600) core for a FPGA. Using VHDL for the implementation. [Project sources](https://github.com/DiscreteVic/MOS6507-HDL-core)

## Previous work:

The basic project was created using my previous project of the [VGA Controller](https://github.com/DiscreteVic/VGAController) as template. 

### Development enviorment

- [DE10-Lite Board](https://www.terasic.com.tw/cgi-bin/page/archive.pl?Language=English&No=1021): As fpga board to implement the hardware design.

- Quartus lite IDE: The core is going to be implemented with VHDL, and the intel application is for the syntetization and deployment tasks. 

In my previous project [7SegController](https://github.com/DiscreteVic/7SegController) is explained how to set up the enviroment.

## [Work diary](/MOS6507_core/WorkDiary/)

## Current status
### Instruction set 

[6502 Instrucction set](https://www.masswerk.at/6502/6502_instruction_set.html#details)


- Transfer Instructions
  - [ ] LDA
  - [ ] LDX
  - [ ] LDY
  - [ ] STA
  - [ ] STX
  - [ ] STY
  - [ ] TAX
  - [ ] TAY
  - [ ] TSX
  - [ ] TXA
  - [ ] TXS
  - [ ] TYA

- Stack Instructions
  - [ ] PHA
  - [ ] PHP
  - [ ] PLA
  - [ ] PLP

- Decrements & Increments
  - [ ] DEC
  - [ ] DEX
  - [ ] DEY
  - [ ] INC
  - [ ] INX
  - [ ] INY

- Arithmetic Operations
  - [ ] ADC
  - [ ] SBC

- Logical Operations
  - [ ] AND
  - [ ] EOR
  - [ ] ORA

- Shift & Rotate Instructions
  - [ ] ASL
  - [ ] LSR
  - [ ] ROL
  - [ ] ROR

- Flag Instructions
  - [ ] CLC
  - [ ] CLD
  - [ ] CLI
  - [ ] CLV
  - [ ] SEC
  - [ ] SED
  - [ ] SEI


