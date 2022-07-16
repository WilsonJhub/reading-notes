# Reading Notes

## Intent Filters
-- -

### Add an Intent Filter  

In order to properly define which intents your activity can handle, each intent filter you add should be as specific as possible in terms of the type of action and data the activity accepts.

The system may send a given Intent to an activity if that activity has an intent filter fulfills the following criteria of the Intent object:

_**Action**_  
A string naming the action to perform. Usually one of the platform-defined values such as ACTION_SEND or ACTION_VIEW.
Specify this in your intent filter with the <action> element. The value you specify in this element must be the full  
string name for the action, instead of the API constant (see the examples below).

**_Data_**  
A description of the data associated with the intent.
Specify this in your intent filter with the <data> element.  
Using one or more attributes in this element, you can specify just the MIME type, just a URI prefix, just a URI scheme, or a combination of these and others that indicate the data type accepted.