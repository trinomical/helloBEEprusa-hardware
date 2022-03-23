# helloBEEprusa-hardware

Added STL files that modify existing AutoCalibration part files to build a DIY auto level arm

Arm is modified to suit a SPDT 125V 3A Sub-Miniature Micro Switch with Lever (lever needs to be removed)
Link to micro switch : https://www.jaycar.com.au/spdt-125v-3a-sub-miniature-micro-switch-with-lever/p/SM1036

Body is modified to allow space for screws connecting micro switch to the arm.
Body accepts SG90 Arduino servo.
Link to a SG90 servo: https://www.altronics.com.au/p/z6392-9g-180deg-plastic-servo-for-arduino/

The plastic arm provided with the servo clips into the DIY Arm.

In order to position the deploy angle better and get the arm out of the way when stowed, the servo deploy and stow angles need changing to 0 and 85 in the Marlin firmware
//#define Z_SERVO_ANGLES { 85, 0 } // Z Servo Deploy and Stow angles
