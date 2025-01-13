# Time Conversion Script

## Overview This script converts time ranges from a 12-hour format (AM/PM) to a 24-hour format. It takes user input, validates the format, and outputs the converted time range. 

## How It Works The script consists of three primary functions: 

1. **main()**: This is the main entry point of the script. It prompts the user to enter a time range and calls the `convert()` function to process the input.
2. **convert(s)**: This function takes a string input representing a time range, validates and formats it using regular expressions, and returns the converted time in a 24-hour format. If the input format is incorrect, it raises a `ValueError`.
3. **format(hour, min, am_pm)**: This function takes individual components of time (hour, minute, AM/PM) and converts them to a 24-hour format. It returns the formatted time as a string.

Prompts the user to input a time range in 12-hour format.

Calls the convert() function to process the user input.

Prints the converted time range in 24-hour format.

Uses a regular expression to validate the input format.

Extracts the time components (hour, minute, AM/PM) from the input string.

Validates that the hours are within the 12-hour format range.

Calls the format() function to convert both start and end times to 24-hour format.

Returns the converted time range in 24-hour format.
Converts the hour component based on AM/PM.

Handles cases where the hour is 12 AM or 12 PM.

Ensures that the minute component is properly formatted.

Returns the formatted time in 24-hour format as a string.

### Example
input:    Hours: 9:00 AM to 5:00 PM

output:    9:00 to 17:00
