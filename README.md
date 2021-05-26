# Notion-and-Google-Calendar-2-Way-Sync
2 Way Sync Between Notion Database and Google Calendar

https://www.youtube.com/watch?v=j1mh0or2CX8 This video was used to make the Google Calendar token. Note that the library names that they "pip installed" are outdated so look at the python file to see what you'll actually need to pip install onto your computer.

The Google Calendar token is what allows for the python code to access your Google Calendar and communicate with the Google Calendar servers to add/receive/modify data.

You'll need to make your GCal token before setting up the rest of the Python script. Use the GCalToken.py file to create your token when you have downloaded the JSON credentials (follow the above youtube video). 

I'm not sure if this is the first one out there, but it is the only 2-way synchronous project I could find so that's pretty cool :)


The functionalities:

- Take existing events from your Notion Dashboard and bring them over to Google Calendar
- If the Notion event has only a date, then the GCal event is made at 8 am 
- If the Notion even has a date and time, then the GCal event is made at the appropriate time
- If the event is already in both GCal and Notion, but you switch the date/time on either, it will sync with the new value across both platforms
- If the event is only in GCal, it will be brought over to Notion, as well as the description of the event that you add from GCal 

When making events, the code will extract the event name, date/time, a category, and text from the Notion Dashboard and integrate that information into your GCal event. Additionally, it will also add a URL source code the GCal event so you can click on the URL and automatically be brought over to the specific Notion Page that your event is at. 


Some more visibility through some upvotes on my Reddit post would be appreciated and I think may bring along some new users to this resource! [Reddit Post](https://www.reddit.com/r/Notion/comments/nlj77o/its_finally_here_unlimited_2way_sync_with_google/)