# Electronic-code-lock-with-multiple-user

Electronic code lock with multiple user ID and password system using 8051 microcontroller,
which provides control to unlock the lock or door. 
It uses embedded system with input from the keypad and the output can be unlocking lock or door.
This system is a Password based electronic Lock System using 8051 Microcontroller,
wherein once the correct ID is entered and then the code or password is entered, the lock is opened 
Again, for the next user the ID and poassword is required to enter.

A 4×4 Matrix Keypad is used to enter the password,16x2 LCD is used for display,one Buzzer is used for security purpose,one motor or actuator is used.
The password which is entered is compared with the predefined password.
First the ID of the user is entered  if the ID is correct then it will ask you to enter the password.
If the entered password is correct, then the system opens the lock or door by rotating motor and displays the status of lock on LCD.
If the password is wrong, then lock would remain closed, and the access will not be granted and the LCD will show access denied.
Password can be entered 5 times and number of count left is displayed on the LCD.  

#Operation
1) Enter the User ID and press '#' on keypad.
2) If ID is correct LCD will display CORRECT ID.
3) Enter the 5 digit Password and 'press D' on keypad.
4) If password is correct LCD will display ACCESS - GRANTED.
5) Lock is unlocked.


#Connection

1)LCD is connected to port 0.

2)Motor is connected to P2.0 and P2.1.

3)Buzzer is connected to P2.3.

4)Keypad is connected as --ROW to P3.0 to P3.3 and COL to P1.0 to P1.3.

#Password

1)Three IDs are ABC, BAC, CAB.

2)Three passwords are 55419 , 12345 , 54321.




