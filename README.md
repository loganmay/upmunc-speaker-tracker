# upmunc-speaker-tracker

![UPMUNC Speaker Tracker Main Gif](https://github.com/loganmay/upmunc-speaker-tracker/blob/master/speaker_tracker.gif?raw=true)

### HEADS UP \#1: DON'T DELETE YOUR COOKIES

Just a heads up - while you're using the UPMUNC Speaker Tracker (UST), don't delete your cookies for the duration of the conference. If you do, you'll lose all the data the system has accumulated about delegates during the conference. So, if you really need to look up something sketchy, steal a computer from an unsuspecting staffer.

### HEADS UP \#2: IT ONLY WORKS ON FIREFOX AND CHROME
![Google Chrome Logo](http://cloud.techylab.com/wp-content/uploads/2012/10/chrome-logo.jpg)
![Mozilla Firefox Logo](http://www.ladadadada.net/images/firefox_logo_transparent_thumb.png)
Sorry, not sorry, Safari. Wait, what's an internet explorer? Is that like a dude in a tin foil hat?

## Using the UPMUNC Speaker Tracker

### Customizing Your Delegates List

The first thing you want to do when using the UPMUNC Speaker Tracker is customize your delegates list. The delegates list appears on the left hand side of the UI. By default, the list contains all of the countries in the UN. Customize the list by clicking the **Edit Delegates List** button, which opens up a small menu:

![UPMUNC Speaker Tracker: Edit Delegates Menu](https://github.com/loganmay/upmunc-speaker-tracker/blob/master/edit_dels.gif?raw=true)

* **Clear All Delegates** will do just that. This is helpful for small committees and crises committees to get rid of the mongo list.
* **Remove Delegates** will allow you to delete delegates one by one. This is better for big committees where much of the original list applies.
* Use the text input field and **Add Delegate** button to add new delegates to the list (Ctrl+Enter works, too). 

Once you're done, click the **Stop Editing Delegates** button to save your changes.

_Note: after you're done adding delegates, you can reload the page to resort them into alphabetical order._

### Taking Roll

Use the **Start Roll Call** button to begin taking roll.  You'll push this button every time you want to take roll again.  The system tracks who makes roll how many times, so be sure to use it to generate accurate data. You also need to take roll through the system in order to build a speakers list with it later on.

Once you start roll, everyone is marked as present. You can then mark delegates as absent by unchecking the green check next to the name.  When you've gone through every delegate, click the **Submit Roll Call** button to save the roll call.

![UPMUNC Speaker Tracker: Roll Call](https://github.com/loganmay/upmunc-speaker-tracker/blob/master/roll_call.gif?raw=true)

_Note: you can use the **Hide Absent Delegates** button to hide absent delegates from the view_

### Setting Caucus Time
In the bottom right hand corner, there is a timer you can hover over to set the duration of the caucus.  It's pretty straightforward - just enter a time in the format of minutes:seconds and click **Set Time**. This is synced up with the individual timer, so keeping everything on time will be simple.

![UPMUNC Speaker Tracker: Caucus Timer](https://github.com/loganmay/upmunc-speaker-tracker/blob/master/caucus_time.gif?raw=true)

### Using the Speakers List

Once you've created your delegates list and taken roll, you're ready to build a speakers list for the committee session. Get started by clicking the **Speakers List** button to open up the Speakers List panel.

![UPMUNC Speaker Tracker: Edit Delegates Menu](https://github.com/loganmay/upmunc-speaker-tracker/blob/master/speakers_list.gif?raw=true)

#### Add a Speaker to the list

Add a speaker by beginning to type the delegate's name into the _Add A Speaker_ text input field. A list of the names of present delegates that match what you've typed will appear below:

_Note: the small number next to the speakers name indicates how many times that delegate has already spoken. Use this to evenly distribute speaking time amongst delegates_

#### Remove a speaker

If a delegate wishes to be removed from the speakers list, just hover over the speaker and click the **red x button** that appears.

#### Give a speaker the floor

When the first delegate on the list is ready to speak, click the **Next Speaker** button. This will remove the delegate from the list, but put the delegate's name front and center underneath the timer.  That means the delegate has the floor and is ready to be timed (See using the timer below.)

![UPMUNC Speaker Tracker Main Gif](https://github.com/loganmay/upmunc-speaker-tracker/blob/master/speaker_tracker.gif?raw=true)

### Using the Timer

#### Set the Speaking Time

Set the speaking time simply by typing the number of seconds into the _# of Seconds_ field.

#### Operating the Timer

Click the **Start Timer** button to begin timing.  If a delegate has the floor, and the name is in big letters underneath the timer, the system is tracking how many seconds the delegate spoke.

Once you start the time, a **Pause** button will appear you can use to pause the clock for whatever reason. If you pause it, the pause button becomes a **Play** button you can use to set the timer in motion again.

_Note: As long as you're not typing in a textbox, you can use the **Space Bar** to pause and play_

On the contrary, the **Restart Timer** button will set the timer back to the speaking time and start the clock immediately.

> Your ideal workflow: Click **Next Speaker**. When the delegate is about to speak, click **Start Timer**. When the timer goes off, repeat.

### Checking Quorum, etc.

At the bottom left hand corner of the screen is a small **'i' icon** which you can hover over to see useful committee info such as quorum, 2/3 majority, etc.

![UPMUNC Speaker Tracker: Checking Quorum](https://github.com/loganmay/upmunc-speaker-tracker/blob/master/info.PNG?raw=true)

## After The Conference

### Viewing Your Committee's Data

When you're all finished up with committee sessions, type **UPMUNC RULEZ** into the _# of Seconds_ field and click **Set Timer**. This will download a text file to your computer that contains all of the speaking data from your committee.  We will work to provide an interface where you can upload the text file and get a clear picture of the data.

### Ideas, Bugs, Suggestions?

We are all ears! Find the Ops Team at the conference or <a href="mailto:loma@sas.upenn.edu">email Logan</a>.
