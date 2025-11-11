Task 1 (setup & header): Script header comment + welcome message.


Task 2 (input & data collection): Prompts for number of entries and loops to collect Student name and Check-in time storing them in a dictionary.


Task 3 (data validation):


Rejects blank names with message "Name cannot be empty."


Re-prompts until a valid timestamp in HH:MM AM/PM is provided.


Prevents duplicate names (skips duplicate entry and warns).


Task 4 (attendance summary): Prints a formatted table using f-strings and alignment; shows total present.


Task 5 (absentee validation): Optionally asks for class strength and prints total absentees.


Task 6 (bonus: save to file): Optionally saves attendance_log.txt with timestamps and counts; uses current datetime.
