Periodic Table of Elements.ed
Version 1 (Greek Edition)

Using the Application:
1. Click on an Element to see more information
2. Click on Language Greek or Αγγλικά to change language (also change the character of decimal point)
3. Click on Change Monitor or Αλλαγή Οθόνης to change to next monitor (if your system have two or more monitors, all of them with different content).
4. Terminate the Application clicking on Exit Application

This program use no cpu cycles when waiting for input.

There are three files (in a folder) to run it (without installation run on a Windows OS pc, from XP and above):
lib.bin (library)
per_pinakas.exe
per_pinakas.gsb

Program to change (and produce the per_pinakas.gsb) is the period_pinakas.gsb which is a UTF8 text file.


You can download and setup M2000 Interpreter (with the help base) if you want to change the program.
You can change the code through these steps:
1. Load the period_pinakas.gsb
2. edit the module a which is the code of the program (press Esc to exit edit)
3. save the program using CTRL+A (this place the save command$)
4. save the "Executable" which is the script "scrabled" by the standard password
5. Open the current directory and using Explorer move the per_pinakas.gsb to the execution folder. This folder has two more files, the lib.bin (is actually the m2000.dll) and the per_pinakas.exe (is actually the m2000.exe) which do two things: Load the lib.bin and not any other m2000.dll (including the one which we have to write/edit programs), then load and run the per_pinaks.gsb. When we have a  file which are scrabbled with the standard password the Ctrl+C, the Esc key and the Break key not working to stop the program. We can terminate the program by using a click on label Τέλος Εφαρμογής.
This program use 0 cpu cycles if we didn't click on an element


These are the commands from M2000 Interpreter console:
load period_pinakas
edit a 
save command$
save "per_pinakas.gsb" @, {a:end}
win dir$
End