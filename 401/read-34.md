# Google's App Publishing Guide
-- - 

# Publishing Your Application
*When you publish your android application, you make the app available to users.* 

-- - 

### Preparing your app for release. 

There are a few steps that you need to complete when preparing your application for launch.  

1. Configure you application for release:
   - At a minimum, you need to remove `Log` calls and remove the `android:debuggable` attribute from your manifest file. 
   - Provide values for the `android:versionCode` and `android:versionName` attribute, which are located in the <manifest> element.  

2. Building and signing a release version of your application.   
   - You can use the Gradle build files with the `release` build type to build and sign a release version of your application.  
   - See [Building and Running from Android Studio.](https://developer.android.com/studio/run).  

3. Testing the Release version of you Application.  
   - Before you distribute your application, you should thoroughly test the release version on at lease on target handset device and one target tablet device.  

4. Updating Application Resources for Release.  
   - You need to be sure that all application resources such as multimedia files and graphics are updated and included with your application or staged on the proper production servers.  
5. Preparing Remote Servers and Services that your Application depends on.  
   - If your application depends on external servers or services, you need to be sure they are secure and production ready.   

-- -

Source: [Google's App Publishing Guide](https://developer.android.com/studio/publish)

