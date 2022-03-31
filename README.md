# capacity-counter
Capacity Counter (CS50 Final Project)
Video Demo: https://youtu.be/2VmucU5f_e0
Description:
Purpose: The intent of this project was to create a counter for small local businesses to keep track of how many people are in their store. This idea was inspired by the aftermath of COVID-19 and how it affected many local businesses as there were many capacity restrictions for small businesses. Thus, I created this app to help local business owners keep track of the number of people in their store to keep everybody safe while keeping their business afloat.

Note: This project was created using Android Studio.

MainActivity.java: This class is the main interface the user will be on when using the app. This page shows the number of people in the store, with the maximum capacity underneath this number, and the stage that the store is in. There are four stages the store can be in.

Stages: 

Stage 1: The number of people in the store is less than 75% of the maximum capacity. The message that is displayed will be "under capacity" and is green.

Stage 2: The number of people in the store is greater than 75% of the maximum capacity but is less than the max capacity. The message that is displayed will be "approaching capacity" and is magenta.

Stage 3: The number of people in the store is equal to the maximum capacity. The message that is displayed will be "at capacity" and is red.

Stage 4: The number of people in the store exceeds the maximum capacity. The message that is displayed will be "over capacity" and is red.

There are two pop up messages to warn the user about bad input. The first being that if the decrement button is pressed when the number of people in the store is 0, a floating message will appear indicating that the counter cannot be negative. The second is one notifying the user that the current capacity of the store is over the maximum capacity, letting the user know when to stop letting more customers into the store.

SettingsActivity.java: This capacity counter has a settings page that allows the user to update the maximum number of people in the store, reset to default settings, and reset the counter to 0. After the user clicks on one of these buttons and finishes inputting information, they are redirected to the MainActivity.java screen. There is also a back button on this screen if the user does not wish to input any new data.

AndroidSaveState.java: The AndroidSaveState class saves the user input of maximum capacity of the store, the number of people in the store, and the stage of the store. This is designed to ensure that the data in the main activity screen is saved when the user is tinkering with the settings page.

Additional Features that could be implemented if the project was done again: A feature that can be added onto this project is having multiple devices controlling one counter, as this app is ideally suited for businesses with one entrance and exit.

Overall, I had fun creating this application and grateful for the opportunity to pursue my passions in computer science by taking CS50.
