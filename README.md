# Electronic-code-lock-with-multiple-user

Electronic code lock system using 8051 microcontroller,
which provides control to the actuating the load. 
It is a simple embedded system with input from the keyboard and the output being actuated
accordingly.
This system demonstrates a Password based electronic Lock System using 8051 Microcontroller,
wherein once the correct code or password is entered, the lock is opened and the concerned person is allowed access to the secured area.
Again, if another person arrives, it will ask to enter the password.
If the password is wrong, then lock would remain closed, denying access to the person.


The main component in the circuit is 8051 controller.
In this project, a 4×4 Matrix Keypad is used to enter the password.
The password which is entered is compared with the predefined password.
First the ID of the user is entered  if the ID is correct then it will ask you to enter the password.
If the entered password is correct, then the system opens the lock or door by rotating motor and displays the status of lock on LCD.
If the password is wrong, then the lock  remains closed and displays Access denied on LCD.
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




