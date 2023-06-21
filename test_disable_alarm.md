Test Name: test_disable_alarm

Test Description:
This test verifies whether the alarm system disables the alarm successfully after it has been set by simulating an event that should activate the alarm and checking if it does not go off.

Prerequisites:
Have the clock app installed
Have an alarm set

Test Steps:

Open the clock app
Go to “Alarm” by tapping the Alarm icon at the bottom of the screen.
Press the green toggle button next to the alarm that was set during prerequisites 
Wait until the set time  
Verify alarm has not gone off

Expected Results:
- The alarm system should detect the disabled event and deactivate the alarm.
- The alarm should not go off.

Test Environment:
- Alarm system version: IOS Clock App
- Testing equipment: iPhone 7s
- Alert/notification mechanisms: speaker on the phone


