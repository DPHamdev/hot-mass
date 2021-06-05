# Testing 

Testing this site to include user friendly experiences was demonstrated on various screen size viewports and external validating tools. 

—

## Validator testing

HTML
https://validator.w3.org/
—

CSS
https://jigsaw.w3.org/css-validator/
—-

These sites were used to test validity of the website code. 

CSS validation revealed issues with bootstrap (https://cdn.jsdelivr.net/npm/bootstrap@5.0.1/dist/css/bootstrap.min.css) not being included within w3 yet, which brings up the error of various css selectors incorporated within bootstraps CSS system. This however didn't affect the functionality of the website at all. 

## User story testing

1. **As a new visitor I want to be able to easily access any section of the page on any device.**

* Wherever the user is located within the website a responsive navbar with clear contrast between background and navigation is located at the top of the page permanately. 
* The link font size reduces as screen sizes decrease to ensure clear navigation is uninterrupted. 

2. **As a new visitor I want to see who I am interacting with.**

* When brought to the landing page the user is confronted a clear bold logo branding the bands image immediately. 
* A responsive javascript gallery is featured including thumbnails displayed at larger screen sizes in order for the user to interact and maintain good user interaction when switching between different devices. 

3. **As a new visitor I dont want to be bombarded with large amounts of text clogging up my device screen.**

* Text included on the site is all housed within individual sections with clearly defined borders, separate colour schemes to the background to ensure contrast. Each heading and text is clearly defined through size. All text is responsive within the elements they're housed to stack differently depending on the screen size they're using in order to ensure aestetically pleasing interaction. 

4. **I want to be able to see what the band has to offer in terms of music.**

* Embedded external media players are clearly displayed within the appropriate Media section with responsive design accounted for so that user is able to interact with appropriate media they wish to select. 

5. **What does the band have to offer me.**

* A merchandise section included displaying items on offer as well as a interactive link directing the user to an external website means the user is able to see what's on offer before ever clicking the link. Responsive design means this section is able to adjust accordingly to stack more appropriately depending on device screen size. 

6. **I want to contact the band.**

* Social media links are included within the footer at the bottom of the page which direct the user to which ever social media they wish to go to. 

* A contact form requiring small but essential information for the band to use allows the user to contact the band with any query without having to divulge massive amounts of time and effort in order to do so. 

## Lighthouse report

![Lighthouse](https://i.ibb.co/9tdPV2k/Screen-Shot-2021-06-05-at-11-18-18.png)

* Scoring highly on everything bar performance due to the background image being hosted externally rather than within gitpod means performance is lower than required. 

## Unfixed Bugs

* Background images wouldn't host correctly when used in CSS which meant to externally hosting and linking the landing page image resulted in a low scoring performance on lighthouse. 
Hosting this on gitpod correctly would rectify this. 

* Padding issues with responsive text means on some sections there is slightly too much space left. 

* Collapsing the navbar to a burger icon would've been ideal however javascript wouldn't work on desktop when trying to implement it which meant I decided to use responsive text sizing rather than a collapsable menu. 
