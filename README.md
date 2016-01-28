# Townsville App Issues
The purpose of this repo is to track issues for the mobile companion app for Townsville AMSA National Convention 2016.

This readme is is designed to outline some of the basics of bug reporting to help best identify issues with the app.

#### [You can submit issues here](https://github.com/KrisnelC/townsville-app-issues/issues)

Lets start with the basics.

## Why send a bug report?
* To tell us about issues we are not aware of
* To help us identify new features we are not aware of
* To help us get a feel for how rangers will use the app, so we can improve the experience

## When to send a bug report
In short, as often as possible. However below are a non-comprehensive list to reasons
* You see an error message, send a bug report
* The screen is blank or data is missing, send a bug report
* When the app does not behave as expected, send a bug report
* When the app crashes, freezes, becomes non-responsive or is slow, send a bug report
* When you don’t get what you need from the app, send a bug report
* If you cannot figure out how to do something, send a bug report
* If you don’t like the way it does things, or the app annoys you, send a bug report

## What it should include

A bug report should contain a lot of information, the more you supply, the better. You can find a template for issues submission [here](). Here is what it should contain and how to write each section:

### Title
Create a short title for the report, and please be clear what the issue is. “Application crashed” is a horrible title as it gives no information on what is included in the report. Instead, title it with the error message and code, or the thing you were doing when it failed. For example: “Error 402: Access denied when clicking ‘Save’” or “App reports error when saving profile”. Both of these provide context for the bug report.

**Bad:** “It crashed”, “Saw an error”, “Bug”
**Good:** “Error 'Your session is invalid' when logging in”

### Classification
We need to know how serious it is, is this a feature request, minor annoyance or a full blown show-stopping nuclear-reactor-melting-down armageddon bug. Try naming your issue something like; “New feature”, “Minor Annoyance”, “Crashing Bug”, “Serious Bug” or “Minor Bug”.

**Bad:** Leave it blank
**Good:** “Serious Bug”, “Annoyance”, “Feature Request”

### Platform
Tell us what you are using to run the application, especially phone make and version, they are all different, and it’s important for us to know it.
How to find your phone version:  [Android](https://github.com/KrisnelC/townsville-app-issues#-how-do-i-know-which-version-of-android-i-have) / [iPhone](https://support.apple.com/en-au/HT201685)

**Bad:** “Android”
**Good:** " Phone: HTC M8, OS: 6.0 Marshmallow ”

###Can it be reproduced?
Some of the most annoying bugs are intermittent and cannot be reproduced. We’d like to know up-front if we are dealing with an oddity or an every-time bug.

**Bad:** Leave it blank
**Good:** “Every time”, “Occasionally”, “Unable to Reproduce”

### Description
Try to include all of the following in the description:

##### Summary
A quick natural language overview of what you were trying to do when the bug appeared. Start with context, where in the application you are, then focus on the “what” you did and “what” the app did. Try to describe it like an old school news reporter would call in a story from a phone booth, just the facts.

**Bad:** App does not work”
**Good:** “Clicked on 'Save' button on ‘Add Post’ screen, but nothing was posted”

##### What happened
Describe step-by-step what you were doing when the bug appeared, and why you think it’s wrong. Be specific, type out the menu names, screen titles and the full wording on buttons or links clicked. If you do the same steps, does the same error occur?

**Bad:** “Blank post”
**Good:** “I clicked on ‘Add’ from the 'Home' screen and entered 'this is my post' into the text field. 'Save' was then pressed and nothing occured”

##### What’s the error
 If an error message does come up, copy and paste the whole thing in. It makes it really easy for us to track these down.

**Bad:** “There was an error, but I clicked it away and did not read it”
**Good:** “Error 403: Access denied”

##### Supporting Information
If this issue happens on a specific login or on specific data or at a specific time, provide that too. Specify the record you were on if you can.

**Bad:** Leave it blank
**Good:** “This error happens whenever I try to post 'TIM IS THE SAFETY MAN'”.

### Steps to reproduce
If you can make this bug happen again, great. That’s a huge help. Describe step-by-step how to reproduce it, from as far back in the process as possible. And again, be specific. “I tapped on X” is different to “I double-tapped on X” is different to “I tabbed to X and pressed return”. All three trigger X, but what did you do?

**Bad:** “I tried to make a post, but it did not work”
**Good:** “From the ‘Add Post’ screen, click on the 'save' button”

### Expected results
Describe what you expected to happen when the bug occurred. This section is especially useful if the program does not behave as you expect it to, or if you would like to change the way the program works because it’s annoying.

**Bad:** “I expected it to work”
**Good:** “I expected my post to appear on the 'home' newsfeed.”

### Actual results
What did happen when the bug occurred. What was wrong, why is it wrong or if an error was thrown, what was the error.

**Bad:** “It did not work”
**Good:** “Error 403: Access denied” or "I expected to see a 'saving' message and be redirected to the Newsfeed"

### Workaround
If you have found a way to continue using the software by working around the bug, explain it. We may fix the bug, but the workaround could be causing other problems. Many people think this should be included in a bug report, I’m not sure as it does encourage workarounds instead of bug reporting.

**Bad:** “I have a workaround”
**Good:** “If you restart the application, and go straight to 'Add Post', it works the first time.”

### Attachments
If you know how to make screenshots, do it. Attach a shot of the error, and of the screen just before the error and the one before that. We developers can then see what happened and what you see. If the application issues a crash log (or has any kind of log), attach that too.

## Appendix
### <a name="android-v"></a> How do I know which version of Android I have?
1. Tap on the device's main Settings icon
2. Tap on "About device" (or tablet or phone)
3. Check the number under Android version
4. Your device will display the version:


* Android 3.1 and higher = Honeycomb
* Android 4.0 = Ice Cream Sandwich
* Android 4.1/4.2/4.3 = Jelly Bean
* Android 4.4 = Kitkat
* Android 5.0/5.1 = Lollipop

Townsville App requires Android version x.x or higer


## References
[How to Write a Good Bug Report](http://noverse.com/blog/2012/06/how-to-write-a-good-bug-report/)
