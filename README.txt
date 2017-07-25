Steps taken to permanently pair both Wii Balance Boards

--------- One time setup

0: Ensure that no wii board is connected/recognized. You can remove
   exisiting wii boards by going to devices/printers and removing them
   from there.

1: Navigate to C:/Program Files(x86)/WiiPair. Run the WiiPair .exe as administrator
   (right click on it and hit run as administrator). A black console will open that
   continuously prints scanning along with other messages.

2: While it is scanning, hit the sync button on both Wiiboards. If the black window
   prints that it successfully paired to two wiidevices and closes, then it was successful. 
   If it only paired to one device, start over from the beginning. And if it prints an
   error message, then it will keep scanning and trying. If that happens, try hitting the 
   sync buttons again, or restarting the WiiPair.exe as administrator again.

---------- How to switch boards

3: After the boards have been paired, you will see that both lights on the board start blinking.
   This means that they are waiting for the computer to connect to them, which you can do by
   starting up the MatLab program. The MatLab program will connect to one of them, and that one's
   light will stop blinking and stay a solid blue. 
   If you wanted to switch boards, you can then turn off the current board (by pulling a battery 
   out then putting it back in). This may cause MatLab to crash, so it's a good idea to exit MatLab 
   before you do this. At this point, the other board should still be blinking, and the current one 
   should be powered off and not blinking. Start up the MatLab program, and it will connect to the 
   board that is blinking, and the blinking will stop. 
   If you wanted to switch back to the other board that is currently off, you can now
   exit MatLab, turn off the current board, hit the power button on the powered-down board, and then
   observe that it is now blinking. You can now start MatLab again.
   Note that both boards will turn off if the computer turns off. To connect to them again once the
   computer has been powered on again, simply press the power button on the desired board to start
   it blinking, and then start the MatLab program.


- Ty Coghlan