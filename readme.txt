Programming Assignment 1
Partners: Sriram Rella and Andrew Chow

Our application is a react native mobile calendar app that pairs with your default calendar app. The primary functionality of the app is that it allows a user to create an event through the app-- with customizability including the name and date of the event. The app also requires a user to sign in, with authentication done through Google, specifically through Firebase Authentication. After the user provides their customized inputs, the app sends the data as an API that allows for the event to appear on their personal calendar app of one’s phone (for example it will appear in Apple Calendar on an iPhone). The app is compatible with Expo Go and was also tested with an iPhone emulator.

Instructions to run the code:
Clone or download the react-native-calendar repository from GitHub. Open the directory in the command window.

Run the application by running the command:

expo start

If expo is not already installed, set it up by running the command:

npm install -g expo-cli

Once the application has loaded and the command above is run, a QR code will appear in the terminal. Download the Expo Go app on a physical phone and scan the QR code to load the app on the phone. Alternatively, type ‘i’ for an iOS emulator (or ‘a’ for an android emulator-- not tested yet on android) in the terminal.

When the app has loaded, type in your Google credentials and click “Login.” Using the “Register” button as a user will allow for the bypassing of this authentication (the email and password fields still need to be filled out, albeit, with fake credentials).

Once logged in, the app will navigate to the home screen. Type in the event name and choose the event date and click “Create Event.” The Expo Go app will ask for access to the phone’s default calendar-- make sure to grant it permission. There is also the ability to sign out of the app using the “Sign Out” Button. Once an event has been created it will display on the phone’s default calendar.