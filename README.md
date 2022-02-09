# powerautomate-event_ics_file
Create an event ics file using Power Automate

# Development history
**Picture this:** 
An email from a colleague arrives with the details of an event in the message body. Since it is a meeting you need to attend, you open the the calendar of your Outlook or Gmail, pick the date, and create a new event entry, typing the Subject, Start Time and End Time, Location and other details. 

And you double check the email again to make sure no errors made. 

Sometimes, you are bogged down by other tasks on hand so you make a mental note about the event and remind yourself to read that email again closer to date. That is, if you remember.

Now, in reality the email may be sent to a fair number of people in your organisation so there could be many people adding the calendar entries independently of each other.

One best practice could be for the sender to send out the invitation directly from his calendar. Not only does it save  recipients time in reating the calendar entry themeselves, the sender can monitor the RSVP, update event details (e.g. location TBA), and the recipients can even counter propose another meeting slot. In Outlook, the sender gets an email notification about each response. It means the sender's Inbox will be constantly buzzing with response notifications, an annoyance.

In the situation where the meeting is to disseminate or update information only, there is in essense no need for the sender to receive responses.

**How to resolve this problem then?**
My solution seems simple enough: attach an ics file of the event. If the recipient is interested to attend or just want to pencil it in his calendar, he can click or import the ics file to add the event to his calendar. 

Here, I came up with the Power Automate Flowto create an ICS file  given user input on meeting details. The ics file is stored in OneDrive and can be imported into Outlook or Google calendar. 
![image](https://user-images.githubusercontent.com/82358116/153165431-c4fc0395-0f40-40d4-8055-511cc1a7a8d2.png)

![image](https://user-images.githubusercontent.com/82358116/153165834-10bd2871-6628-4be7-9971-a13f9719999e.png)
