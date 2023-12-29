# Automation to `Toggle Work Alarms`

## Description:

This is a handy automation designed to assist users in Toggle Work Alarms based on their next days's schedule, for which the events are added to the Calendar.

Features:
1. Automatic Daily Trigger: The Shortcut is set to run at `22:00` (configurable for your needs).

2. Calendar Event Retrieval: It fetches upcoming Work calendar events for the next day, identifying if it's a Vacation Day or Work Holiday. This is acheived by `Holiday or Vacation Check` Shortcut. You need to download or create similar shortcut that checks if it is a work related Holiday or Vacation for a given day from here: https://github.com/hdonapati/missing-link/blob/main/Apple-Shortcuts/Automations/Work-Alarms/Setup.md

3. Toggling Alarms: The Automation retrives all the Alarms labelled `Office` and then turns them all off when it is a work related Holiday or Vacation also giving a notifcation, or else keep them on.

## Setting up Automation:

1. Open the Shortcuts app and navigate to the "Automation" tab, use the '+' button on top-right corner to create a new automation. Select Time of day, in which choose the time you want the automation to run. I have selected it as `22:00` so that the whole day is covered, and select a weekday before all of your Work Days. For last section, select the options as per your convenience.
   <br/> <img src="images/x0.PNG" alt="Time of Day" style="width:400px;"/> <img src="images/x1.PNG" alt="Time Selection" style="width:400px;"/>
   
2. Then choose `New Blank Automation`, which takes you to the screen where you can create the Automation routine.

   > You need to search for the Scripting blocks and have appropriate values/configurations as shown in the images.


3. Add a `Text` block, in which specify the value `Tomorrow` - because we need to fetch Schedule for next day. Then Add `Run Shortcut` block and select the `Holiday or Vacation Check` shortcut. Then add all the other blocks as shown in the images.
  <br/> <img src="images/0.PNG" alt="Script 0" style="width:400px;"/> <img src="images/1.PNG" alt="Script 1" style="width:400px;"/>
  <br/> <img src="images/2.PNG" alt="Script 0" style="width:400px;"/> <img src="images/3.PNG" alt="Script 1" style="width:400px;"/>

4. In the `Show Notification` block, add the Title `Turned off Office Alarm(s) for tomorrow.`

> [!TIP]
> Customize the Shortcut to your preferences, including notification settings and any additional features you may need. Alternatively you can create areminder instead of an alarm, or do both. Alarm better suited for my purpose.

---

**Contribution**:
This Shortcut is open to contributions and improvements. Feel free to suggest enhancements, or report issues. Together, we can make travel preparations even more convenient and stress-free.
