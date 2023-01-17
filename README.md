Deploy and test
This sample comes with a web-based UI for testing the function. To test it out:

Set up your Firebase project:
Create a Firebase project
Register your web app with Firebase
Enable Google Provider in the Auth section
Clone or download this repo and open the fcm-notification directory.
You must have the Firebase CLI installed. If you don't have it install it with npm install -g firebase-tools and then configure it with firebase login.
Configure the CLI locally by using firebase use --add and select your project in the list.
Install dependencies locally by running: cd functions; npm install; cd -
Deploy your project using firebase deploy
Open the app using firebase open hosting:site, this will open a browser.
Start following a user, this will send a notification to them.
