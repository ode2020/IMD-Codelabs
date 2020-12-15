
## Intelligent Mobile Development course
### Part1. Description of the final project
### Part2. The 11 week codelab exercises
### Written by: Odette Muhayimana
### Student Number: 2120196018

----------------------------------------------------------------------------
-----------------------------------------------------------------------------
1. **Final Project: Visit Rwanda App**

Visit Rwanda App is developed for my country's tourism department owned by Rwanda Development Board (RDB).
The Visit Rwanda App will be very useful to both the country and tourists who day to day need access to all tourism related information in an easy way.<br>
Currently there is a website for tourism but there is no mobile app. <br> To develop this Application I will use Java on Android Studio IDE. <br>

1.1. **Features** <br>
The following are some of the features of the Visit Rwanda App: <br>
- Authenticate clients through Sin Up and Sign In
- View various touristic areas and urban areas 
- Select an arear and do the booking
- Insert clients information
- View the booking list
- Update the booking information
- Delete/cancel the booking
- Display the delete alert to the client before deleting/canceling his booking information
- Other many more....

----------------------------------------------------------
-----------------------------------------------------------



2. ## 11 weeks practical exercises
This file contains all practices we have done during all 11 weeks of our codelab.
### Week 2. Getting Started
. Codelab 1.1: Android and Hello World <br> 
>Comment: This first program has a purpose to show that the Android studio has been successfully installed for the developer to start developing android Apps.<br>
![](Week2.png)
-----------------------------------------------------------------------------------------------------------------------------------

### Week 3. Layouts and Resources for UI
. Codelab 1.2.PartA: My first interactive UI <br>
>This codelab aims to create a HelloToast App in a portrait setting. The app consists of two Buttons and one TextView, wherebyif the user taps the first button, it displays a short message (Toast) on the screen.<br>
>>- Tapping the secong Button increases the (click) counter displayed in the TextView starting from zero. <br>
>>- UI elements have been constrained in order to have a nice design as shown on the screenshot above.
![](Week3-Part1.jpg)
----------------------------------------------------------------------------------------------------------------------------------------------


.Codelab 1.2.PartB: The layout Editor <br>
> This pat B teaches us about creating the layout variant for horizontal (landscape) orientation and layout variant for tablets and larger displays.<br>
>Baseline constraints are used to align UI elements with text and pack and align button are used as well to align elements in the layout (Linear and Relative layout). <br>
![](Week3-Part2.jpg)
------------------------------------------------------------------------------------------------------------------------------------------------


### Week 4. Activity and Intents
. Codelab 2.1: Activity and Intents <br>
> The week 4 codelab taught us how to create a new activity other than MainActivity, to define parent and child activities for up navigation how both activities exchange messages using an explicit Intent:<br>
>> - Main activity is created with a Button SEND and the EditText is also added. When the Button is clicked, the main activity uses an intent to start the second activity which displays a message received from the Main Activity<br>
>> - Then EditText and Button Reply are added to the second activity. If the user types in a message and press Reply Button, the reply message is sent back to the Main Activity using an Intent. <br>
![Week4](week4.jpg)
----------------------------------------------------------------------------------------------------------------------------------------------------

### Week 5. Implicit Intents
. Codelab 2.3: Implicit Intents <br>
>- The week 5 codelab creates Implincit Intents App. The app contains 3 button options: Open Web, Open Location And Share this text. <br>
>- The application uses an implicit intent to perform each of the above three options. <br>
>- Then the intent receiver is created to accept an implicit intent then match the right URI protocol with the Host. <br>
![](week5.png)
-----------------------------------------------------------------------------------------------------------------------------------------------------------
### Week 6. User Interaction
. Codelab 4.1: Clickable images <br>
> The week 6 codelab builds a Droid Cafe App. 
>>- The app is built from the basic template activity. We created a clickable image with text decsribing what the image is about.<br>
>>- If the image is clicked, it displays a toast message telling the client the choice he made.<br>
>>- Then if the user wants to go to the new activity he taps the shopping cart icon.<br>
![](week6-Part1.jpg)
---------------------------------------------------------------------------------------------------------------------------------------------------------

. Codelab 4.2: Input Controls <br>
> This codelab teaches about controlling the keyboard by specifying the input type so that the user does not input whatever type of input.
>>- The Droid Cafe App continues by including a second activity called OrderActivity.<br>
>>- On the OrderActivity, we added EditText for a person name, EditText for Address, an EditText for Phone number which will only allow a numerical keyboard to display and a multiline Text to allow the user input more lines of text as needed then comes the Group Radio Button that allow the user to make only one choice from the delivery methods. <br>
![](Week6-Part2.jpg)
--------------------------------------------------------------------------------------------------------------------------------------------------------

### Week 7. User Interaction
. Codelab 4.4: User Navigation <br>
> This is the last part of Doid Cafe App.
>> - We added the back arrow clickable icon which allows the user to navigate from the child activity (OrderActivity) to the parent activity (MainActivity<br>
>> - I have also added a spinner drop-down list allowing the user to specify the type of the phone he has mentioned in the ordering information.<br>

![](Week7-Part1.jpg)
------------------------------------------------------------------------------------------------------------------------------------------------------

. Codelab 4.5: RecyclerView <br>
> The week 7 codelab is about creating a RecyclerView to display a long scrollable list of items(words in our example). RecyclerView is an important concept in nowadays because it does require to create a whole bunch of data set, it allows to initialize just a few items/words the recycle them. <br> 
>>- In our case, this  Recyclerview App allows to tap a word then see it marked as *clicked*. <br>
>>- Again, when we tap the Floating Action Button, a new word is added. <br>

![](Week7-Part2.png)
-------------------------------------------------------------------------------------------------------------------------------------------------------

### Week 8. Metrial Design
. Codelab 5.2: Cards and Colors <br>
> The MaterialMe app is developed<br>
> From the mock sports-news app with very poor design, we created a delightful user experience by using Material Design features among others being:<br>
>>- CardView which is a FrameLayout with some extra features (such as elevation and rounded corners) that gives a consistent look and nice design and amazing user experience. 
>>- The Glide Library have been added to allow use background processing and other complex processing as well, to reduce the memory requirements of loading images <br>
![](Week8.jpg)
----------------------------------------------------------------------------------------------------------------------------------------------------

### Week 9. Background Tasks
. Codelab 7.2: AsyncTask and AsyncTaskLoader <br>
> The WhoWroteIt App is created: <br>
>>- The user inputs the name or a part of the name of the book in the EditText, they hit *Search button* which executes an AsyncTask.<br>
>>- The AsyncTask queries the Google Books API to find the author and Title.<br>
>>- The author and title are displayed as results in the EditText Below <br>
>>- The AsyncTaskLoader is used to reimplement the same background task because it is the efficient way to update the UI and preserves data configuration <br>

![](Week9.jpg)
-------------------------------------------------------------------------------------------------------------------------------------------------------

### Week 10. Notifications
. Codelab 8.1: Notifications <br>
> Notify Me App is created.<br>
>> This App aims to let users trigger, update and cancel notification using the buttons showns in the screenshot<br>

![](Week10.jpg)
-------------------------------------------------------------------------------------------------------------------------------------------------------

### Week 11. Shared Preferences
. Codelab 9.1: Shared Preferences <br>
> HelloSharedPrefereces App is created.<br>
>HelloSharedPreferences App is another variation of HelloToast App that we have created in lesson 1.<br>
>>- The App inlucdes buttons to increment the number, to change the backgroud color and to reset both the number and color to their defaults. <br>
>>- Themes and styles are used to define the buttons <br>

![](Week11.jpg)

