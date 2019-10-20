# Extract data from Google Calendar

### Description:
Assume that you work and get paid based on hours you have worked. You note working hours in your Google Calendar, and you send your working ours to your manager in every xy time period. This program creates a file with the working hours you can send directly saving time on doing it "by hand".

### Usage:
To use this program you have to create a Google CalendarAPI. (See links below.) For the first use you have to sign in to your Google account, but after that you can save the credentials you need to log in so you don't need to sign in every time.

In your calendar consistent naming is essential. You have to name all events the same.

As some work late at night the last days work can be finished at the following days morning (like 1am or 2am) the code counts these to the previous day (when work started).

At the end the program counts the total time of work in hours.

![alt text][https://raw.githubusercontent.com/danielkovacsdeak/extract-data-from-calendar/master/oneWeek.png]

Output: hours.txt

Credits: [Google Developers](https://developers.google.com/calendar/quickstart/python), [Towards Data Science](https://towardsdatascience.com/accessing-google-calendar-events-data-using-python-e915599d3ae2)
