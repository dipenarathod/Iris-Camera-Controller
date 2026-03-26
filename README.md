# Wishbone Camera Controller for OV5640

A Wishbone-compliant OV5640 camera controller written in VHDL.

This project is designed to work with the [NEORV32 RISC-V Processor](https://github.com/stnolting/neorv32) and was developed using the [Waveshare OV5640 Camera Board (C)](https://www.waveshare.com/wiki/OV5640_Camera_Board_(C)).

## Repository Layout
- [RTL](RTL) — VHDL source for the camera controller
- [FPGA Setup/ECP5 EVN Board](FPGA%20Setup/ECP5%20EVN%20Board) — FPGA project/setup files for the ECP5 evaluation board
- [Ada Files/wb_ov5640_helper](Ada%20Files/wb_ov5640_helper) — Ada helper library for controlling the camera interface
- [Ada Files/wb_ov5640_tests](Ada%20Files/wb_ov5640_tests) — Ada test programs and examples

## Dependencies
- [NEORV32 Ada HAL](https://github.com/GNAT-Academic-Program/neorv32-hal)
- [Input Output Library](https://github.com/dipenarathod/Wishbone-NPU/tree/main)

## Development Environment
- Board: Lattice ECP5U5MG-85F Evaluation Board
- Tools: Lattice Diamond, Synplify Pro

## Video Guides
TODO: Link
