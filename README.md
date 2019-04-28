# PYNQ-ZC702
PYNQ image build for ZC702 board

1. Download zc702-2.4.img.zip
2. unzip the image file
3. Writing Img to SD card ref.[https://pynq.readthedocs.io/en/latest/appendix.html#writing-the-sd-card]
4. Boot ZC702 board from SD card by switch SW16 to(0,0,1,1,0)
5. Connect ethernet cable to board and set a IP address manually.
   1. Open Tera connect to board via serial port
   2. Typing command: ifconfig eth0 IP_ADDRESS
6. Open browser and typing IP_ADDRESS of the ZC702 board to open jupyter notebook(password is xilinx)