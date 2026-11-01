# AUTOMATIC_NUMBERPLATE_DETECTION
Automatic number plate detection and low-light enhancement on the DE2-115 FPGA (Cyclone IV). An OV7670 camera feeds a Verilog pipeline that captures a 320x240 Y image, finds the plate via adaptive Sobel-X edges and row/column peak finding, applies contrast-limited histogram equalisation, and shows the boxed result on VGA.
