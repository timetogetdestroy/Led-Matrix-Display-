# Led-Matrix-Display-

This project is a software-based LED matrix display simulation programmed in 8086 assembly language. It demonstrates scrolling text functionality by continuously shifting characters across the screen. The program utilizes BIOS interrupt calls for text rendering and screen manipulation, making it a great learning project for interfacing with low-level hardware controls.

1- FEATURES:

✔️ Scrolling Text – The text message moves from right to left continuously.

✔️ Screen Clearing – Ensures a smooth display without overlapping characters.

✔️ Delay Mechanism – Adds a delay to control scrolling speed.

✔️ Assembly Language Implementation – Uses 8086 assembly and EMU8086 emulator.

2- HOW IT WORKS:

1- The message is stored in memory and displayed at the center of the screen.

2- A loop continuously shifts the text one character to the right.

3- The screen is cleared before displaying the updated text.

4- A delay function is used to control the speed of the scrolling effect.

3- How to Run the Code

Step 1: Download the Source Code

Clone this repository using the command:

https://github.com/timetogetdestroy/Led-Matrix-Display-.git

4- REQUIREMENTS:

1- EMU8086 Emulator (or any x86 assembly simulator)

2- Basic knowledge of 8086 assembly language

5- USAGE:

1- Load the code in EMU8086.

2- Run the program to see the scrolling text animation.

3- Modify the msg variable to display custom text.

6- APPLICATIONS:

✅ Visual text displays

✅ Learning hardware interfacing with LED matrices

✅ Understanding BIOS interrupt-based screen control
