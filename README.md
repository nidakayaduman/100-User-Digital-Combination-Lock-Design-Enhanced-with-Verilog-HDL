# 100-User Digital Combination Lock Design Enhanced with Verilog HDL
 
In this project, Verilog HDL was used to develop a digital combination lock with 100 distinct passwords. A keyboard encoder, a mode switch, and a ROM are all part of the design. The keyboard encoder detects pressed keys and develops signals showing the numbers associated with those keys. In user ID mode, the slider detects key presses and displays the user ID on a seven-segment display. The pushed keys are communicated to the selector pwd block in password enter mode, causing the LEDs to spin progressively. When the user passwords saved in ROM are compared to the entered password, the "GRANTED" LED glows; otherwise, the "DENIED" LED glows. The timer block illuminates the LEDs for a set amount of time. The design was realized in a fully synchronous structure, and the inputs, outputs, and functions were optimized to meet the project's needs.
