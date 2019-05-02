# FPGA
This has all the files related to the implementation of the project Tic-Tac-Toe game on FPGA.

FPGA_report.pdf gives a detailed explanaion on how to implement the classical pencil-paper game in FPGA. TicTacToe.v is it's verilog code, TicTacToe.pcf is pcf code for pin configurations of icoboard. Makefile consists of commands to generate .asc, .bilf, .bin files.

To run the verilog code:
make v_fname=TicTacToe

