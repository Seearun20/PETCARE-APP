# PETCARE-APP
It is KOTLIN firebase Android PET related Ecommerce APP where user can list and adopt pet as well as shop for pets and their accessories
Pet Adoption and Rescue Platform-README

Pre-requisites
Before executing this project, ensure the following software and dependencies are installed:
1.	Operating System:
o	Windows 10 or higher / macOS / Linux.
2.	Software Requirements:
o	Android Studio: Latest version with Kotlin support.
o	Firebase CLI: For setting up Firebase services.
3.	Firebase Configuration:
o	A Firebase project set up with Authentication and Firestore Database.
o	Download the google-services.json file for Android and place it in the app/ directory of your project.
4.	IDE Plugins:
o	Kotlin Plugin (if not already installed in Android Studio).
________________________________________
Admin Account Setup:
First signup as a normal account and after successfull signup go to your firebase console and in firestore database their will be a connection made as users and in that find your username and turn the IsAdmin field as true then this account will become admin.
________________________________________
Step-by-Step Instructions to Execute the Project
1.	Clone the Project Repository:
o	Download the project folder.

2.	Open in Android Studio:
o	Launch Android Studio and select "Open an Existing Project."
o	Navigate to the project directory and select it.

3.	Setup Firebase Configuration:
o	Place the downloaded google-services.json file in the app/ directory.
o	Ensure Firebase Authentication and Firestore Database are enabled in your Firebase Console.

4.	Sync and Build the Project:
o	Open the build.gradle file (Module: app) and ensure all dependencies are up to date.
o	Click on Sync Now to resolve dependencies.
o	Build the project by selecting Build > Make Project in the menu bar.

5.	Run the Application:
o	Connect an Android device or start an Android emulator.
o	Select Run > Run 'app' or press Shift + F10.

6.	Access the Platform:
o	Once the app is running, use the test adopter or admin credentials to log in and explore the features.

7.	Testing the Features:
o	Pet Listings: Listing stray and injured pets on the app.
o	Adoption Requests: Test adopting a pet.
o	Admin Management: Add or modify pet profiles (log in with admin credentials).
o	Giving Feedback and Ratings: Providing and sending feedbacks and suggestions and rating the platform.
o	Search and Filter: Browse available pets using search and filters.
o	Forgot Password: Change password using forgot password.
o	View orders: Check your list of placed orders.
________________________________________
Troubleshooting
•	Ensure you have a stable internet connection as the platform depends on Firebase.
•	Check the Android Studio logcat for any runtime errors.
•	Verify Firebase configurations if authentication or data operations fail.

