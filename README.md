# VoltageAttacker
Voltage Injection Tool

Voltage fault injection, is the process of shorting a pin or component of a board/device at a precise moment in order to complete a certain function. This function can be pausing the clock, resetting the device, or causing memory to be corrupted. This voltage fault is injected with a crowbar circuit, these crowbar circuits and extremely simple. They are simply MOSFETS, that can be stacked together to increase strength and speed. Stacking MOSFETS allows for pulling a voltage down for longer or pulling a higher voltage down further. Attached below are examples of different VFI pcbs. 


![VFI-Small](https://github.com/IsaaccW/VoltageAttacker/assets/65687558/aab1117e-c1c3-4a88-9a7f-967f4760a0bf)
![VFI_Big](https://github.com/IsaaccW/VoltageAttacker/assets/65687558/a5917459-7ce1-4b03-8b63-642dd99d4d3d)

I have attached examples of using Crowbar Circuits to impact devices below, you can also find the POC attacks on my github for a voltage glitching attack on an Arduino Mega 2560. 
https://eprint.iacr.org/2016/810.pdf
https://arxiv.org/pdf/1903.08102.pdf
