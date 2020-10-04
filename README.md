# Unit 16 Project 2 Homework: Professional Materials

Now that you've built a full-stack web application and have another project to share, you'll be updating your portfolio page and other materials to build toward being employer competitive.

If you are opting out of career services, this is *still a required assignment*. Part of being a web developer means being a part of a community. Having a place to share your projects is *necessary* if you're applying for jobs, but is still *critical* on your journey as a developer.


## Requirements

* Updated portfolio featuring projects 1 and 2 and at least four exemplary homework assignments.

* Update GitHub profile with pinned repositories featuring projects 1 and 2 and four exemplary assignments. 

* Updated resume

* Updated LinkedIn profile


## Grading

| Requirement      | Weight |
|---               |---     |
| Portoflio        | 40%    |
| GitHub Profile   | 40%    |
| Resume           | 10%    |
| LinkedIn Profile | 10%    |


## Instructions

1. [Updated Portfolio](#updated-portfolio)
2. [GitHub Profile](#updated-github-profile)
3. [Updated Resume](#updated-resume)
4. [Updated LinkedIn](#updated-linkedin)

### Updated Portfolio

Your updated site should have the following content:

* Your name

* Links to your GitHub profile & LinkedIn page as well as your email address and phone number

* A link to a PDF of your resume

* A list of projects. For each project, make sure you have the following:

  * Project title

  * Link to the deployed version

  * Link to the GitHub repository

  * Screenshot of the deployed application

* Deploy your portfolio to GitHub Pages


#### Design

Unfortunately, this is where it gets a little bit subjective. Your site should look
"polished." Here are a few guidelines on what that means:

* Mobile-first design

* Choose a color palette for your site so it doesn't just look like
the default bootstrap theme or an unstyled HTML site.

* Make sure the font size is large enough to read, and that the colors don't cause eye strain.


### Updated GitHub Profile 

* If you haven't yet, now is the time to update the following in your GitHub profile: 

    * Profile picture

    * Bio

    * Location

    * Email

    * Link to your portfolio

* Employers (and potential collaborators) _will_ look at your GitHub profile, so put your best face forward. 

* Pin some repos that you want to highlight

  * Navigate to [GitHub](https://github.com/) and go to your profile.

  * Click "Customize your pins"

  * Click the checkboxes for your project and 2-3 homework assignments that you would like to share

  * Make sure each of these projects is deployed and add a link to the deployed project in their README files

* Follow your classmates. They are the beginning of your professional network and being a developer is as much about being a part of the community as it is writing code. 


### Updated Resume 

Submit a clear, concise and compelling resume, tailored to the type of job you’re looking for.


### Updated LinkedIn Profile 

Update your LinkedIn Profile with a strong bio statement, a professional photo, and links to your Github and portfolio.

## Version History

portfolio_sa_v1.0 - Initial git commit; Used crude layout from in-class assignment for both index.html & style.css.

portfolio_sa_v1.1 - Added Bootstrap CSS link (index.html lines 16-20); Commented and formatted the head of index.html for readability.

portfolio_sa_v1.2 - Added Navbar to index.html as place holder element to begin web page mock-up (index.html lines 36-85).

portfolio_sa_v1.3 - Commented-out undesired aspects of stock nav bar element (index.html lines 40, 42-44, 62-83, 87-90). Reduced down to 3 nav links "about", "portfolio", "contact".

portfolio_sa_v1.4 - Changed title element to "About" (index.html line 12); Copied contents of index.html to portfolio.html & contact.html, leaving only the nav element in the body w/ reconfigured link adresses (portfolio.html & contact.html lines 44, 48, 52)(This accounts for directory level difference between index.html and the other 2 html files in assests).

portfolio_sa_v1.5 - Removed commented-out sections (index.html lines 62-83, 87-90); Removed "assests" from style.css relative path, to establish link to styles sheet (portfolio.html & contact.html line 26).

portfolio_sa_v1.6 - Added button element for toggling the nav options while the site is scaled down for mobile (index.html lines 43-54)(portfolio.html contact.html lines 40-51); Also added jQuery/ Bootstrap script elements to get the button to toggle.

portfolio_sa_v1.7 - Added the Nav Bar Brand back in, and added my name in as the "brand" (index.html portfolio.html contact.html line 40); Removed header element with "Your Name" content since I made the nav element display my name (index.html portfolio.html contact.html lines 32-34).

portfolio_sa_v1.8 - Added a mian semantic tags around the about placeholder content (index.html lines 76, 92); Added sticky footer (index.html lines 95-99)(portfolio.html contact.html lines 78-82); Added footer style properties for the sticky footer (style.css lines 58-65);

portfolio_sa_v1.9 - Removed heading 2 with my name in it (index.html line 82); Added 3 paragraphs of lorem (index.html lines 84-86); Added .sticky-top class to my nav element so that the user can scroll down if the content on the page is long, and the nave bar will still be visible (index.html line 34); Removed unused/unwanted classes and id's to fix bugs with the nav bar (style.css lines 12-56).

portfolio_sa_v2.0 - Changes mr-auto to ml-auto to shift the nav links to the left when using larger view port (index.html line 56); Updated website version number in the footer text (index.html line 97)(Note: will not make a note of version number updates to the footer going forward).

portfolio_sa_v2.1 - Added role= "main" to the main element to help screen readers and other assistive technologies understand where the main content begins (index.html line 76); Added class "my-container" to further style the container in the main section (index.html line 78); Created a card around the main content in the about section (index.html lines 80-100).

portfolio_sa_v2.2 - Added line divider between heading and image within the card in the "main" element (index.html line 89)(style.css lines 11-13); Added id selector for about image with padding top to give space between image and line (style.css lines 15-17).

portfolio_sa_v2.3 - Added a container around the footer text to add collapsing functionality (index.html lines 111,113); Changed the footer text paragraph tag to a span tag, so as to not render a blank line below (index.html line 112); Added class="text-muted" to grey out the footer text (testing this style)(index.html line 112); Added html selector with the relative position property and min-height set to 100%, added a margine-bottom of 40px to the body selector since my footer is 40px in height, set the height of the footer to 40px, added property line-height to center text vertically, added text-align: center (style.css lines 1-4, 15, 27, 33, 36, 40).

portfolio_sa_v2.4 - Copied all the changes made to improve the nav bar, footer, and page layout in index.html and moved them to portfolio.html, and contact.html as template to start working off. Other than the relative link paths, and header text, the three pages are the same.

portfolio_sa_v2.5 - Added class="float-md-left" to float left on viewports sized MD (medium) or wider as configred at the moment (index.html lines 92, 96); Added class="TextWrap" to index.html (index.html line 94), and .TextWrap selector with image centering properties for mobile (style.css lines 23-28).

portfolio_sa_v2.6 - Added relative link to the for my pictue in the about section (index.html line 94) "about" Removed img selector and its properties (style.css lines 32-34); Added padding to my image to give space between the picture and the text wrap (style.css lines 28,29).

portfolio_sa_v2.7 - Added line divider between heading and image within the card in the "main" element (contact.html line 90); Added form elements for First and Last name, Email Address, and Message (contact.html line 92-132); Added a top padding of 20px to the feilds mentioned above to space them out (style.css lines 22-24).

portfolio_sa_v2.8 - Added viewport meta element, ensuring content will be display properly according to the device width (index.html portfolio.html contact.html line 10).

portfolio_sa_v2.9 - Added a font size to the footer as it was overflowing (index.html portfolio.html contact.html lins 119, 113, 148);

portfolio_sa_v3.0 - Added 8px space between footer and cards on all three pages (style.css line 17); Added unique class names to the div elements that contain forms elements in the "contact" page to adjust spacing (contact.html lines 117, 124); Added selector "form-group-2" and property to add space between the submit button and the "message" form element in "contact" page (style.css line 31-33); Removed commented-out lines (style.css lines 54-56); Added 6 card elements within the main portfolio card element, with place holder images and headings to frame page layout (portfolio.html lines 92-166).

portfolio_sa_v3.1 - Added class "row-1" to the first row of cards (portfolio.html line 92); Added class selector "row-1" and property to add 12px of space between the line border, and the first row of cards in portfolio page (style.css lines 25-27).

portfolio_sa_v3.2 - Added personal text to the about me section (occured prev commit)(index.html lines 101-105); Added image of oil pan project final design, to my first card in my portfolio page (portfolio.html line 99); Spelled out my name in the alt attribute for my pictue in the "about" page (index.html line 96). Added pictures as well as height/ width properties to scale the images (portfolio.html lines 99,110,121,138,149,160); Changed all the card headings from h5 to h6 size, aswell as the heading text to be descriptive (portfolio.html lines 97,108,119,136,147,158).

portfolio_sa_v3.3 - Added class "cardHeight" to to all cards in the portfolio page for card height control (portfolio.html lines 95, 106, 117, 134, 145, 156); Made all the classes associates with the images in the cards the same to define a uniform height, and removed height/ width properties (properties.html lines 138, 149, 160); Added class selector "cardHeight" and set height to 200px (style.css lines 41-43); Added class selector "Project" and set height/ width properties as well as image centering properties (style.css lines 31-39).

portfolio_sa_v3.4 - Changed portfolio theme by adding SVG Hero background (style.css line 22); Changed background and nav bar link text color to match vs code dracula theme (style.css lines 19, 48); Changed nav bar and body text font using Bangers and Saira google fonts (index.html portfolio.html & contact.html lines 32, 49, 71, 75, 79); Added font awesome icons to footer for PDF resume, Git Hub Profile, Linkedin Profile, and email contact (index.html lines 24-29, 131-136)(portfolio.html lines 24-29, 191-196)(contact.html lines 24-29, 158-163).

portfolio_sa_v3.5 - Added links to the github and linkedin icons, so that when clicked the user will be redirected to my respective profiles (index.html lines 133, 135)(portfolio.html lines 193, 195)(contact.html lines 160, 162)(style.css lines 97-103).

portfolio_sa_v3.6 - Added pop-over that displays email address upon email icon button click (index.html lines 170, 188-192)(portfolio.html lines 230, 248-252)(contact.html lines 197, 215-219); Added modal to display resume image and provide option to download pdf resume (index.html lines 128-152, 160-162)(portfolio.html lines 188-212, 220-222)(contact.html lines 155-170, 187-189).

portfolio_sa_v3.7 - Added showcase projects to my portfolio section, including the deployed project links as the displayd images, and the github logo as the link to the github repo fir each project (portfolio.htlm lines 93, 94, 104-196); Changed the appearacne of the porfolio project cards, and changed the background color to a gradient from white to lightgrey in the content cards for each page (styles.css lines 57-60, 63-71, 98-106).

portfolio_sa_v3.8 - Styled About me section (index.html lines 97, 99, 101-113)(style.css lines 52-56, 77-102).

portfolio_sa_v3.9 - Added mailto/tel to my email and phone number in the contact info pop-over (index.html lines 174, 194-207)(portfolio.html lines 254, 274-287)(contact.html lines 197, 217-230).

portfolio_sa_v4.0 - Updated portfolio section to reflect the current projects pinned on my github (portfolio.js lines 109, 122, 117, 145, 148, 153, 205, 208, 213).

## Wish List

Modal pop-ups to enlarge portfolio gifs for better viewing on desktop devices.

- - -
© 2019 Trilogy Education Services, a 2U, Inc. brand. All Rights Reserved.
