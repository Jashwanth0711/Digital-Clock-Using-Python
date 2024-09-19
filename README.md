# Digital-Clock-Using-Python
Python Tkinter Digital Clock
This is a simple digital clock application built using Python's Tkinter library. The clock displays the current time, day of the week, and date, updating every second.

Features:
1.Displays current time in 12-hour format (HH:MM
AM/PM)
2.Shows the current day (e.g., Monday)
3.Shows the current date (e.g., September 19, 2024)
4.User-friendly interface with customizable font and color
Requirements:
1.Python 3.x
2.Tkinter (usually comes pre-installed with Python)
How to Run:
python clock.py
Code Overview:
The application uses the Tkinter library for the GUI and the time module to fetch the current time and date. The clock updates every second using the window.after() function.

Key Functions:
update(): Fetches the current time, day, and date using strftime() and updates the Label widgets accordingly.
Example Output:
Time: 11:23:45 AM
Day: Thursday
Date: September 19, 2024
