# Enfinity-T20F256-FPGA-A-three-in-a-row-robotic-arm-robot-base-on-RISC-V-
A three-in-a-row robotic![整体](https://github.com/user-attachments/assets/9d8e7fbf-3bb0-48e7-8f16-86a348eec476)
 arm robot base on Enfinity T20F256 FPGA which use Minimax algorithm ，In the version 1.0 ,we give the report and code of the project .In the future, we will give more information about the projcet. 

Since standard library functions cannot be called in the RISC-V IDE of the Efinity FPGA, it is extremely difficult to solve the attitude of the robot arm, or to convert the graphic space to the real space, so we write the chessboard position.

We use the serial steering gear of all Spirits technology, through the serial port to send signals to control the steering gear movement, if you want to reproduce this project, it is recommended to buy serial steering gear, of course, ordinary PWM driven digital steering gear is also available.

FPGA program contains RISC-V soft core and a general image processing framework, in the Src file under the vip file, gives the image processing interface, we hope that someone willing to do some coordinate acquisition, circle detection, color block recognition work, these are our lack.

Version 1.0 gives the report and rough code, and we will update it later, and give some comments to let you know more about this project and the domestic Elinx FPGA.




























