# Good Morning Apple Scripts

The best way to implement these scripts is through Automator, where you would add a 'run Applescript' section, inside which you would que all the scripts you would like to be run. Export the automator as a Calendar event, and change when the automator script ques from the event created in teh Calendar (change it to the time you usually week up, obviously up to you to customize if you wake up at a different time on weekends vs weekdays, day by day wakeup times, etc)

The automator runscript is entitled 'automatorRunScripts.scpt', which you would copy-paste into the Automator Applescript Node.


## spotifyWakeUp

Slowly wake up to a randomized song from your favorite playlist. To start, input your username and the uri for your playlist. To get over some odd spotify randomization glitches, the script turns on shuffle and skips the first song to ensure a random song. The script also increments the volume slowly until 'wakeup', feel free to change how fast it increments and by how much



## readiCalEvents

Have your personal butler read off your daily events from the Calendar app on MacOS, which have been integrated through Google Calendar, or any type of calendar for that matter, as long as the events exist in the local Calendar application.


## readTodoistTasks

Have your personal butler read off your Todoist tasks from the Calendar app on MacOS. The best way to do this is integrate Google Calendar into your local Calendar application, and then integrate Todoist with your Google Calendar for your tasks to properly appear in the Calendar app and be read properly.

