# Testing

> [!NOTE]  
> Return back to the [README.md](README.md) file.

⚠️ INSTRUCTIONS ⚠️

In the following sections, you need to convince the assessors that you have conducted enough manual testing to legitimately believe that the site works well. Essentially, in this part, you should go over all of your project's features, and ensure that they all work as intended, with the project providing an easy and straightforward way for the users to achieve their goals.

⚠️ --- END --- ⚠️

## Code Validation

### HTML

I have used the recommended [HTML W3C Validator](https://validator.w3.org) to validate all of my HTML files.

| Directory | File | URL | Screenshot | Notes |
| --- | --- | --- | --- | --- |
|  | [anxiety.html](https://github.com/KC-85/KinderMinds-CI/blob/main/anxiety.html) | [HTML Validator](https://validator.w3.org/nu/?doc=https://kc-85.github.io/KinderMinds-CI/anxiety.html) | ![screenshot](documentation/validation/html--anxiety.png) | ⚠️ Notes (if applicable) |
|  | [depression.html](https://github.com/KC-85/KinderMinds-CI/blob/main/depression.html) | [HTML Validator](https://validator.w3.org/nu/?doc=https://kc-85.github.io/KinderMinds-CI/depression.html) | ![screenshot](documentation/validation/html--depression.png) | ⚠️ Notes (if applicable) |
|  | [dvmentalhealth.html](https://github.com/KC-85/KinderMinds-CI/blob/main/dvmentalhealth.html) | [HTML Validator](https://validator.w3.org/nu/?doc=https://kc-85.github.io/KinderMinds-CI/dvmentalhealth.html) | ![screenshot](documentation/validation/html--dvmentalhealth.png) | ⚠️ Notes (if applicable) |
|  | [index.html](https://github.com/KC-85/KinderMinds-CI/blob/main/index.html) | [HTML Validator](https://validator.w3.org/nu/?doc=https://kc-85.github.io/KinderMinds-CI/index.html) | ![screenshot](documentation/validation/html--index.png) | ⚠️ Notes (if applicable) |


### CSS

I have used the recommended [CSS Jigsaw Validator](https://jigsaw.w3.org/css-validator) to validate all of my CSS files.

| Directory | File | URL | Screenshot | Notes |
| --- | --- | --- | --- | --- |
| assets | [style.css](https://github.com/KC-85/KinderMinds-CI/blob/main/assets/css/style.css) | [CSS Validator](https://jigsaw.w3.org/css-validator/validator?uri=https://kc-85.github.io/KinderMinds-CI) | ![screenshot](documentation/validation/css-assets-style.png) | There are some errors and warnings, however, these are related to Bootstrap & not the plain CSS within style.css. |


## Responsiveness

⚠️ INSTRUCTIONS ⚠️

Use this space to discuss testing the live/deployed site on various device sizes.

The minimum requirement is to test the following 3 sizes:

- Mobile
- Tablet
- Desktop

**IMPORTANT**: You must provide screenshots of your results, to "prove" that you've actually tested them.

Using the [amiresponsive](http://ami.responsivedesign.is) mockup images (*or similar*) does not meet the requirements. Consider using some of the built-in device sizes from the Developer Tools.

If you have tested the project on your actual mobile phone or tablet, consider also including screenshots of these as well. It showcases a higher level of manual tests, and can be seen as a positive inclusion!

⚠️ --- END --- ⚠️

I've tested my deployed project to check for responsiveness issues.

| Page | Mobile | Tablet | Desktop | Notes |
| --- | --- | --- | --- | --- |
I have used the recommended [CSS Jigsaw Validator](https://jigsaw.w3.org/css-validator) to validate all of my CSS files.

| Directory | File | URL | Screenshot | Notes |
| --- | --- | --- | --- | --- |
| assets | [style.css](https://github.com/KC-85/KinderMinds-CI/blob/main/assets/css/style.css) | [CSS Validator](https://jigsaw.w3.org/css-validator/validator?uri=https://kc-85.github.io/KinderMinds-CI) | ![screenshot](documentation/validation/css-assets-style.png) | There are some errors and warnings, however, these are related to Bootstrap & not the plain CSS within style.css. |


## Responsiveness

⚠️ INSTRUCTIONS ⚠️

Use this space to discuss testing the live/deployed site on various device sizes.

The minimum requirement is to test the following 3 sizes:

| Page | Mobile | Tablet | Desktop | Notes |
| --- | --- | --- | --- | --- |
| Home | ![screenshot](documentation/responsiveness/mobile/mobile-home.png) | ![screenshot](documentation/responsiveness/tablet/tablet-home.png) | ![screenshot](documentation/responsiveness/desktop/desktop-home.png) | Works as expected |
| Anxiety | ![screenshot](documentation/responsiveness/mobile/mobile-anxiety.png) | ![screenshot](documentation/responsiveness/tablet/tablet-anxiety.png) | ![screenshot](documentation/responsiveness/desktop/desktop-anxiety.png) | Works as expected |
| Depression | ![screenshot](documentation/responsiveness/mobile/mobile-depression.png) | ![screenshot](documentation/responsiveness/tablet/tablet-depression.png) | ![screenshot](documentation/responsiveness/desktop/desktop-depression.png) | Works as expected |
| DV Mental Health | ![screenshot](documentation/responsiveness/mobile/mobile-dvmentalhealth.png) | ![screenshot](documentation/responsiveness/tablet/tablet-dvmentalhealth.png) | ![screenshot](documentation/responsiveness/desktop/desktop-dvmentalhealth.png) | Works as expected |
| 404 | ![screenshot](documentation/responsiveness/mobile/mobile-404.png) | ![screenshot](documentation/responsiveness/tablet/tablet-404.png) | ![screenshot](documentation/responsiveness/desktop/desktop-404.png-404.png) | Works as expected |

## Browser Compatibility

I've tested my deployed project on multiple browsers to check for compatibility issues.

| Page | Chrome | Firefox | Brave | Notes |
| --- | --- | --- | --- | --- |
| Home | ![screenshot](documentation/browsers/chrome/home.png) | ![screenshot](documentation/browsers/firefox/home.png) | ![screenshot](documentation/browsers/brave/home.png) | Works as expected |
| Anxiety | ![screenshot](documentation/browsers/chrome/anxiety.png) | ![screenshot](documentation/browsers/firefox/anxiety.png) | ![screenshot](documentation/browsers/brave/anxiety.png) | Works as expected |
| Depression | ![screenshot](documentation/browsers/chrome/depression.png) | ![screenshot](documentation/browsers/firefox/depression.png) | ![screenshot](documentation/browsers/brave/depression.png) | Works as expected |
| DV Mental Health | ![screenshot](documentation/browsers/chrome/dvmentalhealth.png) | ![screenshot](documentation/browsers/firefox/dvmentalhealth.png) | ![screenshot](documentation/browsers/brave/dvmentalhealth.png) | Works as expected |
| 404 | ![screenshot](documentation/browsers/chrome/404.png) | ![screenshot](documentation/browsers/firefox/404.png) | ![screenshot](documentation/browsers/brave/404.png) | Works as expected |

## Lighthouse Audit

I've tested my deployed project using the Lighthouse Audit tool to check for any major issues. Some warnings are outside of my control, and mobile results tend to be lower than desktop.

| Page | Mobile | Desktop |
| --- | --- | --- |
| Home | ![screenshot](documentation/lighthouse/mobile-home.png) | ![screenshot](documentation/lighthouse/desktop-home.png) |
| Anxiety | ![screenshot](documentation/lighthouse/mobile-anxiety.png) | ![screenshot](documentation/lighthouse/desktop-anxiety.png) |
| Depression | ![screenshot](documentation/lighthouse/mobile-depression.png) | ![screenshot](documentation/lighthouse/desktop-depression.png) |
| DV Mental Health | ![screenshot](documentation/lighthouse/mobile-dvmentalhealth.png) | ![screenshot](documentation/lighthouse/desktop-dvmentalhealth.png) |
| 404 | ![screenshot](documentation/lighthouse/mobile-404.png) | ![screenshot](documentation/lighthouse/desktop-404.png) |

## Defensive Programming

⚠️ INSTRUCTIONS ⚠️

Defensive programming (defensive design) is extremely important! When building projects that accept user inputs or forms, you should always test the level of security for each form field. Examples of this could include (but not limited to):

All Projects:

- Users cannot submit an empty form (add the `required` attribute)
- Users must enter valid field types (ensure the correct input `type=""` is used)
- Users cannot brute-force a URL to navigate to a restricted pages

Python Projects:

- Users cannot perform CRUD functionality if not authenticated (if login functionality exists)
- User-A should not be able to manipulate data belonging to User-B, or vice versa
- Non-Authenticated users should not be able to access pages that require authentication
- Standard users should not be able to access pages intended for superusers/admins

You'll want to test all functionality on your application, whether it's a standard form, or CRUD functionality, for data manipulation on a database. Try to access various pages on your site as different user types (User-A, User-B, guest user, admin, superuser). You should include any manual tests performed, and the expected results/outcome.

Testing should be replicable (can someone else replicate the same outcome?). Ideally, tests cases should focus on each individual section of every page on the website. Each test case should be specific, objective, and step-wise replicable.

Instead of adding a general overview saying that everything works fine, consider documenting tests on each element of the page (eg. button clicks, input box validation, navigation links, etc.) by testing them in their "happy flow", their "bad/exception flow", mentioning the expected and observed results, and drawing a parallel between them where applicable.

Consider using the following format for manual test cases:

- Expected Outcome / Test Performed / Result Received / Fixes Implemented

- **Expected**: "Feature is expected to do X when the user does Y."
- **Testing**: "Tested the feature by doing Y."
- (either) **Result**: "The feature behaved as expected, and it did Y."
- (or) **Result**: "The feature did not respond to A, B, or C."
- **Fix**: "I did Z to the code because something was missing."

Use the table below as a basic start, and expand on it using the logic above.

⚠️ --- END --- ⚠️

Defensive programming was manually tested with the below user acceptance testing:

| Page | Expectation | Test | Result | Screenshot |
| --- | --- |  --- |  --- |  --- |
| Home | Feature is expected to display examples of why users should join. | Verified that the page displays the club’s mission and purpose in a clear and concise manner. | The mission and purpose were displayed as expected. | ![screenshot](documentation/defensive/home.png) |
| | Feature is expected to have accessible navigation links. | Checked navigation links for correct functionality and accessibility. | Navigation links were functional and accessible. | ![screenshot](documentation/defensive/navigation.png) |
| | Feature is expected to be fully responsive. | Resized the browser window and tested on multiple devices (mobile, tablet, desktop). | The page was responsive across all tested screen sizes. | ![screenshot](documentation/defensive/responsive.png) |
| Schedule/Timetable | Feature is expected to show the running schedule/timetable for sessions. | Confirmed that the page contains a structured table or list with session timings. | Timetable was displayed as expected. | ![screenshot](documentation/defensive/schedule.png) |
| Events | Feature is expected to display details of different running events. | Verified that the page lists upcoming events with relevant details. | Event details were displayed as expected. | ![screenshot](documentation/defensive/events.png) |
| Gallery | Feature is expected to showcase a gallery of past events. | Verified that the gallery contains clear images that aren't stretched, pixelated, and fully responsive. | Images are properly sized, and respond well to different device sizes. | ![screenshot](documentation/defensive/gallery.png) |
| Sign-Up Form | Feature is expected to prevent submission of an empty form. | Attempted to submit the form without filling any fields. | Form submission was blocked, as expected. | ![screenshot](documentation/defensive/signup01.png) |
| | Feature is expected to enforce valid input types for each field. | Entered invalid data (e.g., random text in an email field, numbers in a name field, etc.). | Error messages were displayed appropriately, and submission was blocked. | ![screenshot](documentation/defensive/signup02.png) |
| Social Links | Feature is expected to include working links to the club’s social platforms (Instagram, Facebook, etc.). | Clicked each social link to verify redirection to the correct platform page. | All links redirected to the correct platform pages, opening in new browser tabs. | ![screenshot](documentation/defensive/socialmedia.png) |
| 404 Error Page | Feature is expected to display a 404 error page for non-existent pages. | Navigated to an invalid URL (e.g., `/test`) to test error handling. | A custom 404 error page was displayed as expected. | ![screenshot](documentation/defensive/404.png) |

## User Story Testing

⚠️ INSTRUCTIONS ⚠️

Testing User Stories is actually quite simple, once you've already got the stories defined on your README.

Most of your project's **Features** should already align with the **User Stories**, so this should be as simple as creating a table with the User Story, matching with the re-used screenshot from the respective Feature.

⚠️ --- END --- ⚠️

| Target | Expectation | Outcome | Screenshot | 
| --- | --- | --- | --- | 
| As a user | I want links to clear, simple explanations of mental health topics | so I can understand Anxiety, Depression, and DV-related issues without feeling overwhelmed. | ![screenshot](documentation/features/navbar.png) |
| As a user | I want the navigation to be intuitive and accessible | so I can easily move between topics on any device. | ![screenshot](documentation/features/depression.png) |
| As a user | I want the site to feel calm and visually gentle | so I can read sensitive content comfortably. | ![screenshot](documentation/features/hero.png) |
| As a user | I want practical, supportive self-care ideas | so I know what small steps I can take. | ![screenshot](documentation/features/self-care.png) |
| As a user | I would like the website to be fully responsive | so that I can easily navigate and access information from my phone, tablet, or desktop. | ![screenshot](documentation/features/navbar.png) |
| As a user | I would like to see a 404 error page if I get lost | so that it's obvious that I've stumbled upon a page that doesn't exist. | ![screenshot](documentation/features/404.png) |

## Bugs

### Known Issues

| Issue | Screenshot |
| --- | --- |
| The project is designed to be responsive from `375px` and upwards, in line with the material taught on the course LMS. Minor layout inconsistencies may occur on extra-wide (e.g. 4k/8k monitors), or smart-display devices (e.g. Nest Hub, Smart Watches, Gameboy Color, etc.), as these resolutions are outside the project’s scope, as taught by Code Institute. | ![screenshot](documentation/issues/poor-responsiveness.png) |
| When validating HTML with a semantic `<section>` element, the validator warns about lacking a header `h2-h6`. This is acceptable. | ![screenshot](documentation/issues/section-header.png) |

> [!IMPORTANT]  
> There are no remaining bugs that I am aware of, though, even after thorough testing, I cannot rule out the possibility.

