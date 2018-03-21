This is a protoytpe, a little bit buggy, but still work.
The purpose for this application is to exame the brainwave response according to different size throught visual stimuli.

System Requirement:
1. Windows System 8 or 10
2. Visual Studio 2017
3. Neurosky Brainwave headset(black)
4. GLFW/GLEW install (when you open vs2007, make sure you assign the library)
5. Bluetooth device on your computer
6. Think Gear Connection (optional)
7. C++ install (version 11)

Preparation:
1. Pair you Brainwave headset to the computer
2. Download "MindWaveMobile Tutorial"
3. Run the program and check your headset connecting "COM" (ex.COM5...COM6)

Instruction:
1. open the "Algo SDK Sample" file.
2. double click the visual studio file (Algo SDK Sample.sln)
3. on the right Solution Explorer Window, 
   right click the "Algo SDK Sample" and make sure the GLFW/GLEW libraries are linked
4. Open "Algo SDK Sample.cpp" under "Source Files"
5. On line 117 (from the c++ code), change the "COM" to your headset connecting com (very important otherwise, no brainwave data)
6. on top tab of the main window, select "Build" -> "Build Solution"
7. Run "Local Windows Debugger"
8. A system connect to port window will show up
9. Select algorithm on the right size click "Init" on the left
10. Once you click the start, wait for 5 second, a animation will show up as well as your brain wave data.
11. click pause to stop the recording 

Exported File:
After you run the program, the "data.text" file will generate in the "Algo SDK Sample".
The data contains all the animation size in response of every second.
