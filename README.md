# Firebase_hosting_testing


Step 1 - Install Firebase Tools
We need to install firebase tools globally in command prompt window.

npm install -g firebase-tools

Step 2 - Initialize Firebase App
First we need to login to Firebase in command prompt.

firebase login

Open root folder of your app in command prompt and run the following −

firebase init

This command will initialize your app.

NOTE − If you used default configuration, public folder will be created and index.html inside this folder will be starting point of your app.

You can copy your app file inside public folder as a workaround.

Step 3 - Deploy Firebase App
This is the last step in this chapter. Run the following command from command prompt to deploy your app.

firebase deploy

After this step the console will log your apps Firebase URL. In our case it is called https://<databasename>.firebaseapp.com. We can run this link in browser to see our app.