## Frontend Developer Challenge

Thank you for applying to hear.com as a frontend developer. We would like to get a general idea of your expertise and give you the chance to show us that you are a battle proven developer.

This challenge will involve converting a visual design to HTML and CSS and then adding interactivity to that design using Javascript.

**The challenge**

 * Please create a [Figma](https://www.figma.com/) account and convert `hear-com-landing-page.fig` to HTML and CSS.
	- Please note that there are two versions of the page: 1) mobile and 2) desktop.
	- The end result should work well on mobile, tablet, and desktop devices.
 * Within the design you will find a questionnaire “carousel”.
	- The questionnaire will consist of 6 total slides.
	- The first 5 slides will contain questions which you can find in `questions.txt`.
		- Assume that in the future this number is subject to change and the code should be easily adaptable.
	- The last slide will contain a simple success message and should show all the answers the user selected in an easy to read format.
		- It is up to you on how to style this and make it look nice.
	- The answers to each question will act as radio buttons and you should only be able to select one answer per question.
	- Each question will have a submit button that will allow you to go to the next question.
	- Next and previous arrows will allow you to go back and forth between questions.
	- Each question is required and you should not be able to go to the next question without having answered the current question.
		- You might want to show the user some sort of message if this happens.
	- Bonus points
		- Add the ability to skip to certain questions via the use of URL params. For example: https://localhost:3000/?skip=2 would skip you to the second question.
		- Animate the transition between each step.

**Things to focus on**

 * Scalable and maintainable CSS and JS.
 * Accessibility.
 * Semantic HTML.
 * Speed optimization.

**Tech Requirements**

- Please use vanilla JavaScript only. No JQuery, React, or 3rd party libraries and frameworks.
- Please use vanilla CSS or SCSS. No Bootstrap or 3rd party CSS libraries and frameworks.
- The page should be responsive and should look well on all viewports and function correctly on all major browsers including Internet Explorer 11.
- Use a bundling tool like Webpack, Gulp, Parcel etc...
- An npm build command should build the entire page to a dist folder.

**Setting**

We expect you to ​invest about 4-8 hours f​or this task. We prefer quality over quantity.​ The level of feature completeness, documentation, tests is subject to your decision making. Feel free to make any trade-off and document your decisions. Think: product management is on vacation and not available.

**Deliverable**

Please provide us a link to a git repo with your source code and instructions on how to run the code. Make sure it works out of the box and Briefly describe your solution and explicitly mention any trade-offs and simplifications. Put instructions and solution description in a README file.