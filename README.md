# Personal Portfolio

Link to Portfolio: https://rachelwong.github.io/portfolio/

Link to repository: https://github.com/rachelwong/portfolio

## Purpose

The primary purpose of this project to experiment with how I can best communicate my personality, current work and aspirations to be a fullstack web developer on the website platform. I want to attract work from SMEs in the front-end space. 

I am also using this portfolio assignment as a way to fully understand how CSS-grid works as a two-dimensional layout tool. I have found CSS Flexbox `display: flex;` to be a attractive concept for centering elements and general positioning along the one axis. Through this assignment, I have found `grid-template-rows` and `grid-template-areas` to be a hugely powerful tool that refactored alot of floating, positioning, and margin calculation. 

## Functionality / Features

First and foremost, due to time and resource constraints, this portfolio is designed to function as a single-page website. It exhibits the following attributes:
* Clicking on the project links on the page will trigger JQuery-enabled sliders to reveal more content
* CSS-Grid form the foundation of the layout, which responsively caters for three viewports (Desktop above 1024px, tablet above 400px, and mobile from 400px and below)
* Collapsed navigation menu when the screen size reduces to tablet sizes and returns to a normal horizontal text 
* CSS-Flexbox helped to position typography in grid cells
* Uses `@font-face` to enable a custom typeface [*CircularStd-Bold*](http://fontoteka.com/font/circular-std-bold) that is not available on Google Fonts

## Sitemap

## Screenshots

## Target Audience

I use this portfolio to reach out to fellow full-stack web developers, front-end engineers and project managers both in Australia and other English-speaking countries abroad. I want to showcase my projects - flaws and all - in order to exchange ideas and learn from the online community. 

Also, I would like to use a unique but accessible web page design layout as a calling-card to attract prospective employers in start-ups and SMEs by showcasing my ability to translate my interface aesthetics in a functional, tested product. I would like to demonstrate to recruiters and hiring managers that I am a visual thinker and I'm bringing aboard a mature and current visual aesthetic with the coding abilities to bring designs to life using current frameworks and coding practices. 

## Tech Stack
* [JQuery CDN](http://code.jquery.com/)
* [Normalize CSS](https://github.com/necolas/normalize.css/)
* [Google Fonts](https://fonts.google.com)
* Social Media Icons from [Font Awesome](https://fontawesome.com)
* Used [Giphy Capture](https://giphy.com/apps/giphycapture) for screencaptures of applications running 

## Design Process

My research took me to 
* [SiteInspire](https://www.siteinspire.com) - a gallery showcase of industry-leading website designs
* [Behance](https://www.behance.net/galleries/8/Interaction?tracking_source=title) - a curated listing of interaction design projects
* [Dark Code](https://www.youtube.com/channel/UCD3KVjbb7aq2OiOffuungzw) and [OT Online Tutorials](https://www.youtube.com/channel/UCbwXnUipZsLfUckBPsC7Jog)- YouTube channels of code-along HTML/CSS3/JQuery examples to see what is feasible to design and produce. 


## Wireframes

![alt_text](https://github.com/rachelwong/portfolio/blob/master/img/wireframe1.jpg)

* Tablet Wireframe
* Mobile Wireframe

## Usability considerations
![alt_text](https://github.com/rachelwong/portfolio/blob/master/img/Screen%20Shot%202019-03-24%20at%208.52.22%20am.png | width=300)

I have also reached out to [Ms Larene Le Gassick](https://twitter.com/larenelg), a Brisbane-based full-stack developer with background in  accessibility for her take on auditing and testing for web accessibility. Her advice reaffirmed that enabling website usability and accessibility does not end with a simple matter of checking off a proverbial list or running a website through an automated html auditing tool. Rather only real focus group testing can reveal any flaws and deficiencies in the user journey experience.  

## Extensible Features

As this portfolio website represents my first foray into consolidating and displaying my work for prospective work, the assignment process has revealed ample room for future improvement and refactoring. 

### Performance
It is clear that this is an image heavy website. 

As such, **responsive images** and **optimising image quality** (PNG, GIF, JPG) can go a long way to improve the website loading time. The best scenario would be to have an image server that can resize an image to any given dimension, in real-time, just by changing the image URL. That way, whenever the image dimension requirement changes, all that is required is to specify that dimension in the URL. 

### Mobile First
Instead of employing graceful degradation (desktop-first development) approach, the website could be built for mobile users first (progressive enhancement). 

In this context, some research could be made into [lazy loading](https://codeburst.io/5-steps-to-speed-up-your-image-heavy-website-65c874a86966) whereby image loading can be deferred until it is actually needed. 

### Nice to have features
The prototyping stage involved testing various features that unfortunately did not make it to deployment on time. If time permits, I would like to explore the following: 
* Optimise images further for faster mobile loading
* Add two Javascript image sliders, now replaced temporarily with static placeholder images from my illustration portfolio.
* CSS Animation of decorative images scrolling past 
* More accessibility features such as ARIA properties, roles can be used more effectively. 
* Some more finetuning of typeface positioning using `align-items` and `justify-content` properties will improve on consistency. I note that there is some text blow-out of grid cell when the screen size reduces.
* Add more (successful) programming projects so that it is clearer in my intent to be a software developer. 

## Project Plan & Timeline (with Trello)

### Early Planning (Day 1 - 2)
A [Trello board](https://trello.com/b/i99ZFPBV/portfolio) was set up to track my progress and ensuring that I meet all the design brief and assessment rubric criteria. 

A [Pinterest board](https://www.pinterest.com.au/rachwong/portfolio/) was also set up during the early research phase where I would collect wholesale any designs that caught my eye. 

From there, I built up a rudimentary [Moodzer moodboard](https://moodzer.com/boards/KyWzbYnD/) to orient my prototyping and began penciling through wireframes(## Wireframes). 

### Prototyping and troubleshooting (Day 3 - 4)

After two days of planning, I started to build a prototype to see how close I am able to build the website according to the initial wireframes. I also built separate pages testing out different javascript features such as multiple image sliders on the same page. 

Project documentation was written in parallel with the prototyping and final build process.  

### Final Build and testing (Day 5 - 6)

Since the testing prototype is quite close to the design brief, the final submitted product essentially follows the skeleton HTML5/CSS3 and populated with the real content, colour scheme, live links and portfolio images. 

___

# Q & A

> Describe key events in the development of the internet from the 1980s to today.

> Define and describes the relationship between fundamental aspects of the internet such as: domains, web servers, DNS, and web browsers

> Reflect on one aspect of the development of internet technologies and how it has contributed to the world today
