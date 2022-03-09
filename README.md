# Super_Stopwatch

At a high level, here’s what your program will do: 

1. Track the amount of time elapsed between presses of the enter key, with each key press starting a new “lap” on the timer. 
2. Print the lap number, total time, and lap time.Keeping Time, Scheduling Tasks, and Launching Programs 

This means your code will need to do the following: 

1. Find the current time by calling time.time() and store it as a timestamp at the start of the program, as well as at the start of each lap. 
2. Keep a lap counter and increment it every time the user presses enter. 
3. Calculate the elapsed time by subtracting timestamps. 
4. Handle the KeyboardInterrupt exception so the user can press ctrl-C to quit
