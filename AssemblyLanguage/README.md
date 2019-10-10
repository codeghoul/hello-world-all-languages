RUNNING AN ASSEMBLY LANGUAGE PROGRAM IN MASM ENVIRONMENT


You should follow the instructions for setting up MASM: Configuring MASM 6.11 from your home computer

You should create a folder where you will keep all of your .ASM files (for example, COP3402). Use Windows Explorer to create the folder.

Testing if MASM is installed properly

If you have set up MASM correctly, then you should be able to open a DOS Window and type the command MASM. You should get an error message, but it won't say "Bad Command or File Name". If you get a message indicating that you have used the command incorrectly, then you have installed MASM correctly.
If you do the above and you get the error "Bad Command or File Name", then you have not installed MASM properly. If you get this error, then try the command C:\MASM611\BIN\MASM. You should get an error message, but it won't say "Bad Command or File Name". If you get a message indicating that you have used the command incorrectly, then recheck the link: Configuring MASM 6.11 from your home computer. You have set up the PATH incorrectly.
If you still get the "Bad Command or File Name" error, then you have either installed MASM in a directory other than C:\MASM611, or your installation is really messed up.
If you installed MASM in a directory other that C:\MASM611, then replace C:\MASM611 in the command in step 2 above with the path where you installed MASM.
If you installed MASM in C:\MASM611, then you should reinstall MASM.
Once you are sure that MASM is installed correctly, then you can follow these steps.

Go to Start, Programs, MS-DOS Prompt (or Command Window). Once the DOS window is open, type the command EDIT. Type your file and save it to your .ASM directory (for example, C:\COP3402). Be sure it has a .ASM extension. Do not close the DOS window or the editor.
Go to Start, Programs, MS-DOS Prompt (or Command Window). This will open a second DOS window. Change to your .ASM directory (for example, C:\COP3402) and issue the commands to run MASM. Assuming your file is named FIRST.ASM, then these commands will change to your .ASM directory (for example, C:\COP3402) , compile, link and run it.
C:
cd \COP3402
MASM/L HelloWorld.ASM
LINK HelloWorld.OBJ
HelloWorld.EXE
If you have any errors after issuing the MASM command, then you will need to fix your .ASM file and redo the above steps. You can open the file FIRST.LST to see where all your errors are, but you must change the FIRST.ASM file, not the FIRST.LST file. You will not need to change directories again, so you only need two commands to compile, link, and run the program.
MASM/L HelloWorld.ASM
LINK HelloWorld.OBJ
HelloWorld.EXE