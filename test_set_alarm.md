Test Name: test_set _alarm

Test Description:
This test verifies whether the alarm system triggers the alarm successfully by simulating an event that should activate the alarm and checking if it goes off as expected.

Prerequisites:
Have the clock app installed
Assume user logging in for first time and does not have previous alarms set

Test Steps:

Open the clock app
Go to “Alarm” by tapping the Alarm icon at the bottom of the screen.
Press the “+” symbol at the top of the screen 
Scroll to set the time one minute past the current time
Press Save
Wait 1 minute 
Verify alarm has gone off

Expected Results:
- The alarm system should detect the triggered event and activate the alarm.
- The alarm should produce the expected sound or visual indicators to signify it is going off.
- If applicable, the alarm system should send the appropriate alerts or notifications.

Test Environment:
- Alarm system version: IOS Clock App
- Testing equipment: iPhone 7s
- Alert/notification mechanisms:  speaker on the phone


