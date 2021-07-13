# NoteBook
Notes Taking App 

I learn android architecture which is correct way to organize and bind and store the data and connect with the mainActivity. This application stores your data and add the noes and give features to add and remove the note in the app. In android architecture are made up room, Work manager, Lifecycle , Paging , Navigation and data binding. The control flow to use the android architecture is firstly start with room database(which manages local data , SQLite data sources using objects) which have entity , SQLite and DAO that is data access object and then go to next step that is Repository which is single source of truth for all app data, clean API for UI to communicate and then move to View model which holds all the data needed for the UI , View Model is one which is use in Main Activity and then the final step that is UI Controller(Activtiy) , it displays data and forward on UI events. When you click on submit then note is inserted in the application then it will store the note data and not erase even you close the app.

First Case : Here, User allowed to enter the quick note.

Screenshot (454)

Second Case : Suppose, We have entered "Elon Musk and press on to the submit button", a POP-UP notification is shown with "Elon Musk Inserted".

Screenshot (455)

Third Case : Here, We have entered the second data which is "Mukesh Ambani" and press on to the submit button, a POP-UP notification is shown with "Mukesh Ambani Inserted".

Screenshot (456)

Fourth Case : Here, we have deleted "Mukesh Ambani" with the help of delete button, which is in the corner of the each notes. And a POP-UP notification is shown with "Mukesh Ambani Deleted".

Screenshot (457)

Fivth Case : Here, We have checked, whether the notes, that we have created is stored into the app after killing that application.

Screenshot (458)

