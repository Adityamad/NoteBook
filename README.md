# NoteBook
Notes Taking App 

I learn android architecture which is correct way to organize and bind and store the data and connect with the mainActivity. This application stores your data and add the noes and give features to add and remove the note in the app. In android architecture are made up room, Work manager, Lifecycle , Paging , Navigation and data binding. The control flow to use the android architecture is firstly start with room database(which manages local data , SQLite data sources using objects) which have entity , SQLite and DAO that is data access object and then go to next step that is Repository which is single source of truth for all app data, clean API for UI to communicate and then move to View model which holds all the data needed for the UI , View Model is one which is use in Main Activity and then the final step that is UI Controller(Activtiy) , it displays data and forward on UI events. When you click on submit then note is inserted in the application then it will store the note data and not erase even you close the app.


First Case : Here, User allowed to enter the quick note.

![1notebook](https://user-images.githubusercontent.com/62170581/125393780-2fce2180-e3c6-11eb-9d9e-9d9e8bbc3746.jpeg)


Second Case : Suppose, We have entered "The Family Man and press on to the submit button", a POP-UP notification is shown with "The Family Man Inserted".

![2notebook](https://user-images.githubusercontent.com/62170581/125393801-38265c80-e3c6-11eb-8d79-28627334a1fb.jpeg)


Third Case : Here, We have entered the second data which is "FAANG" and press on to the submit button, a POP-UP notification is shown with "FAANG".

![3notebook](https://user-images.githubusercontent.com/62170581/125393808-3bb9e380-e3c6-11eb-8d64-225ed9caf7b2.jpeg)


Fourth Case : Here, we have deleted "FAANG" with the help of delete button, which is in the corner of the each notes. And a POP-UP notification is shown with "FAANG Deleted".

![4notebook](https://user-images.githubusercontent.com/62170581/125393814-3eb4d400-e3c6-11eb-9d13-19f00d0284db.jpeg)


Fivth Case : Here, We have checked, whether the notes, that we have created is stored into the app after killing that application.

![5notebook](https://user-images.githubusercontent.com/62170581/125393825-45434b80-e3c6-11eb-9d86-5a8d630e194d.jpeg)


