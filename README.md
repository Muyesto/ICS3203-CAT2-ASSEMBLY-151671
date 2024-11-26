# ICS3203-CAT2-ASSEMBLY-151671
#QUESTION ONE: CONTROL FLOW AND CONDITIONAL LOGIC#
-The program basically prompts the user for input which it then classifies the number either as positive, negative or exactly zero. It then displays the ouput.

-To run the code you have to save the code as a .asm file. Assemble it using NASM, link the file and then run the program.

-Gained conssiderable knowledge on how input and output works in assembly and also how branching logic operates in assembly.

#QUESTION TWO#
-The program prompts the user to enter 5 integers which are then reversed using pointers at each end which swap numbers until they meet in the middle.

-To run the code you have to save the code as a .asm file. Assemble it using NASM, link the file and then run the program.

-I encountered a couple of challenges such as errors in addressing or lengths often resulted in incorrect outputs or crashes and ensuring that all conditions were covered without unintended fall-throughs or skipped cases.

#QUESTION THREE#
The following is a short summary of how the stack was used:

push ebp	    - Save the caller's base pointer.
mov ebp, esp  - Create a new stack frame.
push ebx	    - Save the caller's value of ebx.
push eax	    - Pass the argument (n-1) to recursion.
pop ebx	      - Restore the caller's value of ebx.
mov esp, ebp	- Restore the caller's stack pointer.
pop ebp	      - Restore the caller's base pointer.


#QUESTION FOUR#

The sensor value is stored in the memory location.
The program reads this value into the AL register.
Based on this value, the program uses conditional comparisons  and branching instructions to determine the action.
If the water level is low, the program turns on the motor.
If the water level is too high, the program triggers an alarm.
If the water level is moderate, the motor is stopped.


























