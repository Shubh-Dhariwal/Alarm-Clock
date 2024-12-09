Key Features:
Input Time Format:

The program now supports the 12-hour format with AM/PM. Example:
07:30:15 AM for 7:30:15 in the morning.
08:45:20 PM for 8:45:20 in the evening.
Time Validation:

Uses the DateTimeFormatter class to validate and parse the time input.
Regex ensures that the time is in HH:MM:SS AM/PM format.
Alarm Matching:

Compares the current system time (in 24-hour format) with the parsed alarm time by converting them both to LocalTime.
Alarm Sound:

Plays the selected .wav file when the alarm rings.
Steps to Use:
Run the Program: Compile and execute the code.
Set Time: Enter the alarm time in HH:MM:SS AM/PM format.
Choose Song: Select a .wav file as the alarm sound.
Set Alarm: Click the "Set Alarm" button to activate the alarm.
Example Input:
Alarm Time: 10:15:30 AM
Alarm Sound: Select a .wav file (e.g., alarm.wav).
Notes:
Ensure the computer's system time is correctly set to AM/PM for precise triggering.
Only .wav files are natively supported for the alarm sound. Use a library like JLayer for .mp3 support if needed.
