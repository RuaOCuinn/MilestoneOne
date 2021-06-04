<h1 align="center">Oscar Pearson - Author</h1>

## About

Project - User-Centric Frontend Development - Code Institute

The purpose of this project is to provide a website for the fans and readers of author Oscar Pearson.

It will serve as a focal point for all things relating to the author, allowing people interested in his works to discover more about the author and his published works.
The aim is to help the author to market his novels, guide his audience to his social media platforms and keep fans updated on newly published works, as well as works in progress.

## Deployment

A link to the website can be found [https://ruaocuinn.github.io/MilestoneOne/]

<img src="./assets/images/readme-images/landing-page.png" />

## Table of Contents

[User Experience (UX)](#UX)

[Features](#features)

[Technologies Used](#technologies)

[Testing](#testing)

[Deployment](#deployment)

[Known Bugs](#bugs)

[Credits](#credits)


<a name="UX"></a>
## User Experience (UX)

The end user of this project will be fans and prospective fans of author Oscar Pearson.

It is aimed at readers of fantasy novels, specifically readers of the sub-genre 'grimdark' fantasy as this is the type of fiction that Oscar Perason writes.

### User Stories

* As a user I want to be able to view and purchase Oscar Pearson's latest releases.
* As a user I want to be able to view and purchase Oscar Pearson's past published works.
* As a user I want to be shown how to easily follow the author on social media platforms.
* As a user I want to find out more about the author Oscar Pearson's life.
* As a user I want to be able to read a brief synopsis of each book to get a feel for their stories.
* As a user I want to be able to navigate the site easily whether accessing through my mobile or laptop.
* As a user I want to be able to view any events the author is attending eg. signing, interviews etc.
* As a user I want to be able to get in touch to ask questions about upcoming events.

### Design

- ####    Colour Scheme
    - The colours used for the website were chosen in an attempt to pull the user into the dark fantasy worlds created by the author; worlds where darkness is prevelant and the grey steel of swords and spears rules. 
    I have therefor chosen a base color of black with a secondary grey color (#85898c). It is my hope that these basic colours will also work well to not clash with the different colours of the author's book covers displayed on the website.
    Ruby Red (#a3001e) is adde throughout for that hint of blood and feeling of danger.

        <img src="./assets/images/readme-images/colour-palette.png" height="40px" />

- ####    Typography
    - The main font I have chosen is 'Roboto' It is easy to read, stands out and will hopefully remind users of an easy to read book. I will use sans-serif as a backup font.

    - The secondary font used is 'PT Serif' to help headings and titles to stand out from the rest of the text.

    - 'Crimson+Text' was added to the main text for the synopsis, quotes and bio sections to make the longer paragraphs more stylish and exciting to read.

- ####    Images
    - The main use of images for this website will be the ones used for book covers. As none of the books on the website are real I have taken some images from (https://www.pexels.com/) and added some text over them for the Author's name and Book Title.

    - An image of faded parchment - also from (https://www.pexels.com/) - such as might have been used for maps in ancient times, was used for the background of the pages sections. Again this is used to draw the user into the authors fantastical worlds.

    - Other images constist of small icon images taken from (https://fontawesome.com/v4.7/) to add imagery to help convey meaning to heading and make them more fun.

- #### Wireframes
    - All wireframes were made using Balsamiq. I have left up my original wireframes to show how the project changed shape as I worked through it.
    
    - Mobile Wireframe

        <img src="./assets/images/readme-images/mobile-wire.png" />

    - Home Page Wireframe

        <img src="./assets/images/readme-images/desktop-wire.png" />

<a name="features"></a>
## Features

### Common Features

* Header - provides users with easy navigation throughout the webpage.
    - The header is positioned using Bootsraps 'sticky-top' class. This keeps the navigation always within easy reach for the user.
    - The navigation menu is positioned in the header because this is the most common location for it meaning the user will know exactly where to find it.
    - Whichever page the user is currenlty on among the website will be underlined with a red line to show the user exactly where they are.
    - The header title is the Author's name, Oscar Pearson, this is here to instantly reasure fans of the author that they are on the right page for all of his content.
    - Colors were chosen to represent the fantasy author's dark world where powers lies with the strong. The black signifies the dark world and the colour grey of the writing is for the steel of swords and other weaponry.
* Links/Buttons - Any links hovered over will respond.
    - The page navigation links in the header will change colour to a paler version of themselves.
    - The social media images will also change to a plaer version to indicate they are links.
    - The background of the 'Buy Now' buttons will darken slightly when hovered over.
* Writing Progress
    - This feature is in place to provide the page user with up an update progress report for each of Oscar Pearson's upcoming projects. Thus keeping the user enticed and making it likely that they will return in the future to see how favoured book series are coming along.
    - This feature was made using Bootstrap's 'progress-bar', allowing me to change the colouring to suit the page.
* Accessibility
    - The hamburger menu initiated for smaller screens, has aria-label added to let users with screen readers know where the toggleable menu is.
    - Each progress-bar also has aria-label added so users with screen readers will be informed of the progress of selected upcoming projects.
* Hero-image
    - The background hero image is that of old, worn looking parchment meant to convey to the user the feeling that they are once again within Oscar Pearson's fantasy world.
* Footer
    - The footer has been designed to mirror the header by way of its colour scheme, though a dash of red has been thrown in for the Policy buttons.
    - The author's social media links take center stage of the footer to once again encourage the user to check out the author's social media content and stay within easy reach of all things Oscar Pearson.

### Specific Features

* Landing Page
    - The first thing the user is introduced to the Oscar Pearson's latest release, showing the book cover along side a synopsis of the story, quotes from fellow authors and a button link to allow them to purchase the novel.
* Books
    - Similiarly set up to the main Landing page, the Books page consists of previous titles published by the author, allowing users to peruse Oscar's past novels and purchase as they please.
* Events
    - The events page consists of Bootstrap's 'table' class to inform user's of public events Oscar Pearson will be speaking on or attending by laying out clear information as to where and when they will take place.
* Bio
    - The Bio page constists of two halves detailing his life from before he became an author to how he became one and thereafter.
* Contact
    - The contact page provides a simples to use and understand form requesting basic information from any users who wish to get into contact with the Author.

### Prospective Features
-   Creat a space for users to comment on books and engage in discussion on the site about the books and their fantasy worlds.

<a name="technologies"></a>
## Technologies Used

### Languages Used

    - HTML5
    - CSS3

### Frameworks, Libraries & Programs Used

* [Bootstrap v4.2.1 & v4.7.0](https://getbootstrap.com/)
* [Font Awesome](https://fontawesome.com/) - Font Awesome was used to add social icons and complement the design.
* [Google Fonts](https://fonts.google.com/) - Google Fonts was used to import 'Roboto' and 'PT Sarif' fonts in the main.css stylesheet.
* [Git](https://git-scm.com/) - Git was used for version control by utilizing the Gitpod terminal to commit to Git and Push to GitHub.
* [GitHub:](https://github.com/) - GitHub is used to store the projects code after being pushed from Git.
* [GitPod](https://www.gitpod.io/) - GitPod, connected to GitHub, hosted the coding space and allowed the projected to be committed to the Github repository.
* [Balsamiq](https://balsamiq.com/) - Balsamiq was used to create the [wireframes].
* [Paint 3D](https://balsamiq.com/) - Microsoft app Paint 3D was used to edit some of the images for the book covers.
* [jquery v3.5.1](https://getbootstrap.com/) - retrieved from a bootstrap example to assist with my navigation toggler.
* [popper.js/1.16.0] (https://getbootstrap.com/) - retrieved from a bootstrap example to assist with my navigation toggler.
* [Chrome DevTools](https://developer.chrome.com/docs/devtools/) for constant debugging and checking of features.

## Testing

### Google Chrome DevTools
-   Much of my testing was done with dev tools on google chrome throughout the coding process - and fault finding on each specific screen size starting from the smallest screen first and working my way up to my largest screen.
-   During testing and the making of the site I regularly used the element.style box to test out different styling ideas before implementing them into the permanent code.
-   I ran both mobile and desktop through DevTools Lighthouse project:
    - Mobile
    <img src="./assets/images/readme-images/lighthouse-mobile.png" />

    - Desktop
    <img src="./assets/images/readme-images/lighthouse-desktop.png" />

 ### Functionality Testing
- #### Internal & External links
    - All links are working and have been tested on several screen sizes.
    - The hamburger menu appears on screen sizes smaller than 768px. When clicked, it expands to reveal page links. These have been tested and are working as expected on several screen sizes.
    - The navigation bar stays at the top of the page on all screen sizes.
- #### Contact Form
    - The contact form has been tested on several screen sizes and is in working order.
    - Each input field makes use of the 'required' attribute and once each field is filled in the form successfully send. As this is a site made purely for the sake of this project the successfully submited form leads only a codeinstitute formdump taken from the course.

### CSS3 validator - Pass
- The test is showing some issues but they are with the bootsrtap link. 

<a href="https://jigsaw.w3.org/css-validator/validator?uri=https%3A%2F%2Fruaocuinn.github.io%2FMilestoneOne%2F&profile=css3svg&usermedium=all&warning=1&vextwarning=&lang=en">

### HTML5 validator - Pass
- After the below issues were fixed each page was teasted seperately and passed.

- On first testing it showed I was using the same ID for a background image twice. I went back into my code and moved the id from each section header on the individual pages to the <body> element to fix the issue.
- There were some erros with the buttons on the landing page and the books page but they were readily fixed.
- Their was an initial issue with the books page whereby an id for 'cover-image-outer' was used twice. this was fixed by changing it to a class.
- Another issue was highlighted for the contact page whereby the 'aria-describedby' was incorrect. This was quickly fixed.

<a href="https://validator.w3.org/nu/?doc=https%3A%2F%2Fruaocuinn.github.io%2FMilestoneOne%2F">

### Performance Testing
-   Overall WebPage Performance Test was done using WebPageTest with test location set to Ireland and test browser set to Chrome. Some areas of improvement according to this website are Security of the site and Cache Ststic Content which are out of the scope of this particular project, however, I will be looking to imporve these in the future.
    
<img src="./assets/images/readme-images/performance.png" />

### Testing User Stories
* As a user I want to be able to view and purchase Oscar Pearson's latest releases.
    - The sites landing page opens direclty to where the user can view and purchase the author's latest book release by clicking on the provided 'buy now' links to purchase a copy.
* As a user I want to be able to view and purchase Oscar Pearson's past published works.
    - The site is simply laid out with easy to use navigation at hand to guide the user to the author's books and click on the provided 'buy now' links to purchase a copy.
* As a user I want to be shown how to easily follow the author on social media platforms.
    - Social media links are positioned in the header and footer to encourage users to easily followe the author across other popular social networks.
* As a user I want to find out more about the author Oscar Pearson's life.
    - A 'Bio' page is situated within the simple navigation and therein the user will find a summary of the author's life from before and after he became published.
* As a user I want to be able to read a brief synopsis of each book to get a feel for their stories.
    - Each book cover promoting the author's works can be found along side a partnering synopsis to tantalize the reader into the story.
* As a user I want to be able to navigate the site easily whether accessing through my mobile or laptop.
    - The site is very plainly laid out and easily navigated on all devices.
* As a user I want to be able to view any events the author is attending eg. signing, interviews etc.
    - An events page is listed in an easy to follow tabled structure on the fittingly names 'event' page.
* As a user I want to be able to get in touch to ask questions about upcoming events.
    - The user can contact the author with a message through the simple form element on the 'contact' page.

<a name="bugs"></a>
## Known Bugs
* Throughout the making of this site I could not implement the header to look as I wanted with the navigation on laid out neatly on the right hand side and the Author's name on the opposite left. 
I found I had to move on to other things each time I tried to fix this as I was getting more and more lost as I tried to fix the issue. I am aware that this is likely a relatively simple thing to fix and perhaps once I have stepped away from the project I can return and fix the issue with fresh eyes.
* Another issue I feel I could fix in time is that if the screen is too big on some of the pages then there can be a white space left below the footer.

## Deployment

### Publishing
This website was published using [GitHub Pages](https://pages.github.com/). The procedure is outlined below.
1. Go to the GitHub website and log in.
2. On the left-hand side, you'll see all your repositories, select the appropriate one. ([Repository](https://github.com/RuaOCuinn/MilestoneOne) used for this project).
3. Under the name of your chosen Repository you will see a ribbon of selections, click on 'Settings' located on the right hand side.
4. Scroll down and click on the 'Pages' tab on the left-hand side.
Under the 'Source' click on the dropdown and select 'master branch' and click save.
5. A link to your published page then appears above the source option.

<a name="credits"></a>
## Credits

* [pexels](https://pexels.com/) - images for book covers taken from this site.
* [fontawesome](https://fontawesome.com/) - used for favicons throughout my page.
* [balsamiq](https://balsamiq.com/) - used to create wireframes at the beginning of the project.

### Content

*   All content was written by the developer.

### Media
* Animated mock profile image of Oscar Pearson provided by (https://dribbble.com/Setya182)
* Parchment hero-image and book cover for Bloodstone: Book Two on the 'Books' page provided by pixabay.com at (https://www.pexels.com/@pixabay)
* Book cover for Bloodstone: Book Three on the main landing page is by (https://www.pexels.com/@pedro-figueras-202443)
* Book cover for Confused Worship on the 'Books' page provided by (https://www.pexels.com/@monatrms)

### Acknowledgements
* I would like to Acknowledge Maranatha Ilesanmi for all his advice and support through our mentor meetings