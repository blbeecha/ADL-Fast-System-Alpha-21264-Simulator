# ADL-Fast-System-Alpha-21264-Simulator
ADL/Fast System Implementation of Alpha 21264 Tournament Predictor for CS4431

A simulation of the processor description which implements a 6-stage pipeline. This pipeline implements a processor which has a separate register file read stage. 
It implements branch direction prediction using the gshare algorithm or Alpha 21264 tournament predictor depending on which predictor flag is high. 
It also includes a BTB and a return address stack for branch prediction. 
Branch instructions resolve in EX and in case of a misprediction, incorrectly fetched instructions are squashed from the earlier stages. 

This simulator was designed and tested with the ADL/Fast System compiler. 
The report outlines the major benefits of the tournament predictor by comparing gshare to the tournament predictor. 
This project was for CS4431 Computer Architecture at Michigan Technological University.
