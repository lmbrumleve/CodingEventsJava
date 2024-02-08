# Purpose

The Coding Events app is useful for keeping track of various coding related events. 

# Current State of the App
The app in its current state allows a user to create different categories of events in the app, 
and then log details about the particular events in those categories. 
There is also a feature to create tags for events, such as #java or #javascript.

Once an event category and its corresponding events have been created, 
all of the details are stored persistently in a database. 
The user can view a list of the events that have been created, 
as well as a list of the event categories and event tags. 
Within these lists are clickable links, 
that will take the user to useful information about the particular event or event category they have selected.

There is also functionality for the user to delete events.

# Future Improvements

The app could be improved by adding a section on the "Create Event" page for the user to be able to add specific tags to specific events as they are created.

Another feature that would improve the app would be to allow the user to sign up for an account, so that they can follow the events they are most interested in and keep track of their calendar of events.

In order to do this, a Person class needs to be added that would have the following fields: 
- id
- firstName
- lastName
- email
- password

The class would need getters for each of these fields, and setters for every field except for id.

Another class could be created for all of the profile information for the person, called PersonProfile. This class could include more information about the user such as:
- List<Events> eventsAttending(a list of events the user is planning to attend)
- List<Events> eventsOwned (a list of events the user has created)

It would also be good to add a date field to the Events class, and then to create a calendar view based on the PersonProfile with all of their eventsAttending mapped onto the calendar view.
