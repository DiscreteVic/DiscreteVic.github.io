# Minimal Xilinx Enviroment for bare-metal sw development
<link rel="stylesheet" type="text/css" href="/css/style.css">

At my [repository](https://github.com/DiscreteVic/AnaloguePocketDev) is located a hello world project for the Zynq Ultrascale+ (tested on Avnet's ZUBoard-1CG), using the Xilinx toolchain but without any kind of GUI, full comand line process to build the source code (using CMake) and uploading to the board. Every step is scripted:

- 1. Step with the XSA (generated with vivado) the platform folder with the Xilinx libraries can be created with the script create_platform.sh.

- 2. With the platform the source code can be built with the script build.sh

- 3. Finally with the ELF file generated at the previous step the software can be flash, with the flash.sh script.

Any modification should be done at the tcl scripts.

