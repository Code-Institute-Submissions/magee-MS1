# Mike Magee - Code Institute Milestone1

My imaginary client is a two person Drone company - "Aerial Shots" (AS) from Salem Ma.  AS was an early drone technology adopter, flying over 4,000 commercial flights since 2012.  AS established a great word-of-mouth reputation but is losing work to unscrupulous illegal operators trying to steal their business by using cheap unregistered drones and race-to-the-bottom rates.  

AS needs a website that will help set them apart from their new uncredentialed competitors and persuade them to weigh results, experience and reliabilty over price.

AS is strictly a B2B company. 

The business goals of the website:
- Establish brand awareness.
- Establish credibility, reliability and experience.
- Demonstrate quality work.
<br>
<br>
***
## UX
A typical B2B client will approach the site looking for in (decreasing order of importance) the following information:
- Quality visual work
- Referrals
- Experience
- Accreditations
- Safety and insurance record
- Technical details

Client Stories - Ultimately the client will want to:
- Navigate intuitively between various topic related page.  The goal is to move intuitively. 
- Easily locate and review the information described above.  The goal is to quickly obtain satisfaction that AS is credible, experienced, accredited, etc.   
- Browse galleries galleries and images.  The goal is to be sure that the content types, quality and variety will fit their requirements, 
- Submit a request for contact and get a free teaser document in the process.  The goal is to establish a relationship in a timely fashion and move their evaluation closer to enough satisfaction about conducting business.  

***
This section is also where you would share links to any wireframes, mockups, diagrams etc. that you created as part of the design process. These files should themselves either be included as a pdf file in the project itself (in an separate directory), or just hosted elsewhere online and can be in any format that is viewable inside the browser.

- [Main ->](projectrelated/magee-ms1-main-wf.png)

- [Contact ->](projectrelated/magee-ms1-contact-wf.png)

- [Gallery ->](projectrelated/magee-ms1-gallery-wf.png)

<br>
<br>

***
## Features
My mentor suggested a simple feature focusing on the Milestone submission deadline. 
*   <span style="color:green">GREEN</span> are features that I definitely want to include in the MS1 submission. 
*   <span style="color:orange">ORANGE</span> are stretch goals that I would like to include in the MS1 submission. 
*   <span style="color:INDIANRED">RED</span> are features that I will not include in the MS1 submission, but would like to record them for the future. 

### Page specific features

#### <span style="color:green">Homepage </span>
* <span style="color:green">(must)Jumbotron welcome section - Catch the visual attention of the user, demonstrate quality and provide intro and marketing text</span>
* <span style="color:green">(must)Section - OVERVIEW of credentials, certifications, experience </span>
* <span style="color:green">(must)Section - OVERVIEW of Safety and operational issues</span>
* <span style="color:orange">(stretch)Embedded video introduction - A 30 second video of Client attempting to establish initial trust   This will eventually move to About and be slightly more comprehensive  </span>
* <span style="color:orange">(stretch)Referrals - Scrollable list of a dozen or so </span>
* <span style="color:orange">(stretch)Make page scrollable up to reveal more content </span>

#### <span style="color:green">Gallery </span>
* <span style="color:green">(must)Hero Image</span>
* <span style="color:green">(must)Introductory text</span>
* <span style="color:green">(must)Mixed gallery of various shots/media</span>

#### <span style="color:green">Contact</span>
* <span style="color:green">(must)Hero Image</span>
* <span style="color:green">(must)Introductory text</span>
* <span style="color:green">(must)Basic 4 field information collection</span>
* <span style="color:green">(must)Checkbox to request promotional material</span>
* <span style="color:INDIANRED">(later)Calendar date selection</span>
* <span style="color:INDIANRED">(later)Map location selection</span>

#### <span style="color:INDIANRED">(later)About Page</span>  (Detailed credentials, certifications, experience, bio & photos ETC.. )
#### <span style="color:INDIANRED">(later)Classic Blog Page</span>
#### <span style="color:INDIANRED">(later)Commercial related Page</span> 
#### <span style="color:INDIANRED">(later)Pricing Page</span> 


### Global features
#### <span style="color:green">Header </span>
* <span style="color:green">(must)Horizontal menu links to any live pages </span>
* <span style="color:orange">(stretch)Mobile hamburger menu </span>

 #### <span style="color:green">Footer </span>
* <span style="color:green">(must)Social links </span>
* <span style="color:green">(must)Copyright</span>
 
<br>

***
## Technologies Used

In this section, you should mention all of the languages, frameworks, libraries, and any other tools that you have used to construct this project. For each, provide its name, a link to its official site and a short sentence of why it was used.

- [JQuery](https://jquery.com)
    - The project uses **JQuery** to simplify DOM manipulation.
- HTML Validation by freeformatter
    - https://www.freeformatter.com/html-validator.html
- CSS Validation by W3C
    - https://jigsaw.w3.org/css-validator/
- Development framework Visual Studio Code (mac) by Microsoft v1.44.1

******
## <span style="color:GREEN">Testing</span>

There should be no visible difference in behavior between browsers.  I have tested with:  
- Chrome Version 81.0.4044.122
- Firefox Version 75.0 (64-bit)
- Safari Version 13.0.5 (15608.5.11)

In this section, you need to convince the assessor that you have conducted enough testing to legitimately believe that the site works well. Essentially, in this part you will want to go over all of your user stories from the UX section and ensure that they all work as intended, with the project providing an easy and straightforward way for the users to achieve their goals.

Whenever it is feasible, prefer to automate your tests, and if you've done so, provide a brief explanation of your approach, link to the test file(s) and explain how to run them.

For any scenarios that have not been automated, test the user stories manually and provide as much detail as is relevant. A particularly useful form for describing your testing process is via scenarios, such as:

1. Home:
    1. Navigate to the "Home" page by initial landing, from the menu item or by the icon and :Aerial Shots" label on the nav bar
    2. Each of the 3 sections is intended to be very visual, attempting to let the images impress the user.  The text is kept somewhat non-structured, simply white and sparse.  The 3 sections are :
        - Main / Callout 
        - Experience and credentials is intended as an overview.  Eventually, there should be a page dedicated to it. 
        - Safety, planning and diligence.  As with the previous section, it is intended as an overview.  Eventually, there should be a page dedicated to it.  
    3. The form should be sizable without any loss of content.
    4. Confirm that the copyright text in the footer gets hidden at small sizes, leaving just the social media.  The hamburger should appear and everything should be in a single column for presentation.
    5.  Problems - I'm having sizing issues with a left and right margin, and controlling the text when things get smaller.

2. Contact:
    1. Go to the "Contact" page from the menu item
    2. Try to submit the empty form and verify that an error message about the required fields appears
    3. Try to submit the form with an invalid email address and verify that a relevant error message appears
        - All 3 input fields are required.  The  checkbox is not  
    4. There is no back end or JS so there will be no success indication
    5. The form should be sizable without any loss of content.
    6. Confirm that the copyright text in the footer gets hidden at small sizes, leaving just the social media.  The hamburger should appear and everything should be in a single column for presentation.

 ==================================================

3. Gallery:
    1. Go to the "gallery" page from the menu item
    2. This is a very basic display of some work.  
    3. I found that the landscape nature and size of shots did not lend themselves to tiling.  
    4. I would search for some plugin to use instead of a basic html view and I would have a menus that broke the work and pages down with more granularity.  I found a few of these in the last day, but I was not able to generate the appropriate thumbnails to go with the images.
    5. The form should be sizable without any loss of content.
    6. Confirm that the copyright text in the footer gets hidden at small sizes, leaving just the social media.  The hamburger should appear and everything should be in a single column for presentation.

You should also mention in this section any interesting bugs or problems you discovered during your testing, even if you haven't addressed them yet.
 ==================================================


## Deployment

This sample site is set up to use git pages based on the current code version in Git.    

- Pages location is:  https://michaelmagee.github.io/magee-MS1/

This sample site can easily run locally in the VSCode IDE by using the GoLive feature.

### Gitpod Reminders

To run a frontend (HTML, CSS, Javascript only) application in Gitpod, in the terminal, type:

`git pull`   To be sure that the code is current
`python3 -m http.server`  

A blue button should appear to click: *Make Public*,

Another blue button should appear to click: *Open Browser*.



## Credits
- Example MD content ideas reviewed from AJGreaves 
- Organizational and planning support from Mentor Brian M.  
- Fixed Sticky header and footer from getbootstrap doc 
- Attempted color inspiration from color.adobe.com

### Environment 
- Code Institute student template for Gitpod was used
- Locally, Visual Studio Code, periodically pushing to Githib/Gitpod

### Content
- All text and images are mine.

### Media
- Drone Fav Icon info from https://icons8.com/icon/pack/photo-video/small

*Any general project related support documents are in /projectrelated*


### Acknowledgements

- I received inspiration for this project from examples from Code Institute that I played with as I was learning.  
- I took several classes in parallel on Lynda to get different approaches