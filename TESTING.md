# Testing

The following tests have been conducted by the developer. Each test described below was accompanied by the actions taken to ensure the test passed.

## Navigation

* Navigation Test 1:
    1. Visited website on multiple devices to ensure navigation bar is present.
    2. Used Responsive Device Mode to ensure navigation toggle icon works on tablet and mobile.
    3. Visited website on multiple devices and used Responsive Device Mode to ensure all links bring user to intended page section.
    4. Declared test, ‘passed’.

* Navigation Test 2:
    1. Asked friends to test website on mobile browsers.
    2. Received feedback regarding expanded navigation bar.
    3. Researched issue and found a JavaScript script to repair the issue.
    4. Added `Remove Active State Script` to `index.html`  (line 604).
    5. Asked the same people to retest website.
    6. Personally tested the navigation bar on mobile, tablet and desktop browsers.
    7. Marked issue as, ‘resolved’ and declared test, “passed”.

* Navigation Test 3:
    1. Visited navigation menu on 404 Error page.
    2. Clicked each link in the 404 Error Page to verify links work properly.
    3. Declared test, ‘passed’.

## Icons

* Icons Hover Test:
   1. Visited website on multiple devices to verify hover features are functional for all website icons.
   2. Hovered mouse over social media icons to ensure icons change color on hover.
   3. Declared test, ‘passed’.

* Social Media Links Test 1:
    1. Visited social media icons on website.
    2. Clicked each icon to verify links direct users to intended websites.
    3. Declared test, ‘passed’.

* Social Media Links Test 2:
    1. Clicked each icon to ensure links open in a new tab.
    2. Verified all social media links open in a new tab.
    3. Declared test, ‘passed’.

* Social Media Links Test 3:
    1. Visited social media icons on 404 Error page.
    2. Clicked each icon to ensure links direct users to intended websites.
    3. Declared test, ‘passed’.

* Back To Top Icon:
    1. Visited website on multiple devices and scrolled down to footer section.
    2. Clicked the arrow up icon (fas fa-chevron-up).
    3. Verified icon directs users to top of page when clicked.
    4. Declared test, ‘passed'

## Forms

* Contact Form:
    1. Visited contact section of website.
    2. Filled out contact form with text.
    3. Tried to fill out contact form while leaving a `required` field blank.
    4. Tried to submit "Email" row without a valid email address and was unsuccessful.
    5. Filled out text-area area to ensure comments section fits 3 rows of text.
    6. Repeated steps 1-4 on mobile and tablet.
    7. Declared test, ‘passed’

## Buttons

* Jumbotron Call To Action:
    1. Visited website on desktop, tablet and mobile.
    2. Visited Jumbotron section of website.
    3. Clicked, 'Schedule' button to verify button works.
    4. Repeated steps 1-2 in Chrome Dev Tools, Responsive Device Mode.

* Navigation Call To Action:
    1. Visited website header on desktop, tablet and mobile.
    2. Hovered mouse over, ‘Sign Up' button to verify hover feature is functional.
    3. Repeated steps 1-2 in Chrome Dev Tools Responsive Device Mode.
    4. Declared test, ‘passed’.

* Navigation Call To Action Test 2:
    1. Visited website header on desktop, tablet and mobile.
    2. Clicked circular, ‘Sign Up' button to verify button directs users to Contact form.
    3. Repeated steps 1-2 in Chrome Dev Tools Responsive Device Mode.
    4. Declared test, ‘passed’.

## Animations

* Sign Up Button Hover Test:
   1. Visited schedule section of website.
   2. Hovered mouse over, 'Sign Up' text in each schedule card.
   3. Verified hover animation worked for each ‘Sign Up Button’.
   4. Declared test, ‘passed’.

* Navigation Call To Action Animation Test:
    1. Visited website header on desktop, tablet and mobile.
    2. Hovered mouse over, ‘Sign Up' button to verify transform: rotate animation is functional.
    3. Repeated steps 1-2 in Chrome Dev Tools Responsive Device Mode.
    4. Declared test, ‘passed’.

* AOS Animations Test:
   1. Visited  and scrolled down through entire website.
   2. Analyzed animation speed, duration and effect.
   3. Sent website link to friends, family and Peer Review on Slack for feedback.
   4. Was notified by a Code Institute peer that one of the animations in the schedule section was broken.
   5. Inspected animation syntax.
   6. Repaired animation duration and delay speeds.
   7. Inspected all animations’ durations and delay times.
   8. Adjusted duration and delay speeds to make page more consistent.
   9. Committed and pushed all changes.
   10. Repeated steps 1-3 to verify animations were repaired.
   11. Declared test, ‘passed’

## UX

* Colors & typography:
    1. Visited website on multiple devices and browsers.
    2. Tested color palette with eye-dropper tool in Chrome Dev Tools.
    3. Asked friends and family to open website on respective browsers to ensure colors and font load properly.
    4. Declared test, ‘passed’

* Navigation Call To Action:
    1. Opened website in Dev Tools and inspected  ‘Sign Up' button.
    2. Utilized Responsive Device Mode to inspect button’s appearance on smaller devices.
    3. Noticed button appeared too large on smaller devices.
    4. Added media queries to stylesheet to make button smaller on smaller screens.
    5. Committed and pushed all changes.
    6. Repeated steps 1-5 in Responsive Device Mode to verify media queries resize button on smaller screens.
    7. Declared test, ‘passed’.

* Jumbotron Sizing Test:
  1. Opened website in Dev Tools and inspected Jumbotron.
  2. Utilized Responsive Device Mode to inspect text and background image sizes.
  3. Noticed Jumbotron content appeared too large on smaller devices.
  4. Added media queries to stylesheet.
  5. Committed and pushed all changes.
  6. Repeated steps 1-2 in Responsive Device Mode.
  7. Declared test, ‘passed’.

## W3C

* W3C Jigsaw CSS Test 1:
    1. Visited W3C HTML Validator.
    2. Uploaded entire stylesheet.
    3. Made all changes.
    4. Ran test again to verify all CSS passed.
    5. Repeated this step again after adding or updating anything in styleshee.

* W3C HTML Test 1:
    1. Visited W3C HTML Validator.
    2. Pasted all contents of index.html.
    3. Made all corrections to repair errors.
    4. Ran test again to verify all HTML passed tests.
    5. Repeated this step again after adding any new syntax and/or making changes.
