Test Name: test_reset_alarm

Test Description:
This test verifies whether the alarm system resets the alarm successfully after it has been set off by simulating an event that should activate the alarm and checking if it goes off again.

Prerequisites:
Have the clock app installed
Have an alarm that has previously gone off

Test Steps:

Open the clock app
Go to “Alarm” by tapping the Alarm icon at the bottom of the screen.
Press the alarm list item button that was previously set during prerequisites 
Choose your time by scrolling
Press Save
Wait for your set alarm time
Verify alarm has gone off


Expected Results:
- After step 5 the time should be updated visually and the toggle button is green
- The alarm system should detect the enabled event and activate the alarm.
- The alarm should not go off.

Test Environment:
- Alarm system version: IOS Clock App
- Testing equipment: iPhone 7s
- Alert/notification mechanisms:  speaker on the phone


