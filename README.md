# Depth_estimation_on_FPGA
Time of Flight (ToF) has revolutionised the industry by providing low cost 3D imaging. On the other hand, passive stereo vision systems which are based on multiple camera systems and feature mapping, provide high resolution depth-estimation. Both methods have their limitations, ToF suffers from low spatial resolution and is highly susceptible to noise whereas Stereo vision is very computationally complex which results in a trade-off between speed and accuracy. 

To address all these problems simultaneously, we are working on a fusion between both methods, which uses complementary features so that we can achieve good resolution and have its hardware implementation to ensure speed remains more or less intact.

This repo will contian python and verilog/VHDL implementation of all three, ToF stereo and Fusion, methods.
