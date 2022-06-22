# Android Introduction
-- -
## Android SharedPreferences/ Espresso Testing/Espresso Test Recorder/Android Tasks  
-- -
-- -

### Android SharedPreferences
Save Key-value data:  
- Using SharedPreferences allows you to save a small collection of key-values.  


Get a handle to shared preferences:
  - 
  - **getSharedPreferences()** — Use this if you need multiple shared preference files identified by name, which you specify with the first parameter. You can call this from any Context in your app.  
  - **getPreferences()** — Use this from an ***Activity*** if you need to use only one shared preference file for the activity. Because this retrieves a default shared preference file that belongs to the activity, you don't need to supply a name.  
        
     
    - Context context = getActivity();
      SharedPreferences sharedPref = context.getSharedPreferences(
      getString(R.string.preference_file_key), Context.MODE_PRIVATE);


### Espresso
The following code snippet shows an example of an Espresso test:  

    @Test 
    public void greeterSaysHello() {
        onView(withId(R.id.name_field)).perform(typeText("Steve"));
        onView(withId(R.id.greet_button)).perform(click());
        onView(withText("Hello Steve!")).check(matches(isDisplayed()));
    }

What does Espresso do?  
    
- Espresso tests state expectations, interactions, and assertions clearly without the distraction of boilerplate content, custom infrastructure, or messy implementation details getting in the way.  


### Espresso Test Recorder  

- The Espresso Test Recorder tool lets you create UI tests for your app without writing any test code. By recording a test scenario, you can record your interactions with a device and add assertions to verify UI elements in particular snapshots of your app. Espresso Test Recorder then takes the saved recording and automatically generates a corresponding UI test that you can run to test your app.  

-- -
-- -


