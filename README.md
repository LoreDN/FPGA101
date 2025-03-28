# :mortar_board: FPGA101 COURSE


## :file_folder: How does this repo work
This repo serves as a collection of exercises and projects carried out during the <b>FPGA101</b> course. <br>
Every board has its own folder, inside wich can be found a subfolder for each project, and a 
<i>'BOARDNAME_configuration.txt'<i> file, wich contains all the standard mappings of the Board, 
in order to make easier the creation of the <i>constrs</i> file <i>'project.xpr'</i>. <br>
Every project has its own subfolder inside the corresponding board folder, in wich can be found 
a folder named <i>'project.srcs'</i>, wich contains the project files ,and a <i>'project.xpr'</i> 
file, wich is the complete project that should be open from Vivado.
<br>
<br>


## PYNQ-Z2 board

### Project 1: Led :bulb:
Implementation of a VHDL program that allows to turn on a led after the activation of a switch.
<br>