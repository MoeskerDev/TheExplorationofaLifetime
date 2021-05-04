# The exploration of a lifetime
---
## Purpose of the project
---
The users of the site are people who want to learn more about the experiences of other people regarding flying into space, they want to learn more about the Moon and/or Mars. Furthermore, site visitors are able to request more information or book a flight into space. 
The company wants to create more bookings by sharing the experiences of other people, providing more information about the two destinations and to make it easy to book a flight or request more information regarding a departure from several locations in the world.

---
## UX
---
### User stories

1.	As a visiting user I want to easily find and read the experiences of other people so that I get an idea of the quality of the service. 					
2.	As a visiting user to the website I want to quickly learn more about the Moon and Mars so that I can decide if and which one I want to visit.				
3.	As a visiting user to the website I want to be able to navigate directly to the book a flight area so that I don't waste time searching for it.

### Wireframes
*	there is a pdf version added in the project itself and can be found at the [wireframes](https://github.com/MoeskerDev/TheExplorationofaLifetime/tree/master/wireframes) folder.

---
## Features
---
### Header
*	each page will include the Space✈M logo which always links back to the homepage when clicked on and it is a representation of the company. Also, the navbar with three links for users to change pages by clicking on each specific link: Home - Background information - Book a flight.
*	both are responsive to the screensizes Ipad and Iphone5, the latter one will display a burger menu.

### Footer
*   each page will show the footer with the company address so users know where the company resides.
*	will include four social links which allows users to follow updates, come into contact with each other and share experiences.
*   they are responsive to smaller screensizes like Ipad and mobile Iphone5.

### Home
*	will have a header and footer.
*	additionally a body with three sections, each will have their own header.
*	in the first section there will be two quotes with a video link in the middle for users to think about space and earth in a funny and philosophical way.
*	in the second section there will be two reviews with a green round button to redirect directly to the green book a flight page.
*	in the third section we show the three departure locations on earth.
*   responsive to Ipad and Iphone5.

### Background information 
*	will have a header and footer.
*	the body has three sections with each their own header as well.
*	the first section includes two video links, one about the Moon and one about Mars, to inform the users about the two possible destinations with again in the middle the green round button to link directly to the book a flight page.
*	the second section is used to provide additional information about the flights in a structured way by using a table which shares dates, duration, departure location and destination. As well as a green round button to redirect directly to the green book a flight page.
*   in the third section we show the three departure locations on earth.
*   responsive to Ipad and Iphone5.

### Book a flight
*	will have a header and footer.
*	the body will have two sections.
*	the first section shows an image of the Moon and of Mars including the price for each flight. 
*	the second section includes a form with required information and submit button to either request more information or to book a flight.
*   responsive to Ipad and Iphone5.

### Screen readers
*	using ARIA attributes to create accessibility for screen readers.
---
## Color-scheme
---
1.		#021f4b blue
2.		#4c3b71 purple 
3.	    #115268 green
4.		#fafafa white
5.      #676767 grey
*   the color-scheme inspiration came from the following [image](https://www.pinterest.com/pin/727683252268415243).
---
## Technologies Used
---
*	HTML: was used to create the basic skeleton of the project
*	CSS: was used for styling the pages to make it more attractive for users to visit.

### Framework
*	[Bootstrap](https://getbootstrap.com/docs/4.0/getting-started/download/): the project uses Bootstrap 4.0 to be responsive to screen size and it provides a certain basic structure which saves time.

### Tools
*   [FontAwesome](https://fontawesome.com/icons?d=gallery): all the icons I used on my website are from here.
*   [GoogleFonts](https://fonts.google.com/specimen/Space+Mono?query=space+mono&preview.text_type=custom#standard-styles): by browsing Google fonts I chose the space mono 400 regular for content and the 700 bold for headers and the menu in general.
* [Favicon](https://favicon.io/) : I created a favicon to fix an error.
*   DevTools: was used for the positioning of features and content while also used during adaptations regarding responsiveness.

### Features for the future
*   Fixed header, that does not move for Ipad and mobile screen size.
*   Drop-down menu
*   Table
*   
---
## Testing
---
### Supported screens and browsers
*   Desktop: my own screen with size 1366x768.
*   Ipad: Ipad screen size, 768x1024.
*   Mobile: the mobile Iphone5 screen size, 320x568.
    * Screenshots are added in the project in a pdf file and can be found at the [docs](https://github.com/MoeskerDev/TheExplorationofaLifetime/tree/master/assets/docs) folder.

*   Chrome: this is the browser I normally use and have used during this project. For the most time I did not have access to the browser view, but via DevTools at the end I was able to see how to adjust for an Ipad screen and mobile (Iphone5) screen. All the links, buttons and videos work.
*   Firefox: for now I only pasted the link in the browser and it showed that the links, videos as well as the buttons were working in the same way.
*   Edge: I tested the links, videos and buttons and they were all working similarly when I pasted the url in this browser.

### Test cases

1.  As a visiting user I want to easily find and read the experiences of other people so that I get an idea of the quality of the service.
    *   Home: on this page we see a header with a logo that links to the homepage. Then a navbar that links to all three pages. The first section header with two quotes and a video. Then another section header with two reviews and a round button with a link to the booking page. Below that a section header with three departure locations. Finally, a footer with the address of the company and four social links. 
    *   As a visiting user, when I visit the [homepage](https://moeskerdev.github.io/TheExplorationofaLifetime/index.html), I can see the section header and read the reviews below from people who already experienced a flight in an instant on the homepage.

2.  As a visiting user to the website I want to quickly learn more about the Moon and Mars so that I can decide if and which one I want to visit.
    *   Background information: on this page we see the same header and footer. Besides that there is a section header with two informative videos and another round button with a link to the booking page. Below that section header with a table that contains more information regarding the dates, departures, travel time and destination. Below that a section header with three departure locations and at the bottom the footer again with the address of the company and four social links. 
    *   As a visiting user you can learn more about the Moon and Mars by clicking on background information in the navbar which leads to the [background information](https://moeskerdev.github.io/TheExplorationofaLifetime/info.html) page where you can watch both videos.

3.  As a visiting user to the website I want to be able to navigate directly to the book a flight area so that I don't waste time searching for it.
    *   Book a flight: on this page we have the same header and footer. At the top there is a section header with images of the Moon and Mars including the prices per destination. Below that a header as a question with a form where you can either request more information or leave your info if you want to book a flight. Name, email and the specific request are required. There is a submit button as well. 
    *   As a visiting user you are one click away from booking on each page via the green **_book now_** button or via the booking a flight link in the navbar, as you have seen on the [homepage](https://moeskerdev.github.io/TheExplorationofaLifetime/index.html) and [background information](https://moeskerdev.github.io/TheExplorationofaLifetime/info.html) page. When you click on the green button you are directed to the final book a flight page. The same result when you click on the book a flight link in the navbar on any page.
        Directed to the last page, [book a flight](https://moeskerdev.github.io/TheExplorationofaLifetime/book.html), you can fill out the form. 

*   The logo link should direct to the homepage when being clicked on which it does.
*   All the lines/boxes of the form should be filled out since they are required. If not a message should appear to fill out a certain line/box which it does. Once you fill out all the lines before you click on 'I want to fly into space' these warnings should not appear which indeed they do not, as expected.
*   The social links should open in another browser tab once you click on any of the four. All four social links open, as expected, in another browser tab.

### Code validation
*   HTML: was checked and passed the [W3C validator](https://validator.w3.org/) with no issues.
*   CSS: was checked and passed the [Jigsaw validator](https://jigsaw.w3.org/css-validator/) with no issues.
    *   Please note that I removed my alt text at the images and videos since they came up as errors in the above validators.

* An overview of the lighthouse results can be found in the project as a pdf file at the [docs](https://github.com/MoeskerDev/TheExplorationofaLifetime/tree/master/assets/docs) folder. 

### Fixed Bugs
*   The options of my burger menu did not show after clicking the button. It turned out that my fixed height for the header was in the way, which taught me another part of responsiveness design. This also helped me regarding the overlapping of the sections in different screen sizes.

* My video was not displaying completely in Ipad size. I fixed that my looking at my grid system and changing my code from col-md-4 to col-lg-4 col-md-6.

*   At some point I decided to check my social links and they did not work eventhough I followed a CI tutorial doing this. I did not understand why, looked online and then found a website where they mentioned that you should use the [absolute URL](https://pixelgrade.com/docs/lens/troubleshooting/arent-social-links-not-working/). I adapted the links and after that they worked!

*   Responsiveness; I am happy to say that I was able to fix my responsiveness issues for Ipad and mobile Iphone 5 size. I am happy with the way it looks now. I removed all previous code for media queries and started again. I learned from this what it is like to fix code, rather building it up from scratch. Although I did not have time to make it responsive to all screen sizes, I did use the grid system and with time and more creations I will learn more and more.

* I had a favicon error in the console and this was fixed by creating and adding a [favicon](https://favicon.io/) to my website.
---
## Deployment
---
### GitHub pages

This website was deployed to GitHub pages from the [GitHub repository](https://github.com/MoeskerDev/TheExplorationofaLifetime) by following these steps:

1.  Login into [GitHub](https://github.com/).
2.  From all the repositories on the screen, select **TheExplorationofaLifetime**.
3.  From the menu items click on **Settings**.
4.  Scroll down to the **GitHub Pages** part.
5.  Under **Source** click on the drop-down menu and select **Master Branch** instead of **None**.
6.  While selecting Master Branch, the page is automatically refreshed and is now deployed.
7.  Scroll back down to the **GitHub Pages** part and get the link to the deployed website.

At the moment of submitting this project the Development Branch and the Master Branch are identical.

### Gitpod

To clone this project in Gitpod you have to:

1.  Have a GitHub account. [Create one here](https://github.com/join).
2.  Use the Chrome Browser.

Then:

1.  Install the [Gitpod Browser Extension for Chrome](https://www.gitpod.io/docs/browser-extension/).
2.  Then, restart the browser.
3.  Log into [Gitpod](https://gitpod.io/login/) with your gitpod account.
4.  Go to the [Project GitHub repository](https://github.com/MoeskerDev/TheExplorationofaLifetime).
5.  Click on the green **Gitpod** button.
6.  A new gitpod workspace will be created from the code in GitHub where you can work locally.

If you want to work on the project code within a local IDE:

1.  Follow this link to the [Project GitHub repository](https://github.com/MoeskerDev/TheExplorationofaLifetime).
2.  Click on the **Code** button next to the green **Gitpod** button.
3.  Choose the **Clone** option with HTTPs.
4.  Copy the clone **URL** for the repository.
5.  Open the terminal in your local IDE.
6.  Change the current working directory to the location where you want the cloned directory to be made.
7.  Type 'git clone', then paste the URL copied at step 4.
---
## Credits
---
### Content
*   The quotes came from the following [site](https://www.keepinspiring.me/inspiring-space-quotes/).
*	The departure locations used in my website came from this [site](http://www.braeunig.us/space/center.htm).
*   In order to get the Youtube Video Thumbnail Image I used the following [site](http://www.get-youtube-thumbnail.com/).
* The text about the Moon and Mars were taken from the transcript of the videos.
*   The Moon and Mars images had to be converted from webp to jpg so I used this [site](https://ezgif.com/webp-to-jpg).
*   The reviews, company info, address, pricing and FAQ were written by me.

### Media
*	The images used in this site came from this [source](https://pixabay.com/).

    Image by <a href="https://pixabay.com/users/geralt-9301/?utm_source=link-attribution&amp;utm_medium=referral&amp;utm_campaign=image&amp;utm_content=1566159">Gerd Altmann</a> from <a href="https://pixabay.com/?utm_source=link-attribution&amp;utm_medium=referral&amp;utm_campaign=image&amp;utm_content=1566159">Pixabay</a>

    ![Jumbotron image](https://pixabay.com/get/ge28daf992e47d858224ecd5a03ecf6b2b62beb6020d45f71546cabd758e45507d82746fd5dcc62318990e768a06d9d27_1280.jpg "The universe")
    ![Moon image](https://cdn.pixabay.com/photo/2016/01/20/14/51/earth-1151659_960_720.jpg "The Moon")
    ![Mars image](https://cdn.pixabay.com/photo/2020/11/30/19/57/mars-5792147_960_720.jpg "Mars")	
	
*	The video's used in this site came from Youtube:

    [![Universe song](http://i3.ytimg.com/vi/vIy76M-4txo/hqdefault.jpg)](https://youtu.be/vIy76M-4txo)

    [![Moon video](http://i3.ytimg.com/vi/6AviDjR9mmo/hqdefault.jpg)](https://youtu.be/6AviDjR9mmo)

    [![Solar system video](http://i3.ytimg.com/vi/libKVRa01L8/hqdefault.jpg)](https://youtu.be/libKVRa01L8)

    [![Mars video](http://i3.ytimg.com/vi/D8pnmwOXhoY/hqdefault.jpg)](https://youtu.be/D8pnmwOXhoY)

### Code
* The jumbotron came from the CI tutorial, but I used [online](https://stackoverflow.com/questions/55038449/adding-background-image-to-jumbotron/55039070) code to add an image to it.
*   The mx-auto that I used came from this [site](https://stackoverflow.com/questions/39031224/how-to-center-cards-in-bootstrap-4).
*   The code for the [cards](https://getbootstrap.com/docs/4.0/components/card/) was taken from Bootstrap and the for the [borders](https://stackoverflow.com/questions/50743134/how-do-i-disable-the-border-on-bootstrap-4-cards/53397641) from stackoverflow.
*   The [resizing](https://stackoverflow.com/questions/15685666/changing-image-sizes-proportionally-using-css) of the images so that they are equal. 
*   The basic code for the form was taken from a CI tutorial, but the code for the radio buttons was taken from [here](https://www.w3schools.com/bootstrap4/bootstrap_forms_inputs.asp).
* The styling of the [hr](https://www.w3schools.com/howto/howto_css_style_hr.asp) element to make it more visible.
*   The (submit) [button](https://stackoverflow.com/questions/2238239/tooltips-for-button) code came from a CI tutorial and was adjusted. 
*   Regarding [responsiveness](https://www.w3schools.com/cssref/pr_dim_min-height.asp) and showing my menu options in mobile, the min-height helped me out a lot together with [media queries](https://stackoverflow.com/questions/6370690/media-queries-how-to-target-desktop-tablet-and-mobile).
* For the grid system, I have looked at CI tutorials and [online](https://getbootstrap.com/docs/4.0/layout/grid/).
*   In the end, most of the basic structures came from CI tutorials. I especially looked again at the miniprojects.

### Acknowledgements
*   I would like to thank my mentor for guiding me through the steps and staying optimistic about being able to finish before the deadline even though I am a complete beginner who was stressed with time.
*   Thanks to tutor support I was was able to view my project in my own browser at the end by fixing my open ports issue. This helped me to work a lot easier and gave me a much better overview.
*   Thanks to student support for having a look at my surgery at the end of last year and the possibility regarding an extra time request.
