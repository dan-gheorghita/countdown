# countdown.py

**Countdown Script Analysis**

**Overview**

The `countdown.py` script is a simple Python program that counts down from 60 seconds and plays an alarm sound at the end of the countdown.

**Code Breakdown**

### Importing Modules

The script starts by importing two Python modules:

* `time`: provides functions for working with time and dates
* `subprocess`: allows the script to execute external commands, such as playing a sound file

### Countdown Loop

The script then enters a `while` loop that continues until `timeLeft` is less than or equal to 0. Inside the loop:

1. `print(timeLeft, end='')`: prints the current countdown value (`timeLeft`) to the console, without adding a newline character (`end=''`).
2. `time.sleep(1)`: pauses the script for 1 second, allowing the countdown to decrement at a rate of 1 second per iteration.
3. `timeLeft = timeLeft -