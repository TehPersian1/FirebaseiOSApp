Class: Fall 2021 CPSC 454-02
Title: Google Cloud Platform: a Multi-Factor Authentication Application
Authors: Shervin Afrasiabi, Vishva Patel, Gregory Miller, Shreeji Khalasi, John Tu

#Requirements:
A machine that can run Xcode. Either a Mac or a vitual machine with iOS version 14.5 compatible operating system or higher.

#How to run code:

1) Download Firebase_Frontend.zip and unzip folder
2) In the folder open Firebase_frontend.xcworkspace file in XCode
3) If needed at the top of Xcode change the scheme to the FireBase_Frontend and the device to iPhone 12 Pro Max
4) Lastly, click the 'start the active scheme' button at the top left 


#File Descriptions:

**View Controller:** Allows the users to login or sign up an account. Leads to either the login page or sign-up page depending on button pressed.

**Sign Up View Controller:** User can enter in first name, last name, email, and password manually and sign up or they can sign in with Google, which will enter that info in for them. If the password doesn't meet some requirements an error will appear.

**Login View Controller:** If the user has an existing account, they can enter they email and password and press login the get to the welcome page. They can also use mobile login method which will be described in the SMS View Controller Scene.

**SMS View Controller:** The user can enter a phone number which a one-time password will be sent which the user will enter and press verify. If the one-time code is incorrect an error will appear on screen.

**Captcha View Controller:** After a user logins or signs up they will have to enter a captcha which will be a unique 6 value code that will display on screen and the user will have to correctly enter in the code or it will not let them enter the welcome page. 

**Home View Controller:** Once the user has gone through all the view controllers above they will land on a page that says welcome