# IOT-SECURITY-LOCK-AND-ALERT-SYSTEM-USING-RFID
The purpose of this project is to present a secure smart door lock which is intended to offer high security, easy access, and control.
Therefore, the proposed system makes use of RFID tags and GSM modules to implement a secure but easy-to-use system. It has the possibility to replace the traditional door lock system. By using the proposed method, the security of the household can be enhanced at a very low cost.
The RFID reader communicates with the Arduino through the SPI protocol and different Arduino boards have different SPI pins.
To test if the RFID reader is working properly or not, upload the “dumpinfo” from the examples in the Arduino and see if it is showing the information of the tags on the serial monitor or not.
If you are new to RFID, then follow this tutorial | RFID basics and RFID module interfacing with Arduino
The I2C LCD communicates with the Arduino through the I2C protocol.
Different Arduino boards have different I2C pins. The I2C pins on Arduino Uno and Arduino Nano are A4, A5.
Next connect the keypad with Arduino. The 4X4 keypad has 8 connections but we don’t require the last column of keypad. We only require numbers for the password. 
So we won’t use the last pin of keypad which is for fourth column.You can also use 4X3 keypad instead of 4X4 keypad.
Next connect the Led's, servo and buzzer with the Arduino as shown in the below diagram.
In the end, connect the power source to the Arduino. I have used three 18650 cells. We can give 6 to 12V to the Arduino through the barrel jack.
The initial password is ‘1234’.
