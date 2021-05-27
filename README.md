# Portfolio Project 1 - HTML/CSS Essentials
![Multiple Device Demo](./readme-content/images/multi-device.png)
## Live Site
[Katie Horrocks - Wildlife Photography](https://daveyjh.github.io/ci-portfolio-one-v4)
## Repository
[https://github.com/daveyjh/ci-portfolio-one-v4](https://github.com/daveyjh/ci-portfolio-one-v4)
***
## Table of Contents
- [Objective](#Objective)
- [Brief](#Brief)
- [UX &#8722; User Experience Design](#UX-&#8722;-User-Experience-Design)
- [Initial Concept](#Initial-Concept)
    - [Wireframes](#Wireframes)
        - [All Wireframes - Separate Document](./readme-content/wireframes.md)
    - [Colour Scheme](#Colour-Scheme)
    - [Typography](#Typography)
    - [Imagery](#Imagery)
- [Features](#Features)
    - [Existing Features](#Existing-Features)
    - [Features Left to Implement](#Features-Left-to-Implement)
- [Technologies Used](#Technologies-Used)
- [Testing](#Testing)
- [Bugs](#Bugs)
    - [Current](#Current)
    - [Resolved](#Resolved)
- [Deployment](#Deployment)
- [Credits](#Credits)
    - [Content](#Content)
    - [Media](#Media)
    - [Acknowledgements](#Acknowledgements)
- [Personal Development](#Personal-Development)
***
## Objective
In this project I intend to provide a portfolio style website for my sister's wildlife photography.  The main objective is to demonstrate competency in HTML and CSS.  I hope to provide an emotive, static front end application which is easy to navigate and has a clear purpose.

**The needs within this project are not genuine and are made purely for the purpose of completing my Code Institute project**
***
## Brief
### **Katie Horrocks - Wildlife Photography**
The goal of this website is to promote Katie Horrocks' photography.  The client would like to have:
- a brief introduction, who she is and what she does
- the client intends to display a few small galleries
- a contact form
- links to her social media sites

Katie does not work professionally as a photographer, the site is to serve as a platform for displaying her pictures and allowing interested parties to contact her for general purposes.

*She may, at a later date, add a blog to the site so that element should be considered during the design of the application*
***
## UX &#8722; User Experience Design
### User Requirements
Some example user stories which will affect the design
 
- *"As a first time visitor, I want to know what this site is about. I may use a number of different devices (mobile/tablet etc.) to view the site. I would like to be able to navigate easily"*
- *"As a returning visitor, I want to take a look at some different galleries and possibly some social media links. I am interested in learning a little more about Katie, but I really do like the photographs"*
- *"As an interested person, I would like to see some of Katie's work. I want to be able to contact Katie, perhaps connect with her via social media"*
***
### Initial Concept
With photographic images featuring as a really important aspect of the site, I  hope to keep the design fairly free from other distractions. I anticipate using a fairly neutral colour scheme as I feel this will allow the content images to stand out more from the design aspects. The application is to be designed with 'mobile first' in mind
#### Wireframes
<!-- wireframe images and link to more -->
Home
![Home Page Wireframe](./readme-content/images/mob-home.png)
Gallery Selection
![Gallery Selection Wireframe](./readme-content/images/mob-gallery-select.png)
Gallery Page
![Gallery Page Wireframe](./readme-content/images/mob-gallery.png)
About
![About Wireframe](./readme-content/images/mob-about.png)
Contact
![Contact Wireframe](./readme-content/images/mob-contact.png)
*See [here](./readme-content/wireframes.md#tablet) for other device types*
***
#### Colour Scheme
A neutral colour scheme created using *[coolors.co](https://coolors.co)*

![Colour Scheme](./readme-content/images/khp-color.png)

The scheme applied to the home page
![Colours Applied](./readme-content/images/mob-col-1.png)

*Some colours used in the final project may be shades of those listed, generated using [coolors.co](https://coolors.co)*

**I had not run the colour combinations through a contrast checker before commencing the project.** A revised colour scheme is shown below
![Revised Colour Scheme](./readme-content/images/khp-color-1.2.png)
Unfortunately the colours originally chosen gave a poor result unless taken to the extremes of light and dark. I have generated a new colour theme, again with some shades and tones to be used. The main changes are the lightening of the header and footer, and the font colour within those elements has been changed to purple
![Purple Font Change](./readme-content/images/header-purple-font.png)
***
#### Typography
The website will not feature a great deal of text. The fonts are imported into the CSS file from *[Google Fonts](https://fonts.google.com/)*
- **Caveat** has been chosen as the main font for the title text. It is a friendly font which gives a more personal appearance. The fallback family of **cursive** maintains the personal appearance
- **Dancing Script** has been chosen for the 'tag line' font. The font is more calligraphic and exudes a stylish tone, relatable to the photographic content of the website. The fallback family of **cursive** means the overall style will be maintained in the event some fonts fail to render
- **Indie Flower** has been chosen as the nav menu and secondary page's title font. It maintains the welcoming mood of the site, hoping to maintain positive user experiences. As with the other larger text elements, the fallback font remains as **cursive**
- **Raleway** has been chosen as the font for any areas featuring a higher volume of text. The font is more standard but maintains a sense of personal feel with its rounded styling and light weight.  A fallback font of **Trebuchet MS** is used as it maintains the light weight appearance. A fallback family of **sans-serif** is used to maintain a contrast to the fallback of the other text elements in the website
***
#### Imagery
As the main feature of the website, the imagery will be from Katie's personal collections.  Many of the images are large files, and so will be compressed for quicker load times. The image in the header should be friendly and not too complex. The content images will be arranged into categories to allow a number of galleries to be presented.

The images will be compressed using *[Compressor.io](https://compressor.io/)*
***
## Features
 
### Existing Features
<!-- - Feature 1 - allows users X to achieve Y, by having them fill out Z -->
1. The design is made with mobile first in mind
>*"As a visitor ... **I may use a number of different devices**"*
- *the media queries in the CSS file are done in a way to keep the aesthetics of the site looking OK across the majority of screen sizes*
***
2. The header will be visible on all pages and have a maintained style throughout
>*"As a visitor ... **I would like to be able to navigate easily**"*
- *the nav menu is accessible at the bottom of the header and sticks to the top of the page if scrolled*
***
3. The header content is brief and informative and contains a couple of images
>*"As a first time visitor ... **I want to know what this site is about**"*
- *the text content in the header indicates exactly what this site is about. The images are relevant and one intends to provide a positive emotive response*

    ![Header Snip](./readme-content/images/header-snip.png)
***
4. The home page has a large image showing animal photography
>*"As a first time visitor...**I want to know what this site is about**"*

>*"As a returning visitor...**I really do like the photographs**"*
- *the hero image shows off the type of photography included in the website, on certain devices, a few images are displayed for a little variety*

    ![Home Image Snip](./readme-content/images/home-img.png)![Desktop Images](./readme-content/images/desktop-imgs.png)
***
5. The footer element has accessible icons which link to social media platforms
>*"As a returning visitor...**some social media links**"*

>*"As an intersted person ... **connect with her via social media**"*
- *the social media links will be available on all pages. On all devices, the home page features a fixed footer, which is visible as soon as the page loads no matter the device type*

    ![Footer Snip](./readme-content/images/footer-snip.png)
***
6. The galleries are separated into different categories
>*"As a returning visitor...**look at some different galleries**...**I really do like the photographs**"*
- *the gallery images and styling allows clear identification of the various galleries*

    ![Galleries Snip](./readme-content/images/galleries.png)
***
7. The about page allows a little insight into the person behind the photographs
>*"As a returning visitor...**I am interested in learning a little more about Katie**"*
- *the about page gives some basic information about Katie's achievments and what she does. It also contains an image of her so people may recognise her*
    ![About Snip](./readme-content/images/about.png)

***
8. The contact page allows enquiries to be sent directly to Katie
>*"As an interested person...**I want to be able to contact Katie**"*
- *the contact form is **not currently active** as it requires languages I have yet to learn. The form is there to demonstrate the html structure and style*

    ![Contact Snip](./readme-content/images/contact.png)
***
The footer element contains a link to my GitHub and linked in profiles
>BONUS
- *the design of the footer allows for discrete links to me, should any visitors wish to know more about the site's creator (yellow border imposed on screenshot for demonstration purposes)*

    ![Footer Highlight](./readme-content/images/footer-highlight.png)
***
### Features Left to Implement
1. I would like to have the nav menu disappear when viewed via a landscape orientation on mobile devices
    - *The nav bar takes up valuable screen real estate on smaller devices. I would like to change the camera icon in the header to a menu icon on certain screens. This icon would act as a drop down activator for the nav menu, allowing more space for photographs*
    - The sticky position applied to the header is a workaround until I can research the drop down menu in greater depth. When the pages are scrolled, it allows the main header content to disappear, but keeps the nav menu visible. I have done some research into hidden menu's and am confident with the CSS methods to achieve this, however, there appears to be an issue with screen readers and assistive technologies. I do not wish to implement a feature which causes accessibility issues. With the research I have done, this feature would be too time consuming to implement at present for too little gain
2. The form on the contact page currently does not send information anywhere. 
    - The limitation of this project is to use CSS and HTML and so I have not yet learned about creating the necessary scripting behind the form. I have chosen to leave the form on the website to show comprehension of the form element, however **the 'action' and 'method' attributes have been removed** to prevent any issue with errors
3. If Katie decides to add a blog at a later date it will require a re-work of the navigation bar
    - As with note 1 above, I would look to implement a menu structure which allows the additional content to be revealed. I would use this method for the gallery selections, possibly removing the galleries.html page altogether, and would modify the structure of the navigation. The "about" page would sit within a sub menu with "blog" and would fall under a title along the lines of "other" to indicate it does not contain photographs
***
## Technologies Used

<!-- In this section, you should mention all of the languages, frameworks, libraries, and any other tools that you have used to construct this project. For each, provide its name, a link to its official site and a short sentence of why it was used. -->
- *[Balsamiq](https://balsamiq.com/)*
    - Balsamiq was used to create [wireframes](./readme-content/wireframes.md) for the project
- *[Compressor.io](https://compressor.io/)*
    - All images within the project have been processed through their free compression service
- *[Font Awesome](https://fontawesome.com/)*
    - The project uses icons from Font Awesome version 5
- *[Coolors.co](https://coolors.co)*
    - The colour scheme, and subsequent shades and tones, were generated via this application
- *[Visual Studio Code](https://code.visualstudio.com/)*
    - I have used this IDE as I had a very limited experience with an older version. The extensions available have allowed me to customize my workspace and become more efficient
        - Special mention to *[YuichiNukiyama](https://github.com/YuichiNukiyama)* for their *[Preview on Web Server](https://github.com/YuichiNukiyama/vscode-preview-server)* extension as this allowed a very quick visual representation of changes made
- *[Chrome DevTools](https://developer.chrome.com/docs/devtools/)*
    - Once the website was made to a basic deployment level, this extension featured heavily as I modified sizings and spacings
- *[Google Fonts](https://fonts.google.com/)*
    - The fonts used in the website are imported from Google Fonts
- *[Multi Device Mockup Generator](https://techsini.com/multi-mockup/index.php)*
    - The image at the top of this document was created using a free service provided by TechSini.com
- *[WebAIM Contrast Checker](https://webaim.org/resources/contrastchecker/)*
    - I put the relevant hex colour values in to the contrast checker to unsure good results, this is why a second colour scheme was generated
- *[a11y Contrast Accessibility Validator](color.a11y.com)*
    - I ran the finished website through this check service to double check contrasts on the final version
- *[W3C Markup Validation Service](validator.w3.org)*
    - I used this service to check the HTML and CSS files for errors. During development, I copied the entire text from the files and ran them through the direct input method
***
## Testing
As the website is written purely with HTML and CSS, the testing carried out will ensure the visual and functional aspects of the site work as intended. I will test on a number of browsers and screen sizes. I also intend to test the website for accessibility, validation and SEO
- *All anchor elements should work as intended and external links should open in new tabs*
- *All user requirements should be addressed and tested*
- *Contrast checks should report no errors (without explanation)*
- *Validation checks should report no errors*
- *Lighthouse testing scores should be high (ideally above 90)*

I have loaded the website in Chrome, Firefox and Edge. Each browser displayed as intended and the responsive design functioned as intended. Further to testing in the developer tools option of each browser, I have used a number of mobile devices to ensure the website functions and appears OK across all devices
- *Having used "vh" for some sizing means you need to scroll on certain devices to see the full page. This appears to be due to the address bar/status bar and is something I will research before my next project*

All anchor elements have been tested to ensure the correct href value has been used and external links open in new tabs 

All user requirements have been addressed and tested as shown in [Existing Features](#Existing-Features)

I have run the website through [a11y Contrast Accessibility Validator](color.a11y.com) and the result is shown below
![Contrast Check Results](./readme-content/images/testing/contrast-check.png)
*As shown in the image, there is one failure on this test. The failed element is the footer text, which links to me as an author of the website, and I am happy to leave this as it is. The element in question is intended to be subtle and is not relevant to the content of the site. I believe changing the style of this element to pass the contrast check could cause it to distract from the purpose of the main site*

Each page has been run through the W3C markup validation service, the index page and CSS reports are shown below
![index.html Validation](./readme-content/images/testing/index-validate.png)
![CSS Validation](./readme-content/images/testing/css-validate.png)
All page tests are shown [here](w3c.md) and I have included a brief explanation of the 3 warnings shown on the CSS validation

I have run the entire website through Chrome's lighthouse audit service and the results are shown below
- Mobile
![Mobile Lighthouse Results](./readme-content/images/testing/lighthouse-mob.png)
- Desktop
![Desktop Lighthouse Results](./readme-content/images/testing/lighthouse-desktop.png)
***
## Bugs
### Current
- Having tested the website via GitHub Pages and viewing on an iOS device (iPhone XR), some sizing is not correct and leads to a bad UX

*This appears to be due to the methods of spacing and sizing I have used. At this stage, I am not going to attempt to fix this as the UX is only slightly effected and more research leads me to believe the media queries I have used are not specific enough for iOS products*
***
### Resolved
1. The anchor elements in the nav section do not span the 'tab' which they sit in. More evident on wider screens, could lead to bad UX

***index.html** - lines - **31 - 33***
~~~
    <li class="active">
        <a href="./index.html">home</a>
    </li>
~~~
*Putting the text in a div as a child of the anchor has resolved the issue. The div is a  block element, and so, fills the width of the anchor. This reduces the chance of a bad UX from the tab not accepting user input even though it has changed colour*

***index.html** - lines - **31 - 37***
~~~
    <li class="active">
        <a href="./index.html">
            <div>
                home
            </div>
        </a>
    </li>
~~~
*Commit - **[9ed8b54](https://github.com/DaveyJH/ci-portfolio-one-v4/commit/9ed8b5488bbbd882e5775e213c983fddad779b27#diff-0eb547304658805aad788d320f10bf1f292797b5e6d745a3bf617584da017051R32-R57)***
***
2. The text in the overlay container overflows out the top on smalls screens
![Text Overflow](./readme-content/images/text-overflow.png)

*Issue dealt with during modifying media queries. Commits between 14:00 - 15:20 on 08/05/2021. Consisted of some font-size changes and alteration to the max-height of the containing div*
***
3. The footer encroaches far too much into the screen space on small landscape screens

*Commit - **[9831174](https://github.com/DaveyJH/ci-portfolio-one-v4/commit/98311749f1d119f4469e0e60d142e9734ed9b789#diff-a72d4ee198d130c997b203ecb2f5c54d84617b3cdf7bd9eaab804be78e2709aeL398)** - removed font-size change from **style.css** line **398***
***
4. Some screen sizes cause the lower section of overlay text to be obscured by the footer

*Commit - **[fb5cc65](https://github.com/DaveyJH/ci-portfolio-one-v4/commit/fb5cc65e3a87240f06642a4cad651c5f7c30349b)** - altered min-height value to be responsive up to 700px. From 700px, apply a minimum height value which allows the entire content to be viewed*

*Commit - **[6cfe816](https://github.com/DaveyJH/ci-portfolio-one-v4/commit/6cfe816bf42ac0e03b51c5331cc896e74dde2ac9#diff-a72d4ee198d130c997b203ecb2f5c54d84617b3cdf7bd9eaab804be78e2709aeR363)** - at screen min-width of 1200px, the min-height is removed to prevent obscure lower margins on the content*
***
5. The icons which link to my GitHub and LinkedIn only work at the very bottom of the rendered icon

***style.css** - lines - **183 - 185***
~~~
footer span a {
    position: relative;
}
~~~
*Setting the position to relative appears to have resolved the issue. I believe this causes the anchor element's z-index to be higher than the FontAwesome icon. When I have more time, I will try and research more about the class and styling applied by FontAwesome*

*Commit - **[5847e65](https://github.com/DaveyJH/ci-portfolio-one-v4/commit/5847e655d53517ef85bfbe9b267e1f437a5b6f4a#diff-a72d4ee198d130c997b203ecb2f5c54d84617b3cdf7bd9eaab804be78e2709aeR183-R185)***
## Deployment
Throughout the project, I have used VSCode with source control and a number of extensions. I have also used GitHubs desktop application. The two programs have allowed me to stage and commit files as and when necessary. Once committed, deploying the prject to a live site has been achieved via the following

**Github Pages**
- Navigate to the relevant GitHub Repository [here](https://github.com/DaveyJH/ci-portfolio-one-v4)
- Select "Settings" from the options below the name of the repository

![Settings Snip](./readme-content/images/github-settings.png)
- Select "Pages" from the left hand menu

![Pages Snip](./readme-content/images/pages-select.png)
- Select "Branch: main" as the source and leave the directory as "/(root)"

![Source Snip](./readme-content/images/pages-source.png)

- Click the Save button

- Take note of the URL provided

![URL Snip](./readme-content/images/pages-url.png)

- GitHub takes a short while to publish the page. The bar turns green if you refresh the pages tab and the page has been deployed

![Confirmed Deployment Snip](./readme-content/images/pages-deployed.png)
- Click the link or copy the URL to a browser to reach the deployed page
https://daveyjh.github.io/ci-portfolio-one-v4/

The site is now live and operational
***
## Credits

### Content
- The idea to link to lines of code within GitHub commits came from *[Chase Woodford](http://www.chasewoodford.com/blog/linking-highlighted-lines-code-github/)*
- I must pay thanks to my sister, Katie Horrocks. Her passion for photography has enabled me to design and produce a project which I have thouroughly enjoyed working on
### Media
- The photos are from Katie's personal albums and she has given permission for me to use them so as not to infringe her copyrights
    - The silhouette background image is from [Unsplash](https://unsplash.com)
### Acknowledgements
- I would like to thank my Code Institute mentor, [Spencer Barriball](https://github.com/5pence), for the guidance and encouragement given throughout the project. Following his advice, I have really refined the project and am very happy with the result
***
### Personal Development

Having had a session with my Code Institute mentor, I went about modifying the commit messages on most commits to include a reference to the document which had been worked on. I used the following method to modify the commit messages through git:

*In the powershell terminal within VSCode, with the repository as my current working directory, I entered the following:*

```
git rebase -i HEAD~95
```
*This generated a text document within my editor. I changed "pick" to "r" on all commits which needed document references adding*

*(snippet from document)*
```
pick 4696f63 DOC+ temporary gallery-select images
r 34b9b76 ADD images + basic styling to gallery-select
r 7e42d60 REM <a> from header. stop cursor change on text
r 6882570 ADD basic form structure
r 04e17e6 ADD placeholders + change "enquiry" to textarea
pick f45cb8e ADD styling to form [contact.html]
```
*This allowed me to edit the commit messages individually in my editor to include the document reference*
```
ADD placeholders + change "enquiry" to textarea [contact.html]
```
*Once the files were edited, saved and closed, I proceeded to force push the commits back into the GitHub repository*
```
git push --force
```
*This allowed the commit messages to be changed but changed the commit times of the messages to the time of the edit*

I thought this was a big problem and spent a while researching how to modify commit times. I tested the time change on one commit, did something wrong in the process and duplicated the entire commit history (bar the initial commit) with new SHAs, resulting in 191 commits. I believe I merged the modified commit (with original commit time) with the original branch, causing a new 'history' of commits which were duplicates of the existing ones. I then ran another rebase of the entire commit history and was able to identify the unwanted commit messages, delete the lines from the generated todo file and, once saved and forced back to GitHub, the commit duplicates ceased to be present

This process has highlighted the danger of rebase operations within a repository. Although I may occasionally rebase and edit a typo in an un-pushed commit, I think in the future, especially with pushed commits, I would prefer to make changes in a new commit and document the changes very well in a readme file

In the case of having an error within the commit message format for a while, I should have continued with a new format and made reference to the error in this document. The note would have been as follows:

*I have made an error with the first 95 commit messages within this repo. The commit messages do not indicate which documents have been worked on, leading to a more time consuming analysis of the commit history. I will endeavour to maintain a commit message structure which allows quick identification of the modified documents within the first line of the commit message [**document name here**]*

In future, if collaborating with others, I will clarify the format/content of commit messages to ensure a consistent method is applied throughout the project. I will avoid using the rebase facility of GitHub as much as possible