# Introduction to Amplify Storage

## Initialize Amplify Storage
To initialize the Amplify Auth and Storage categories you call `Amplify.addPligin()` method for each category.  
To complete initialization call `Amplify.configure()`.  

### Java Initialization 
Add the following code to your onCreate() method in your applicaiton class:

`Amplify.addPlugin(new AWSCognitoAuthPlugin());`  
`Amplify.addPlugin(new AWSS3StoragePlugin());`'


Your class should look like this:  

    public class MyAmplifyApp extends Application {
        @Override
        public void onCreate() {
            super.onCreate();

            try {
                // Add these lines to add the AWSCognitoAuthPlugin and AWSS3StoragePlugin plugins
                Amplify.addPlugin(new AWSCognitoAuthPlugin());
                Amplify.addPlugin(new AWSS3StoragePlugin());
                Amplify.configure(getApplicationContext());

                Log.i("MyAmplifyApp", "Initialized Amplify");
            } catch (AmplifyException error) {
                Log.e("MyAmplifyApp", "Could not initialize Amplify", error);
            }
        }
    }