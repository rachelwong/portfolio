# Personal Portfolio

Link to Portfolio: https://rachelwong.github.io/portfolio/

Link to repository: https://github.com/rachelwong/portfolio

[Click for Google Presentation](https://docs.google.com/presentation/d/e/2PACX-1vQD8oQapz83rfKfwE_YR-hh1fQ_yfNU9QfvyP-5mBYggrdI2EdgpR8cmzjKoXKp9BPK_CPBgTv78UE7/pub?start=false&loop=false&delayms=5000)

## Purpose

The primary purpose of this project to experiment with how I can best communicate my personality, current work and aspirations to be a fullstack web developer on the website platform. I want to attract work from SMEs in the front-end space. 

I am also using this portfolio assignment as a way to fully understand how CSS-grid works as a two-dimensional layout tool. I have found CSS Flexbox `display: flex;` to be a attractive concept for centering elements and general positioning along the one axis. Through this assignment, I have found `grid-template-rows` and `grid-template-areas` to be a hugely powerful tool that refactored alot of floating, positioning, and margin calculation. 

## Functionality / Features

First and foremost, due to time and resource constraints, this portfolio is designed to function as a single-page website. It exhibits the following attributes:
* Clicking on the project links on the page will trigger JQuery-enabled sliders to reveal more content
* CSS-Grid form the foundation of the layout
* Media queries responsively caters for three viewports (Desktop above 961px, tablet above 400px, and mobile from 400px and below)
* Collapsed navigation menu when the screen size reduces to tablet sizes and returns to a normal horizontal text 
* CSS-Flexbox helped to position typography in grid cells
* Uses `@font-face` to enable a custom typeface [*CircularStd-Bold*](http://fontoteka.com/font/circular-std-bold) that is not available on Google Fonts

## Target Audience

I use this portfolio to reach out to fellow full-stack web developers, front-end engineers and project managers both in Australia and other English-speaking countries abroad. I want to showcase my projects - flaws and all - in order to exchange ideas and learn from the online community. 

Also, I would like to use a unique but accessible web page design layout as a calling-card to attract prospective employers in start-ups and SMEs by showcasing my ability to translate my interface aesthetics in a functional, tested product. I would like to demonstrate to recruiters and hiring managers that I am a visual thinker and I'm bringing aboard a mature and current visual aesthetic with the coding abilities to bring designs to life using current frameworks and coding practices. 

## Tech Stack

* [JQuery CDN](http://code.jquery.com/) to enable the slide out content
* [Normalize CSS](https://github.com/necolas/normalize.css/) as the industry standard for resetting browser default styles to create a clean slate to work with
* [Google Fonts](https://fonts.google.com) for main paragraph text 
* Social Media Icons from [Font Awesome](https://fontawesome.com)
* Used [Giphy Capture](https://giphy.com/apps/giphycapture) for screencaptures of applications running
* [Full Page Screen Capture Chrome browser extension](https://chrome.google.com/webstore/detail/full-page-screen-capture/fdpohaocaechififmbbbbbknoalclacl/related?hl=en) for capturing screenshots of the website at different screen resolutions. 

## Design Process

During the first two days of the project timeline, my research took me to 
* [SiteInspire](https://www.siteinspire.com) - a gallery showcase of industry-leading website designs
* [Behance](https://www.behance.net/galleries/8/Interaction?tracking_source=title) - a curated listing of interaction design projects
* [Dark Code](https://www.youtube.com/channel/UCD3KVjbb7aq2OiOffuungzw) and [OT Online Tutorials](https://www.youtube.com/channel/UCbwXnUipZsLfUckBPsC7Jog)- YouTube channels of code-along HTML/CSS3/JQuery examples to see what is feasible to design and produce. 

A number of websites had particularly inspired the design aesthetic
* [TQ South](https://tq.co/) - a website showcasing tech companies in Amsterdam South
* [https://s-i-l-o.fr/](https://s-i-l-o.fr/)
* [David McGillray art director portfolio](http://dmcg.co/)
* [A history of racial justice](https://calendar.eji.org/racial-injustice/mar/)
* [Design your life](http://designyourlife.com.au/)
* [Dropbox blog](https://blog.dropbox.com/)
* [Canal Street Market](https://canalstreet.market/community/)

<img src="http://theartboxacademy.com/wp-content/uploads/2016/03/bigstock-Seamless-abstract-mosaic-patte-125785532.jpg" alt="mondrian" width="500" />
*Image courtesy of http://theartboxacademy.com*

In the end of the first two days, I leaned for the [Mondrian](https://en.wikipedia.org/wiki/Piet_Mondrian), line-heavy graphic style for the website and using typeface as navigation. The lattice art style will allow me to experiment with CSS grid and challenge me in getting positioning correct for all three viewports. It is both an visually pleasing style and sufficiently exciting coding challenge to implement. 

## Usability considerations

To cater for a spectrum of users, I implemented the following

* Used semantic HTML `<nav>` `<section>`
* Used `ARIA-labeledby`, `ARIA-describedby` to label content
* used `role` for navigation, buttons
* used `alt` tag for images where needed
* used `title` tag for links where needed

I attempted to test my site using the [a11y Color Contrast Accessibility Validator](https://color.a11y.com/Contrast/). Unfortunately for some reason it failed to pick up on the black text and subsequently failed the test. 

<img src="https://github.com/rachelwong/portfolio/blob/master/img/a11y_colourContrast.png" width="800" alt="a117 testing">

The *Google Audit* also revealed that the site could use some improvement. Key opportunities for improvement include
* Avoid enormous network load (the whole page is 8mb)
* serve responsive images
* minify or refactor the javascript

<img src="https://github.com/rachelwong/portfolio/blob/master/img/Googel%20Audit.png" width="800" alt="Google Audit testing">

The site was also tested on Safari, Firefox, Edge and Chrome browsers. It was noted using the free browser compatibility tool [Browserling](https://www.browserling.com) that due to the javascript, some text blow-out occurred when viewed on Internet Explorer. 

#### Consulting the Accessiblity Expert

<img src="https://github.com/rachelwong/portfolio/blob/master/img/Screen%20Shot%202019-03-24%20at%208.52.22%20am.png" width="400" align="center" alt="larene twitter conversation" />

I have also reached out to [Ms Larene Le Gassick](https://twitter.com/larenelg), a Brisbane-based full-stack developer with background in  accessibility for her take on auditing and testing for web accessibility. Her advice reaffirmed that enabling website usability and accessibility does not end with a simple matter of checking off a proverbial list or running a website through an automated html auditing tool. Rather only real focus group testing can reveal any flaws and deficiencies in the user journey experience.  

## Extensible Features

As this portfolio website represents my first foray into consolidating and displaying my work for prospective work, the assignment process has revealed ample room for future improvement and refactoring. 

### Performance
It is clear that this is an image heavy website. 

Therefore, **responsive images** and **optimising image quality** (PNG, GIF, JPG) can go a long way to improve the website loading time. The best scenario would be to have an image server that can resize an image to any given dimension, in real-time, just by changing the image URL. That way, whenever the image dimension requirement changes, all that is required is to specify that dimension in the URL. 

<img src="https://github.com/rachelwong/portfolio/blob/master/img/code_img.png" height="200" alt="code sample" align="center">

### Mobile First
Instead of employing graceful degradation (desktop-first development) approach, the website could be built for mobile users first (progressive enhancement). 

In this context, some research could be made into [lazy loading](https://codeburst.io/5-steps-to-speed-up-your-image-heavy-website-65c874a86966) whereby image loading can be deferred until it is actually needed. 

### Nice to have features
The prototyping stage involved testing various features that unfortunately did not make it to deployment on time. If time permits, I would like to explore the following: 
* Optimise images further for faster mobile loading
* Add two Javascript image sliders, now replaced temporarily with static placeholder images from my illustration portfolio.
* Include an About Me page that introduces myself. 
* CSS Animation of decorative images scrolling past 
* More accessibility features such as ARIA properties, roles can be used more effectively. 
* Some more finetuning of typeface positioning using `align-items` and `justify-content` properties will improve on consistency. I note that there is some text blow-out of grid cell when the screen size reduces.
* Add more (successful) programming projects so that it is clearer in my intent to be a software developer. At the moment, the amount of illustrative work might confuses the message that I am sending to website visitors. 
* Add Copyright statement

## Project Plan & Timeline (with Trello)

<img src="https://github.com/rachelwong/portfolio/blob/master/img/timeline.jpg" width="1000" align="center" alt="Timeline for the project">

### Early Planning (Day 1 - 2)
A [Trello board](https://trello.com/b/i99ZFPBV/portfolio) was set up to track my progress and ensuring that I meet all the design brief and assessment rubric criteria. 

<img src="https://github.com/rachelwong/portfolio/blob/master/img/Screen%20Shot%202019-03-24%20at%2010.53.01%20am.png" width="800" alt="Trello board" >

A [Pinterest board](https://www.pinterest.com.au/rachwong/portfolio/) was also set up during the early research phase where I would collect wholesale any designs that caught my eye. 

<img src="https://github.com/rachelwong/portfolio/blob/master/img/pinterest.png" width="800" alt="Pinterest" />

From there, I built up a rudimentary [Moodzer moodboard](https://moodzer.com/boards/KyWzbYnD/) to orient my prototyping and began penciling through wireframes(## Wireframes). 

<img src="https://github.com/rachelwong/portfolio/blob/master/img/moodboard.jpg" width="800" alt="Moodzer">

### Prototyping and troubleshooting (Day 3 - 4)

#### Wireframes

![alt_text](https://github.com/rachelwong/portfolio/blob/master/img/wireframe1.jpg)

* [Desktop Wireframe](https://github.com/rachelwong/portfolio/blob/master/img/wireframe1.jpg)
* [Tablet Wireframe](https://github.com/rachelwong/portfolio/blob/master/img/wireframe_tablet.jpg)
* [Mobile Wireframe](https://github.com/rachelwong/portfolio/blob/master/img/wireframe_mobile.jpg)

After two days of planning, I started to build a prototype to see how close I am able to build the website according to the initial wireframes. I also built separate pages testing out different javascript features such as multiple image sliders on the same page. 

Project documentation was written in parallel with the prototyping and final build process.  

#### Prototyping in working HTML5 and CSS3

<img src="https://github.com/rachelwong/portfolio/blob/master/img/proto_screenshot_desktop.png" width="600" alt="Prototype desktop screenshot">

* [Desktop Prototype](https://github.com/rachelwong/portfolio/blob/master/img/proto_screenshot_desktop.png)
* [Tablet Prototype](https://github.com/rachelwong/portfolio/blob/master/img/proto_screenshot_tablet.png)
* [Mobile Prototype](https://github.com/rachelwong/portfolio/blob/master/img/proto_screenshot_mobile.png)


#### Final Build and testing (Day 5 - 6)

Since the testing prototype is quite close to the design brief, the final submitted product essentially follows the skeleton HTML5/CSS3 and populated with the real content, colour scheme, live links and portfolio images. 

#### Screenshots

<img src="https://github.com/rachelwong/portfolio/blob/master/img/screenshot_desktop.png" alt="screenshot" width="600" align="center">

* [Full screen](https://github.com/rachelwong/portfolio/blob/master/img/screenshot_desktop.png) from 961px width and upwards 
* [Tablet screen](https://github.com/rachelwong/portfolio/blob/master/img/screenshot_tablet.jpg) from 401px width to 960px width 
* [Mobile screen](https://github.com/rachelwong/portfolio/blob/master/img/screenshot_mobile.jpg) anything below 400px width 

#### Sitemap

Although the portfolio is essentially a single page site the content does align to a single-layer hierarchy. 

<img src="https://github.com/rachelwong/portfolio/blob/master/img/SiteMap.png" alt="Final sitemap" width="760">
___

# Q & A

> Describe key events in the development of the internet from the 1980s to today.

The internet descended from ARPAnet, a project funded by the U.S. Department of Defence. Technically, the internet was created when various networks in universities across the United States were themselves networked together. The internet was first used in the development of computer science, allowing more efficient sharing of knowledge and computing power between the computer science departments of the networked universities. The internet started to see wide adoption in industry when its first "killer app" was developed: email. Consumer use started to explode with the invention and deployment of the World Wide Web, a technology now so indentified with the internet that the two terms are often (incorrectly) used interchangably. In recent times, consumer use of the internet has been increasingly shaped by internet-enabled mobile devices such as smartphones and tablets. Today, more than half of the world's population has access to the internet.

> Define and describes the relationship between fundamental aspects of the internet such as: domains, web servers, DNS, and web browsers

Every device connected to the internet has an I.P. address, be it a smartphone used to access the internet or a server computer hosting a website. Because I.P. addresses are long strings of semi-random numbers, remembering lots of them would be prohibitive. Instead, domain names are used. When a user types "google.com" into their web browser, this query is sent to a domain name server (DNS), which looks up google.com and returns the associated I.P. address. The web browser then requests data (in this case, the homepage of google.com) from this I.P. address, and the server there will send the browser the requested data. Web servers and web browsers use publically available proctocols to transfer information. The most commonly used protocols are HTTP (HyperText Transfer Protocol) and HTTPS (the same, but communications are encrypted). These can be thought of as computer languages: if the computers involved (browser and server) did not speak the same language, communication could not occur. Once the information is recieved, it is displayed to the user, again in accordance with common, publically available standards.

> Reflect on one aspect of the development of internet technologies and how it has contributed to the world today

Because of the development and widespread deployment of cloud-based storage solutions, many kinds of work no longer necessarily need to be done at a traditional workplace. Instead of storing a spreadsheet locally on a work computer, it can be stored on an always-accessible internet-connected server. This means the spreadsheet can be edited live from any internet connected device at any time, be it the traditional work computer between the hours of 9am and 5pm, or from the worker's smartphone at 3am Sunday morning. This technology (as well as similar precedecessors) has enabled a wide range of social changes, including increased telecommuting, offshoring, and responsiveness of businesses outside of normal business hours. It has also increased the expectation for employees to be available to their employers at any time of the day and on any day of the week.

