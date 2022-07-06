# AWS Authentication

## Getting Started
Amplify Authentication provides an interface for authenticating a user.   

### Configuring Authentication Category
***Steps for configuring Auth Category:***  

***Run:***  
`amplify add auth`  

***Enter the following when prompted:***  

*? Do you want to use the default authentication and security configuration?*  

   `Default configuration`  


*? How do you want users to be able to sign in?*  

 `Username`  

*? Do you want to configure advanced settings?* 

  `No, I am done.`

***To push your changes to the cloud, execute the command:***  

***Run:***  
`amplify push`

Upon completion, `amplifyconfiguration.json` should be updated to reference provisioned backend auth resources. Note that these files should already be a part of your project if you followed the [Project setup walkthrough](https://docs.amplify.aws/lib/project-setup/create-application/q/platform/android/).  

-- - 

Source: [Amplify and Cognito](https://docs.amplify.aws/lib/auth/getting-started/q/platform/android/#configure-auth-category)