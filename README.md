# db_UdundiChallenge

## App purpose
Front end coding challenge as part of Udundi developer interview process.

## Tech Stack

Application uses a single HTML file linked to the bootstrap CDN and its own local css styleshit for additional styling changes.

## Process

### Landing page

#### Layout

HTML body is set with a red oxide background color as will as the provided background image offset to the right. Text and button are grouped into a div and the facebook and instagram icons are grouped into a footer element.

Text is positioned using flex display and a top margin adjustment. Additional horizontal adjustments are achieved through the bootstap offset class and button and text caption are positioned using bootstrap d-inline class. CSS properties were used to remove the default button appearance surrounding its embedded SVG icon. Footer is positioned using flex display.

#### Animation

Landing page text has a slightly staggered fade-in via the CSS animation property.

#### Mobile responsiveness

CSS file includes a media query with the following effects on displays smaller than 800px.

Background size changes from contain to cover to better suit verticaly oriented displays.

"Explore text" size is reduced by half to fit smaller displays.

Text changes from white to black for readability on displays that position it against the lighter part of the background image.


### Text box

Text box is created as a bootstrap modal. CSS animation property is used to have it slide onscreen from the left when plus button is clicked. CSS properties are added to elements within to more closely match mockup styling.

Standard button border is removed from close button in css to better match provided mockup. Read More button has had a color gradient added as a background.


## Demo

Submission is deployed via [GitHub](https://dboren.github.io/db_UdundiChallenge/) and its repository can be found on [GitHub](https://github.com/dboren/db_UdundiChallenge).