# powerautomate-event_ics_file
Create an event ics file using Power Automate

# Development history
## Scenario  
Picture this: An email from a colleague arrives with the details of an event in the message body. Since it is a meeting you need to attend, you open the calendar of your Outlook or Gmail, pick the date, and create a new event entry, entering the subject, start and end times, location and other details.  Finally you check the email once again to confirm that no errors are made. 

But really, how many of us take the trouble to create the calendar event? Sometimes I simply make a mental note to myself to read that email once again closer to date. Moreover, why bother to create a calendar event since some senders have a quirky habit of sending meeting reminders.

Now, consider the case that the email about the event is sent to a large number of people in your organisation. This means there could be many people adding the calendar entries independently of each other. Duplication of efforts.

## Possible solution: Panacea or Annoyance?
One best practice is that the sender sends the invitation directly from his calendar. Not only does it saves recipients time from having to add that calendar entry themeselves, the sender can monitor the RSVP and update event. However, this seems to come with some annoyance. In Outlook, if the sender does not disable the Response OFF when setting up the calendar entry, then he will get a RSVP email response when each recipient clicks YES/NO/MAYBE to the meeting invitation. The recipient may not  "respond" to the email, as he knows doing so can flood the inbox of the sender.

Where the purpose of the meeting is to disseminate or update information only,  responses can be [disabled] (https://www.bettercloud.com/monitor/the-academy/how-to-disable-request-for-rsvps-in-outlook-invites/#:~:text=In%20the%20new%20calendar%20invite%2C%20select%20the%20Response,check%20mark%20is%20marked%20next%20to%20the%20text.)

## How to resolve this problem then?
My solution seems simple enough: attach an ics file of the event. If the recipient wishes to attend or just wants to pencil it in his calendar, he can click or import the ics file to add the event to his calendar. 

## Technical solution
Here, I came up with the Power Automate Flow to create an ICS file given user input on meeting details. The ics file is stored in the user's specified OneDrive folder. When composing an email, the ics is attached with it. Recipients can import the .ics file to add the calendar entry into Outlook or Google calendar. 

![image](https://user-images.githubusercontent.com/82358116/153165431-c4fc0395-0f40-40d4-8055-511cc1a7a8d2.png)

![image](https://user-images.githubusercontent.com/82358116/153165834-10bd2871-6628-4be7-9971-a13f9719999e.png)
