# Talk to Me!

## Description of Lesson:
    - We're going to be making an app that talks!

## Getting Started:
- Go to the App Inventor Website at this URL:  www.appinventor.mit.edu
- Click on the orange button that says "Create Apps" to begin
- Login with your Gmail account and click "Continue" if some announcements are shown.
- In the top left click "Start a New Project" and name your project *TalkToMe*

### The Designer Window 
- When you first start a new project, you will see the Designer Window! This is where you create the Graphical User Interface (GUI) and can see what your app looks like as you add different parts to it! These parts are called components and can include anything from buttons, to pictures, to text boxes to include words, and even a GPS (like the one you use in your car to find new places!).
- Next, download the MIT AI2 Companion App from the Google Play Store or by scanning the QR code that you are given.
- Connect the MIT AI2 Companion app to your project by pressing the "Connect Tab" and choose AI Companion. You will need to type in a 6 letter code to finish connecting! Now you'll be able to see your app on the device that you downloaded the AI app on just like any other games on your phone!

### Building your app:
- It's time to make your app say something fun! Under the text properties tab, delete "Text for Button 1" and type "Talk to me" instead. This should change what your button says right away. 
- Now go to the Media drawer in the Palette and talk out the TextToSpeech component and put it onto the Viewer.
- It's time to tell your app what to do. In order to do this we need to change to the Blocks Editor from the Designer editor! Click the button "Blocks" to move to the Blocks Editor.  
### Buttons
- Step 1. Drag and drop the "when Button1.click do" event block to the Viewer panel section. This block works only when the button of your app is clicked, and that's why it's called an "Event Handler". It only works during certain events. Think of it like how you only celebrate your birthday on the day you were born and not everyday of the year :D
- Step 2. Click on the TextToSpeech drawer and click and drag the TextToSpeech1.Speak block into the viewer panel section. This is the block that will make your phone speak!
- Step 3. It's time to write out what you want your phone to say. You're going to need a speech block. Click on the text drawer and take ou a pink puzzle piece socket that is called message and write any message you want your phone to say! Finally link it to your TextToSpeech purple block. 
- Step 4. Test it out on your device with the volume up!!

#### Add Ons**
- While it's super cool that your app can say the text message phrase you gave it...let's make it even more fun!
- We're going to make your app respond to when you shake your phone. 
- Step 1. Drag out the Accelerometer Sensor and drop it onto the viewer. Click on the Accelerometer drawer to see its blocks and drag and drop AccelerometerSensor1.Shaking do block (yellow) onto your workspace. This block will do whatever action is inside of it ONLY when your device is shaking! It's called an event block. 
- Step 2. Remember when you created the when Button1.click do button earlier to make your app say your special message only when you click the button? It's your lucky day! You can just copy these blocks and snap them inside of your Accelerometer shaking block. You can change the text to something funny like "Hey! Stop Shaking me!"

**Test out your App now to make sure it works :)**

- Step 3. Lastly, let's make your app say whatever phrase you type in! From the User Interface drawer, and put it above the button that is already on the viewer screen. Select the green TextBox1.Text box. This block is called a "getter" and a "setter" which means it will GET the text the user types in and SET it as what the app needs to say to the screen! You can think of it like how on the first day of school you may go to the store and get a new shirt to wear then on the first day of school you set this shirt by wearing it!
- Step 4. The last step is to pull out the "Congratulations..." text box and plug in the new green text box you just got.

**WOO HOO! Your app should have 2 new features. When the button is clicked, it will speak out loud whatever the user types in. It will also say "Stop Shaking Me" if the user shakes their phone.**

-P.S If you finished early or want to try more...you can use what you learned to make a Magic 8 Ball App, a random word generator, or a Mad Libs Game!