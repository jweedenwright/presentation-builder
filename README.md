# Presentation Builder

## Overview
This project's purpose was to create a dynamic presentation out of HTML, CSS and JavaScript that would work in any browser size.

Obviously this is nearly impossible as you could put so much content into each slide that would make it impossible to view on a mobile device, but if you design your presentation mobile first, then you never have that issue!

## Development Notes
The code is all housed in the index.html file and contains a few example slides. The JavaScript included in the page handles all the logic to auto scroll slides as well as generate and insert the 'Next' and 'Prev' slides. All you have to do is download the project and add a new 'section' each time you need a new slide. For example:
```html	
	...
	<section class="page orange">
		<div class="nav"></div>
		<h2>Slide Title Goes Here</h2>
		<p>Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.</p>
		<ul class="super-list">
			<li><a href="https://google.com" target="_blank" rel="noopener noreferrer">Test Link 1</a></li>
			<li><a href="https://google.com" target="_blank" rel="noopener noreferrer">Test Link 2</a></li>
		</ul>
	</section>
	...
```
Would automatically add another slide wherever you inserted it inside the HTML body tag. **NOTE: You CANNOT add a 'section' into a 'section'.** Each section must be a child of the next to ensure that the slides all work as they would in a presentation.

## Future Work
Creating this project following AMP (Accerlated Mobile Page) standards was desired, but because of limitations in time and AMP functionality, it was not completed.