# Testing

The following tests have been conducted by the developer. Each test described below was accompanied by the actions taken to ensure the test passed.

## Navigation

* Navigation Test 1:
    1. Visited the website on multiple devices to ensure the navigation bar is present.
    2. Used Responsive Device Mode to ensure navigation toggle icon works on tablet and mobile.
    3. Visited the website on multiple devices and used Responsive Device Mode to ensure all links bring users to the intended page section.
    4. Declared test, ‘passed’.

* Navigation Test 2:
    1. Asked friends to test website on mobile browsers.
    2. Received feedback regarding the expanded navigation bar.
    3. Researched issue and found a JavaScript script to repair the issue.
    4. Added `Remove Active State Script` to `index.html`  (line 604).
    5. I asked friends to retest the website.
    6. Personally tested the navigation bar on mobile, tablet, and desktop browsers.
    7. Confirmed the navigation issue was, ‘resolved’.
    8. Declared test, “passed”.

* Navigation Test 3:
    1. Visited the navigation menu on the 404 Error page.
    2. Clicked each link in the 404 Error Page to verify links work properly.
    3. Declared test, ‘passed’.

## Icons

* Icons Hover Test:
   1. Visited the website on multiple devices to verify hover features are functional for all website icons.
   2. Hovered mouse over social media icons to ensure icons change color on hover.
   3. Declared test, ‘passed’.

* Social Media Links Test 1:
    1. Visited social media icons on the website.
    2. Clicked each icon to verify that links direct users to intended websites.
    3. Declared test, ‘passed’.

* Social Media Links Test 2:
    1. Clicked each icon to ensure links open in a new tab.
    2. Verified all social media links open in a new tab.
    3. Declared test, ‘passed’.

* Social Media Links Test 3:
    1. Visited social media icons on the 404 Error page.
    2. Clicked each icon.
    3. Verified links direct users to intended websites.
    4. Declared test, ‘passed’.

* Back To Top Icon:
    1. Visited the website on multiple devices and scrolled down to the footer section.
    2. Clicked the arrow up icon (fas fa-chevron-up).
    3. Verified icon directs users to the top of the page when clicked.
    4. Declared test, ‘passed'

## Forms

* Contact Form:
    1. Visited the contact section of the website.
    2. Filled out the contact form with text.
    3. Attempted to fill out contact form while leaving a `required` field blank.
    4. Attempted to submit the "Email" row without a valid email address and was unsuccessful.
    5. Filled out the text-area field to ensure the comments section fits 3 rows of text.
    6. Repeated steps 1-4 on mobile and tablet.
    7. Declared test, ‘passed’

## Buttons

* Jumbotron Call To Action:
    1. Visited the website on desktop, tablet, and mobile.
    2. Visited the Jumbotron section of the website.
    3. Clicked, 'Schedule' button to verify button works.
    4. Repeated steps 1-2 in Chrome Dev Tools, Responsive Device Mode.

* Navigation Call To Action:
    1. Visited website header on desktop, tablet, and mobile.
    2. Hovered mouse over, ‘Sign Up' button to verify the hover feature is functional.
    3. Repeated steps 1-2 in Chrome Dev Tools Responsive Device Mode.
    4. Declared test, ‘passed’.

* Navigation Call To Action Test 2:
    1. Visited website header on desktop, tablet, and mobile.
    2. Clicked circular, ‘Sign Up' button to verify button directs users to the Contact form.
    3. Repeated steps 1-2 in Chrome Dev Tools Responsive Device Mode.
    4. Declared test, ‘passed’.

## Animations

* Sign Up Button Hover Test:
   1. Visited the schedule section of the website.
   2. Hovered mouse over, 'Sign Up' text in each schedule card.
   3. Verified hover animation worked for each ‘Sign Up Button’.
   4. Declared test, ‘passed’.

* Navigation Call To Action Animation Test:
    1. Visited website header on desktop, tablet, and mobile.
    2. Hovered mouse over, ‘Sign Up' button to verify transform: rotate animation is functional.
    3. Repeated steps 1-2 in Chrome Dev Tools Responsive Device Mode.
    4. Declared test, ‘passed’.

* AOS Animations Test:
   1. Visited and scrolled through the website.
   2. Analyzed animation speed, duration, and effect.
   3. Sent website link to friends, family, and Peer Review on Slack for feedback.
   4. Was informed by CI peer that one of the animations in the schedule section was broken.
   5. Inspected animation syntax.
   6. Repaired animation duration and delay speeds.
   7. Inspected all animations’ durations and delay times.
   8. Adjusted duration and delay speeds to make the page more consistent.
   9. Committed and pushed all changes.
   10. Repeated steps 1-3 to verify animations were repaired.
   11. Declared test, ‘passed’

## UX

* Colors & typography:
    1. Visited the website on multiple devices and browsers.
    2. Tested color palette with the eye-dropper tool in Chrome Dev Tools.
    3. Asked friends and family to open the website on respective browsers to ensure colors and font load properly.
    4. Declared test, ‘passed’

* Navigation Call To Action:
    1. Opened the website in Dev Tools and inspected the ‘Sign Up' button.
    2. Utilized Responsive Device Mode to inspect the button’s appearance on smaller devices.
    3. Noticed button appeared too large on smaller devices.
    4. Added media queries to the stylesheet to make the button smaller on smaller screens.
    5. Committed and pushed all changes.
    6. Repeated steps 1-5 in Responsive Device Mode to verify media queries resize button on smaller screens.
    7. Declared test, ‘passed’.

* Jumbotron Sizing Test:
  1. Opened website in Dev Tools and inspected Jumbotron.
  2. Utilized Responsive Device Mode to inspect text and background image sizes.
  3. Noticed Jumbotron content appeared too large on smaller devices.
  4. Added media queries to the stylesheet.
  5. Committed and pushed all changes.
  6. Repeated steps 1-2 in Responsive Device Mode.
  7. Declared test, ‘passed’.

## W3C

* W3C Jigsaw CSS Test 1:
    1. Visited W3C HTML Validator.
    2. Uploaded the entire stylesheet.
    3. Made all changes.
    4. Ran test again to verify all CSS passed.
    5. Repeated this step after adding or updating anything in the stylesheet.

* W3C HTML Test 1:
    1. Visited W3C HTML Validator.
    2. Pasted all contents of index.html.
    3. Made all corrections to repair errors.
    4. Ran test again to verify all HTML passed tests.
    5. Repeated this step after adding any new syntax and/or making changes.

## Responsive Design

* Mobile-Friendly Test - Google Search Console
   1. Visited [Mobile Friendly Test by Google](https://search.google.com/test/mobile-friendly).
   2. Pasted project URL.
   3. Received these [test results](https://search.google.com/test/mobile-friendly?id=PGU_pMz-lTi471FCzSbJIQ).
   4. Verified 'Page is mobile-friendly' according to Google's Mobile-Friendly Test.
   5. Inspected [Page loading info](https://search.google.com/test/mobile-friendly?id=PGU_pMz-lTi471FCzSbJIQ).
   6. Verified that website has no loading issues according to Google's Mobile-Friendly Test.

* Am I Responsive Test
   1. Visited [Am I Responsive](http://ami.responsivedesign.is/).
   2. Pasted project URL.
   3. Examined website appearance across devices.
   4. Verified 'Page is Responsive'.
   5. Took screenshots of responsive emulator results.
   6. Embedded screen-captures specified above in README.md
