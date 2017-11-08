# upmunc-speaker-tracker

![UPMUNC Speaker Tracker UI Picture](https://github.com/loganmay/upmunc-speaker-tracker/blob/master/upmunc.PNG?raw=true)

### WARNING \#1: DON'T DELETE YOUR COOKIES

Just a heads up - while you're using the UPMUNC Speaker Tracker (UST), don't delete your cookies for the duration of the conference. If you do, you'll lose all the data the system has accumulated about delegates during the conference. So, if you really need to look up something sketchy, steal a computer from an unsuspecting staffer.

### WARNING \#2: IT ONLY WORKS ON FIREFOX AND CHROME (SORRY, NOT SORRY SAFARI)

![Google Chrome Logo](https://www.seeklogo.net/wp-content/uploads/2014/10/Google-Chrome-logo-vector-download.png)
![Mozilla Firefox Logo])(http://gruvix.com/wp-content/uploads/2011/11/firefox-logo.jpg)

## Using the UPMUNC Speaker Tracker

### Customizing Your Delegates List

The first thing you want to do when using the UPMUNC Speaker Tracker is customize your delegates list. The delegates list appears on the left hand side of the UI. By default, the list contains all of the countries in the UN. Customize the list by clicking the **Edit Delegates List** button, which opens up a small menu:

![UPMUNC Speaker Tracker: Edit Delegates Menu](https://github.com/loganmay/upmunc-speaker-tracker/blob/master/edit_delegates.PNG?raw=true)

* **Clear All Delegates** will do just that. This is helpful for small committees and crises committees to get rid of the mongo list.
* **Remove Delegates** will allow you to delete delegates one by one. This is better for big committees where much of the original list applies.
* Use the text input field and **Add Delegate** button to add new delegates to the list (Ctrl+Enter works, too). 

Once you're done, click the **Stop Editing Delegates** button to save your changes.

_Note: after you're done adding delegates, you can reload the page to resort them into alphabetical order._

### Taking Roll

Use the **Start Roll Call** button to begin taking roll.  You'll push this button every time you want to take roll again.  The system tracks who makes roll how many times, so be sure to use it to generate accurate data. You also need to take roll through the system in order to build a speakers list with it later on.

Once you start roll, everyone is marked as absent. You can then mark delegates as present by clicking the **Absent** button next to the name, which will then read **Present**.  When you've gone through every delegate, click the **Submit Roll Call** button to save the roll call.

![UPMUNC Speaker Tracker: Roll Call](https://github.com/loganmay/upmunc-speaker-tracker/blob/master/roll_call.PNG?raw=true)

_Note: you can use the **Hide Absent Delegates** button to hide absent delegates from the view_

### Using the Speakers List

Once you've created your delegates list and taken roll, you're ready to build a speakers list for the committee session. Get started by clicking the **View Speakers List** button to open up the Speakers List panel.

![UPMUNC Speaker Tracker: Edit Delegates Menu](https://github.com/loganmay/upmunc-speaker-tracker/blob/master/speakers_list.PNG?raw=true)

#### Add a Speaker to the list

Add a speaker by beginning to type the delegate's name into the _Add A Speaker_ text input field. A list of the names of present delegates that match what you've typed will appear below:

![UPMUNC Speaker Tracker: Adding a Speaker](https://github.com/loganmay/upmunc-speaker-tracker/blob/master/add_speaker.PNG?raw=true)

_Note: the small number next to the speakers name indicates how many times that delegate has already spoken. Use this to evenly distribute speaking time amongst delegates_

#### Remove a speaker

If a delegate wishes to be removed from the speakers list, use the **red x button** to begin deleting delegates.  Once you're done removing delegates, use the **red thumbs up button** to return to the normal view.

#### Give a speaker the floor

When the first delegate on the list is ready to speak, click the **Next Speaker** button. This will remove the delegate from the list, but put the delegate's name front and center underneath the timer.  That means the delegate has the floor and is ready to be timed (See using the timer below.)

### Using the Timer

#### Set the Speaking Time

Set the speaking time simply by typing the number of seconds into the _# of Seconds_ field.

#### Operating the Timer

Click the **Start Timer** button to begin timing.  If a delegate has the floor, and the name is in big letters underneath the timer, the system is tracking how many seconds the delegate spoke.

Once you start the time, a **Pause** button will appear you can use to pause the clock for whatever reason. If you pause it, the pause button becomes a **Play** button you can use to set the timer in motion again.

On the contrary, the **Restart Timer** button will set the timer back to the speaking time and start the clock immediately.

> Your ideal workflow: Click **Next Speaker**. When the delegate is about to speak, click **Start Timer**. When the timer goes off, repeat.

### Checking Quorum, etc.

At the bottom left hand corner of the screen is a small **'i' icon** which you can hover over to see useful committee info such as quorum, 2/3 majority, etc.

![UPMUNC Speaker Tracker: Adding a Speaker](https://github.com/loganmay/upmunc-speaker-tracker/blob/master/info.PNG?raw=true)
