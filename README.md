![CI logo](https://codeinstitute.s3.amazonaws.com/fullstack/ci_logo_small.png)

#  Sligo
live demo is available here (https://madatoo.github.io/ms2-sligo/)

This site is a work in progress and will be updated with new content. In the future, I want to connect both my projects, MS1 and MS2, into one.
## Introduction
This is my second Mile Stone Project for Code Institute.

This time, I decided to create this webpage for my family and friends in Poland. This is an online travel journal from my trips around Ireland. For the purpose of this course, I will limit the website to only a few places in Ireland that I have been to.

Before I started creating this project, I thought about the aims and goals I want to achieve with this. Below, I list some of those answers:

My main goals:
1. Create a place, where I can improve my writing skills (writing posts on
   Facebook/Instagram doesn't give me as much satisfaction as I would like).
2.  Showcase my husband’s photos and/or films, from the trips we've been on together, on this website.
3.  Build a community of people with similar interests to me in one place.
4. In the future, I would like to offer the website’s visitors my own
    services such as short-term flat rentals etc.
5. And finnaly, the most important personal goal for me is to show my web
    developer skills.

##  User Experience
User experience is probably the most significant thing when building a webpage. From my own experience in sales and marketing, it is key to focus your attention in the right areas (like user experience, in this case). To do this properly, you need to spend a while to figure out who is your target audience. Then you need to get to know them and their needs, for instance what they would look for on your website and why. Once you have that information, you need to think about different ways you can deliver them the best solutions.

Fortunately for me, I know the first viewers of this page.

 1. They are middle aged or older.
 2. Usually, they have teenage or adult children.
 3. They mostly use smartphones and laptops.
 4. They like to watch photos (carousel gallery would probably work best for them).
 5. Majority of them also likes movies.

For school purposes this webpage is written in English, but my audience will be in Poland. I will have to add a second language (Polish) to the page, to make their experience on the website better.

### First time Visitor's needs:

Website's first time visitors could want:

1. To look for nice places to visit on their trip to Ireland.
2. To look for maps, instructions or tips on how to travel around.
3. To easily navigate throughout the website.
4. To find social media links and/or a way to contact me.
5. To look at some pictures and/or films.
6. To read about more recommended places.

### Returning visitors are very often interested in:

 1. Up to date information about travel.
 2. New articles on the website.
 3. Answers to their own questions, which can be available in FAQ (in future).
 4. Collaborating with me.
 5. Planning their own trips with me (available in the future).

## Design

### Features

#### Global

This website will be very simple and intuitive, to give my audience a great user experience.

That can be achieved by having:

 1. A home button (logo placed on the top left corner).
 2. Responsive menu on the left side below logo,
 3. Social media icons, on the top right-hand side, to follow me on Instagram, Facebook and You Toube. Those links will open in separate pages.
 4. A footer stuck at the bottom of each page with copyright information.

I will begin by creating the mobile first design. Currently, most people look at websites on their smartphones before they check them online on bigger devices, such as tablets or laptops.

Those features will apply to all of the pages on my website.

##### Home page

The home page is going to include all of the features listed above. It will also have a jumbotron which will hover, and move a little to the front, to give my audience a fun experience when they will visit this page.

##### Contact page

The contact form will be placed in a way that is demonstrated in the wireframes. I would like to add some funny effects (for example: changing colours when a button is touched or a form is sent to me). On the left-hand side I would like to add a video window, where a short film will be available, showcasing some of the places mentioned on the website. I would like to link this form with jsemail.com, to receive messages from visitors.

##### Trips page

This is the most important page on this project. It will contain the map with recommended places such us: beaches, parks, towns, restaurants, etc. The map will contain flag markers and pictures with descriptions taken from Google Maps API. I would also like to create a carousel gallery with those places. Upon clicking a photo on the carousel, it will open a new window that will have a miniature picture of the clicked place and some brief information about it.

## Technologies Used

- HTML
- CSS
- JS

### Frameworks, Libraries & Programs Used

- Balsamic was used to create wireframes for each site on this project.

- Github was used to store the project.

- Gitpod is an Integrated Development Enviroment (IDE) which was used to create project.

- Git was used to version control.

- Github Pages was used to present created page.

- Bootstap

- FontAwesome

## Testing

1. Functionality
    - eye-friendly - I wanted create website, which will be frendly for our eays ( light corors with good contrast can help reduce effort needet to follow by texts). In my poinion test is passed.
    - navigation on site is clearly and visible  - yes
    - content on the web is stricly connected to the main topic - yes
    - links to social media in footer provide to intended websites - yes
    - links in nav bar provides to intendent sections on the webpage - yes
    - buttons below paragraphs provides to additional sources (other websites about the main topic) - yes
    - map shows clicked markers and when one of them is clicked again should be dispayed info about that place and link to google map with this place. For now - it not working properly. The css code is ok, but map is not showing . Test failure.
    - 
2. Browser Compatibility
    Google Chrome - working 
    Firefox -working
    Edge - working
    Safari-working but small devices need to have media query with smaller heading.

    

3. Responsiveness

Yes there is.

4. User Stories

    User Stories

As a user I am dissapointed, that I can't watch the videos directly on the page.

To solve all of these issues I was looking for some solutions online - on Stack Overflow, Slack and Student Support. Due to limited time for this project, I am glad that i at least made what I have now. For my circumstances, I think I've done a good job. I had to share a laptop with my daughter, who is a university student, because the motherboard in mine was broken. I have a personal laptop only since Friday afternoon.

I had trouble with the display map, because I restricted an API. Only when it wasn't done - the map appered on the screen. I also had trouble to see how my work looks like during the weekend (it was visible for Student Support but not on my laptop) - on both browsers (Chrome, Firefox), as I could not see anything.

I needed to replace old links from Bootstap - but even that did not solve all of my problems.

In the future, I want to remove all of the errors and create a much more customised map, which I saw in Google Maps documentation.

Lighthouse report:

Performance 28 (because I have a lot unused JS script (arras),
Accessibility 90
Best Practices 80
SEO 92

file is available (here)[assets/jpg/jpg.Ligthouse.docx] 


Knows Bugs:
|
## Deployment

To deploy this page to GitHub Pages from its GitHub repository, the following steps were taken:

1. Log into GitHub.
2. From the list of repositories on the screen, select madatoo/ms2-sligo
3. From the menu items near the top of the page, select Settings.
4. Scroll down to the GitHub Pages section.
5. Under Source click the drop-down menu labelled None and select Master Branch
6. On selecting Master Branch the page is automatically refreshed, the website is now deployed.
7. Scroll back down to the GitHub Pages section to retrieve the link to the deployed website.

Run this project locally (clone this project into Gitpod) you will need:

- a Github account. Create a Github account here
- use the browser with extention for gitpod Then follow these steps:

1. Install the Gitpod Browser Extentions for your browser
2. After installation, restart the browser
3. Log into Gitpod with your gitpod account.
4. Navigate to the Project GitHub repository
5. Click the green "Gitpod" button in the top right corner of the respository
6. This will trigger a new gitpod workspace to be created from the code in github where you can work locally.

## Credits

To create this project I used Google Maps Platform, Bootstap and w3schools, Kevin Powell, Traversy Media If a source is not mentioned above, then additional information about an original code, which was changed according to my website's needs, is mentioned in other files.

### Code
Bryce St. Pierrewebsites, medium.com, Traversy Media, Florin Pop, Sam Codes and their tutorials. I also used Slack, Stack Overflow, Tutors CI.

### Content
This was written by me after researching information about the places mentioned on the website.

### Media
Photos are from my own stock, except for the photos of the Yeats Building and the Lissadell House and Gardens which are from Google Images.
##### Youtube films:

Jonathan Graham
Go Strandhill 
Lissadell House
Frank Adam 
Gerard Beirne 
Outside Magazine Media

### Acknowledgements
I want to thank my Mentor, who has helped me with this project, the Tutors Team,who have helped me with the technical issues and my family who have supported me throughout the course of this project :) And my family and friends
