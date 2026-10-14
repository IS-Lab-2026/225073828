Problem 1 - Bicycle Rental

- BLOCK1 : Initializes the "Scanner" object to read keyboard input from the user.

- BLOCK2 : Prompts the user to enter the starting time (0–23) and ending time (1–24). It stores the entered values in the variables "start" and "end".

- BLOCK3 : Initializes "total" to 0 to store the total rental cost and "hour" with the starting time to track each rental hour.

- BLOCK4 : Uses a "while" loop to calculate the rental cost hour by hour until the current hour reaches the ending time. It checks which time bracket the hour falls into and adds the appropriate rate to "total": 500 RWF for hours 0–6 and 21–23, 1,000 RWF for hours 7–13 and 19–20, and 1,500 RWF for hours 14–18. The variable "hour" is incremented after each iteration.

- BLOCK5 : Displays the starting time, ending time, and total rental cost in RWF. Finally, it closes the "Scanner" object.
  
