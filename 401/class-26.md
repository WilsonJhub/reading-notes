# Android Fundamentals
-- -
-- -
## Application fundamentals
-- -

### Application components  
There are 4 application components
1. Activities  
2. Services  
3. Broadcast receivers  
4. Content providers  

- ***Activity:*** An activity is the entry point for interacting with the user. It represents a single screen with a user interface.  
  - *Example:* an email app might have one activity that shows a list of new emails, another activity to compose an email, and another activity for reading emails.  
- ***Services:*** A service is a general-purpose entry point for keeping an app running in the background for all kinds of reasons. It is a component that runs in the background to perform long-running operations or to perform work for remote processes.  
  - *Example:* a service might play music in the background while the user is in a different app, or it might fetch data over the network without blocking user interaction with an activity.
- ***Broadcast receivers:*** A broadcast receiver is a component that enables the system to deliver events to the app outside of a regular user flow, allowing the app to respond to system-wide broadcast announcements. Because broadcast receivers are another well-defined entry into the app, the system can deliver broadcasts even to apps that aren't currently running.  
  - *Example:* an app can schedule an alarm to post a notification to tell the user about an upcoming event... and by delivering that alarm to a BroadcastReceiver of the app, there is no need for the app to remain running until the alarm goes off.  
- ***Content providers:*** A content provider manages a shared set of app data that you can store in the file system, in a SQLite database, on the web, or on any other persistent storage location that your app can access. Through the content provider, other apps can query or modify the data if the content provider allows it.  
  - *Example:* the Android system provides a content provider that manages the user's contact information. As such, any app with the proper permissions can query the content provider, such as ContactsContract.Data, to read and write information about a particular person.  
-- -
-- -

Source: [Android Fundamentals](https://developer.android.com/guide/components/fundamentals)