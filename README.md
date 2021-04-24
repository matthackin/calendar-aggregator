# calendar-aggregator
Project to aggregate data from Google calendar

This project will get all of the events from a specific calendar ID and save them to a .csv file.

Requirements:
* `config.json` file to be completed by filling in the calendar ID you are wanting to fetch.
* `credentials.json` file from the relevant Google project
* After running `node .` it will create a link you must follow.
* Once followed the link you can log in (must be on list of approved users for the Project if it is not published)
* This will automatically create the `token.json` file.
* It should now display the events from the calendar specified.