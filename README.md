# powerautomate-event_ics_file
Create an event ics file using Power Automate

# Development history
## Scenario  
Picture this: An email from a colleague arrives with the details of an event in the message body. Since it is a meeting you need to attend, you open the the calendar of your Outlook or Gmail, pick the date, and create a new event entry, typing the Subject, Start Time and End Time, Location and other details. 

And you check the email again to make sure no errors made. 

Sometimes, you can't even be bothered to add a calendar entry as you are bogged down by other tasks on hand so you make a mental note about the event and remind yourself to read that email again closer to date. That is, if you remember. Moreover, the sender has a habit of sending email reminders about the event!

Now, in reality the email may be sent to a fair number of people in your organisation so there could be many people adding the calendar entries independently of each other. Duplication of efforts.

One best practice would be for the sender to issue the invitation directly from his calendar. Not only does it saves  recipients time in adding that calendar entry themeselves, the sender can monitor the RSVP and update event details (e.g. location TBA), and the recipients can even counter propose another meeting slot. However, this seems to come at the price of annoyance:  In Outlook, the sender gets an email notification about each response (YES, NO, MAYBE). The recipient, knowing it, may not  "respond" to the email, knowing that it only generates another email for the sender.

In the situation where the meeting is to simply to disseminate or update information only, it makes little sense for the sender to receive responses.

## How to resolve this problem then?
My solution seems simple enough: attach an ics file of the event. If the recipient wishes to attend or just wants to pencil it in his calendar, he can click or import the ics file to add the event to his calendar. 

## Technical solution

Here, I came up with the Power Automate Flow to create an ICS file  given user input on meeting details. The ics file is stored in the user's specified OneDrive folder and can be imported into Outlook or Google calendar. 

![image](https://user-images.githubusercontent.com/82358116/153165431-c4fc0395-0f40-40d4-8055-511cc1a7a8d2.png)

![image](https://user-images.githubusercontent.com/82358116/153165834-10bd2871-6628-4be7-9971-a13f9719999e.png)
