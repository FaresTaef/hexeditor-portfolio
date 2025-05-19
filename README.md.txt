# HEX/BIN/CHAR File Editor (C++ Portfolio Project)

This is a terminal-based file editor built in C++ for the IU "Programmierung mit C/C++" course.

## 📌 Features
- Open a binary file
- View contents in:
  - HEX (Hexadecimal)
  - BIN (Binary)
  - ASCII (Character Representation)
- Edit any byte directly (HEX value)
- Save changes (overwrite or save as a new file)

---

## ⚙️ Compilation
```bash
g++ -o hexeditor main.cpp FileLoader.cpp Formatter.cpp Display.cpp Editor.cpp SaveHandler.cpp

Usage 
Running the Programm:
./hexeditor sample.bin

Editing Bytes:

Offset |   HEX   |    BIN     | CHAR
---------------------------------------
000000 | 48     | 01001000 | H
000001 | 65     | 01100101 | e
000002 | 6C     | 01101100 | l

You can enter an offset (byte position) and a new HEX value to change:

Edit mode - enter offset and new hex value (e.g., 5 A3), or 'q' to quit:


Example 

Compile the Program

g++ -o hexeditor main.cpp FileLoader.cpp Formatter.cpp Display.cpp Editor.cpp SaveHandler.cpp

Run it with Binary File:
./hexeditor sample.bin

Edit Bytes value with HEX:
For example, change byte at position 3 to FF:

Edit mode - enter offset and new hex value (e.g., 3 FF), or 'q' to quit:

























