# Python-Reminder-Bot
A Python reminder bot that stores a time-table in a .json file and sends a windows notification as a reminder.

# Requirements
## Plyer
This bot uses Plyer to send Windows notifications.

You can download Plyer through pip using `pip install plyer`.

If pip does not work, check out [this post](https://stackoverflow.com/questions/23708898/pip-is-not-recognized-as-an-internal-or-external-command) on Stackoverflow

## JSON File
store your desired shedule in a JSON file named `schedule.json`

the `schedule.json` file must be in the same directory as script, or provide full path to JSON file in the main script.

Uses the military-time format/24-hour format.

