# NOVA Clinic

<p>
  <img src="assets/readme images/Nova.png" width="100%" alt="mock up photos">
</p>

[Click here to view the live project](https://8000-juginowakow-novaclinicp-fwcidu5t89p.ws-eu87.gitpod.io)

## Table of contents
1. Introduction
2. UX
    1. User Demographic
    2. User Stories
    3. Development Planes
    4. Design
3. Features
    1. Design Features
    2. Existing Features
    3. Features to Implement in the future
4. Issues and Bugs
5. Technologies Used
     1. Main Languages Used
     3. Frameworks, Libraries & Programs Used
6. Testing
    1. Testing User Stories
    2. Manual Testing
    3. Automated Testing
     - Code Validation
     - Browser Validation
    4. User Testing
7. Deployment
     1. Deploying on GitHub Pages
8. Credits
     1. Content
     2. Media
     3. Code
9. Acknowledgements
***

## Introduction
The goal of this website is to showcase a new (fictional) Aesthetic Clinic in Mnchester, UK. The clinic's webiste was created as the first part of the five Milestone projects required to obtain the Diploma in Full Stack Software development program at The Code Institute.

The inspiration for this site came from the fast growing trend of non-invasive beauty procedures in the UK area. The site focuses on representiving various treatments and serves as an introdution for new comers of various possibilities of aesthetic medicine. The site has commercial purpose.

The main requirements of this project are to build a responsive and static front-end site to present useful information to users using all the technologies learned so far, namely HTML5 and CSS3. The site is to contain no less than three pages.

[Back to the top](#nova-clinic)
## UX
### User Demographic
The ideal user for this website is:
* Current user
* Potential Patient
* Returning Patient
* Person with interest in eastetic medicine 

### User-Stories
#### Current User Goals
1. As a current user, I want to access the website easily and see up to date contact details, promotions and location of the clinic.
2. As a current user, I want to be bale to navigate through the site with ease and access the information I require with ease.
3. As a current user, I want to easily navigate to content I have previously viewed within a small number of steps.

#### Potential Patients
1. As a potential patient, I want to easily navigate the entire site intuitively.
2. As a potential patient, I want the information I seek to be easily accessible and relevant.
3. As a potential patient, I want attractive and relevant visuals and colour schemes that work with the content.

#### Returning Patients
1. As a returning patient, I want to be able to enquire about a follow up .
2. As a returning patient, I want the information I seek to be easily accessible and relevant.
3. As a returning patient, I want to see instructional images and/or videos with user controls relevant to the information.

#### Person with interest in aesthetic medicine
1. As a person with interest in aesthetic medicine, I want to be able to expand on my knoledge by fiding factually accurate content.
2. As a person with interest in aesthetic medicine, I want to access a sight that offers various top treatmnets.
3. As a person wih interest in aesthetic medicine, I want to easily navigate the entire site intuitively.

### Development-Planes
For the site to fuction as intended and fullfill its purpose for the user, the developer needs to develop all aspects of a fictinal healthcare facility. This includes the tratmnet description, enquiry page, team photo, clinics address and contact details so that the user can successfuly go through a patient journey from start to finish.

#### Strategy
Strategy incorporates user needs as well as product objectives. This website will focus on the following target audience, divided into three main categories:
- **Roles:**
    - Current Users 
    - Potential Patient
    - Returning Patient
    - Person with interest in aesthetic medicine

- **Demographic:**
    - fessional adults 
    - UK residents
    - Manchester residents (focus)
    - Interested in receiving a treatment

- **Psychographic:**
    - Middle to upper-class
    - Interested in beauty treatments 
    - Beauty oriented values
    - Trend focused


The website needs to enable the **user** to:
- Retrive the desired information:
    - Treatment guide and description
    - Preparation required for the appointment 
    - Medical opinion
    - Recommended treatment for personal circumstances
    - Clinic's address and contact details
    
The website needs to enable the **site manager** to:
- Gather queries from potential and returning customers 
- Gather customer details for reference and future marketing 

#### Scope
The scope plane is about defining requirements based on the goals established on the strategy plane. Using the information in the strategy plane, the identified required features have been broken into the following two categories.
- Content Requirements:
    - The user will be looking for:
        - Available tretamnts list and description
        - Tips on what treatment is best
        - Gallery to vie the results
        - Social Media links to confirm credibility of teh business
        - Reviews
- Fuctionality Requirements   
    - The user will be able to:
        - Contact the clinic to book an appoitment 
        - Be able to easily navigate the site to find the information they require

#### Structure
The information above were organized in a hierarchical tree structure, showing how users can navigate through the site with ease and efficiency, with the following results:
<details>

<summary>Structure of the Site</summary>

<p>
  <img src="assets/readme images/Sitemap.png" width="100%" alt="structure photos">
</p>

</details>

### Skeleton 
Wireframes were made to showcase the appearance of the site pages while keeping a positive user experience in mind. The wireframes were created using a desktop version of [Balsamiq](https://balsamiq.com/).

<summary>Skeleton of the Site</summary>

<p>
  <img src="assets/readme images/NOVA CLINIC - About Us page.png" width="100%" alt="Treatments Page Wireframes">
  <img src="assets/readme images/NOVA CLINIC - Contact us page .png" alt="Contact Page Wireframes">
  <img src="assets/readme images/NOVA CLINIC - Home page .png" alt="Home Page Wireframes">
</p>

</details>


### Design
#### Colour Scheme 
I have chosen my colour scheme by using [SheCodes](https://palettes.shecodes.io/) colour scheme palette based on bright pink (#f95959)contrast colour, which represents femininity and sensitivity whioch the clinic represents.

This is complemented by a dark blue (#233142), lighter blue (#455d7a), whitesmoke (#f5f5f5) and grey (#e3e3e3).
The grey shade (#e3e3e3) was used with .6 opacity to create a text overlay box on top of the hero picture on the main page.
Main content text is a dark blue (#233142) shade, as this colour creates the best contrast between other colours on the page, to gurantee the clean look of the website and high readibility of the text. The background palette includes some soft shades to make it easier to read for visually impaired individuals.

#### Typography
The typography pairing used on this site are [Aboreto, cursive](https://fonts.google.com/specimen/Aboreto?query=aboreto) and [Poppins](https://fonts.google.com/specimen/Poppins?query=poppin). A backup of Sans-Serif had been applied in case of an error.

Aboreto was used for the title,headings and contact information; Poppins was used for standard text.

#### Imagery
The selected imagery has been sourced from various sites. Some pieces, like the Review section or logo in the tab bar, were created using [Canva](https://www.canva.com/).

[Back to the top](#nova-clinic)

## Features
### Design Features
Each page within the site has a responsive and consistent navigation system. Deatiled features are included below.
- The **Header** is across the top of the page. It is not static because this would take too much space on thre screen and distract from the content. The Header is 100% in width and 150px in height.
- The **Navigation Bar** is positioned on the right side of the header, aligned with the title. It appears on all screen sizes.
- The **Footer** is 100% in width. The footer is located permanently at the bottom of teh page on all screen sizes. The fotter contains all social media links in the form of social media logos and a copywrite text in the middle.

<dl> 
    <dt><a href="index.html" target="_blank alt="NOVA Clinic Home Page">Home Page</a></dt>
    <dd>
        The <em>Home Page</em> is a scrollable page and its content is devided into maximum two columns, changing to one column on a smaller screen.
        <ul>
            <li>
            <em>Intro</em> - This "About Clinic" section introduces the customer to the site, it includes image and text elemets.
            </li>
            <li>
            <em>Mission Statement</em> - This is a text only section that states the main values of the clinic.
            </li>
            <li>
            <em>Reviews</em> - This is a graphic that I ahve designed that showcases the positive reviews the buisness had received.
            </li>
            <li>
            <em>Maps</em> - This section contains a map with the address of the business. The map width is 100% of the viewport.
            </li>
        </ul>
    </dd>
</dl>
<dl> 
    <dt><a href="treatments.html" target="_blank alt="NOVA Clinic Treatments Page">Treatments Page</a></dt>
    <dd>
        The <em>Treatments Page</em> is a scrollable page and its content is devided into two columns, changing to one column on a smaller screen.
        <ul>
            <li>
            <em>Intro</em> - 
            </li>
            <li>
            <em>Main Content</em> - This is a section containing images of teh treatments on the right-hand side and text on the left-hand side. The text is designed to explain the basic fuctions of the treatments.
            </li>
            <li>
            <em>Paragraph</em> - This is a text only section that includes an anchor with link to the contact.hmtl page. This is to enable customers to book apoitments easier after they familiarise themselves with the content.
            </li>
        </ul>
    </dd>
</dl>
<dl> 
    <dt><a href="contact.html" target="_blank alt="NOVA Clinic Contact Page">Contact Page</a></dt>
    <dd>
        The <em>Contact Page</em> is a scrollable page and its content is devided into two columns, changing to one column on a smaller screen.
        <ul>
            <li>
            <em>Intro</em> - This section explains to the user how to submit a query and in what time they should expect a reply.
            </li>
            <li>
            <em>Main Content</em> - This  section contain two boardered tables. The on the left contains the business's contact details and address. The table on the right is a submission form, all firld are required to be filled before the submission can be made.
            </li>
            <li>
            <em>Button</em> - This is Submit button that would issue to form to the correct, earlier chosen server.
            </li>
        </ul>
    </dd>
</dl>

### Existing Features
- **Header** - Appears on every page; This inludes the company name which is used throught the page to increase recognizability.
- **Navigartion Bar** - Appears on every page to provide visible and easily accessable navigation 
- **Footer** - Appears on the bottom of every page. This provides easy access to external links.
- **Social Media Links** - Appears in the footer, at the bottom of every page. Links are embedded in the social media icons and open in a new tab to provide better user experience.
- **Google Maps Embedded** - Appears on the bottom of the Home page, just before the footer. It is an iframe embedding for Google Maps showing the location of the NOVA clinic. The map is flexible and resizes depending on the screen taht its viewed on.
- **Contact Form** - Appears in the Contact page of the website. It provides point of contact for customers. Additionally all fields are required to avoid error submissions.
- **[Home Page](index.html "Home Page")** - Provides the user with basic information about the clinic and gives an overview of services. 
- **[Contact Page](contact.html "Contact Page")** - Provides the user with a form to initiate contact with the clinic; this could be a question or booking request/cancellation.
- **[Treatment Page](treatment.html "Treatment Page")** - Provides an overview and detailed description of the treatments.

### Features To Implement In The Future
- **Gallery**
    - **Feature** - create a page that displays the "before" and "after" of all treatments. 
    - **Reasons For The Feature Not Being Currently Included** - not suffient amount of time to execute this on a desired level.
- **Book Now Button**
    - **Feature** - create a page that allows user to book a tretament; with calendar and times available displyed and connected to a live booking system.
    - **Reasons For The Feature Not Being Currently Included** - not suffient amount of time to execute this on a desired level; also more advance coding skills required.
- **Expand on Treatments** 
    - **Feature** - create a separate page for each one of the treatments and feature particular team members that specialise in this particular procedures.
    - **Reasons For The Feature Not Being Currently Included** - not suffient amount of time to execute this on a desired level.

## Issues and Bugs
The developer run into a number of issues during the development of this site. The most interesting ones have been described below, thid includes the fix for the bug.

**Logo Bug** - A bug was detected whist trying to embed a logo for the page in the browser tab. The logo was uploaded using a [Favicon Generator](https://favicon.io/ "Favicon Generator") with their instructions but unfortunately did not dipslayed as expected. It turns out the link available on favicon was incorrect and eventually through trial and error the developer connected the right folders to the HTML header section. However, the logo was still not visible at times.To make sure the icon is visible every time the page is opened, the server was stoppped and restarted, the page was reloaded and cache removed from the browser with the help of my mentor Owonikoko Oluwaseun.This managed to rectify the issue permanently.
**Home Page Image Bug** - A bug was detected by the developer upon uploading images and text content to the main page. Due to the screen being split into two dolumns using sections and divs the developer was unable to align a large image within a designated space. The image kept cominhg up cropped or too big for the container. After a search online and converstaion with mentor, the developer decided to utilise a flex-container and therefore devided the space into two, equal columns with a help of Boostrap. This had rectify the issue and the developer successfully incorporated text and images into the project's main home page.
**Contact Form Bug** - Upon creating the Contact Form the developer realised that there is not eanough space between the input fields and the text above it, as well as the input fields itself are not big enough. This created a cramped space within the form and would negatively impact the user experience. The developer has used various sites used by codes, like [Slack](https://slack.com/intl/en-gb "Slack")and [Stack Overflow](https://stackoverflow.com/ "Stack Overflow"), to find different ways to fix this issue. The developer then created a css rule for input items by type (email,text.tel) and increased margin and padding. Thsi created the desired space and resolved the problem.

## Technologies Used
### Main Languages Used
- HTML5
- CSS3

### Frameworks, Libraries & Programs Used
[GitHub](https://github.com/ "Link to Github") - was used to store the project after pushing from Gitpod
[GitPod](https://www.gitpod.io/ "Link to Gitpod") - was used to write and commit the code as well as push to GitHub
[Font Awesome](https://fontawesome.com/ "Link to Font Awesome") - was used to obtain icons for the project
[Balsamiq](https://balsamiq.cloud/ "Link to Balsamiq") - was used to create Wireframes
[Google Fonts](https://fonts.google.com/ "Link to google Fonts")- was used to source fonts for the project
[Canva](https://www.canva.com/ "Link to Canva") - was used to create graphics for the project (Like the logo or reviews)
[Bootstrap](https://getbootstrap.com/ "Link to Bootstrap") - was utilised for flexi-containers and other helpful solutions to make the coide more responsive
[Am I Responsive?](https://ui.dev/amiresponsive "Link to Am I Respponsive?") -  was utilised to check if the site is responsive 
[Favicon](https://favicon.io/ "Link to Favicon") - was used to create a logo for the business and browser tab 

[Back to the top](#nova-clinic)

## Testing
## Testing User Stories

#### Current User Goals:
1. As a current user, I want to access the website easily and see up to date contact details, promotions and location of the clinic.
    - Footer includes links to social media where news and promotion would be posted 
    - Navigation bar includes a clear tabs describing their purpose
    - Map is included on the bottom of the page and displays the address 

2. As a current user, I want to be bale to navigate through the site with ease and access the information I require with ease.
    - Navigation bar is easily accessible and visible at the top of the page
    - Navigation bar takes the user to the correct destination and is lebelled correctly
    - The footer menu is easy to use; including social media icons taking a user to the correct page 

3. As a current user, I want to easily navigate to content I have previously viewed within a small number of steps.

    - Navigation bar is easily accessible and visible at the top of the page
    - Navigation bar takes the user to the correct destination and is lebelled correctly
    - Wesbite's layout is easy to navigate 

#### Potential Patients
1. As a potential patient, I want to easily navigate the entire site intuitively.

    - Navigation bar is easily accessible and visible at the top of the page
    - Navigation bar takes the user to the correct destination and is lebelled correctly
    - Wesbite's layout is easy to navigate 

2. As a potential patient, I want the information I seek to be easily accessible and relevant.

    - Treatments made, if the site were real, would be regulary updated with new tretaments information 
    - The footer includes social media icons that user can use to access social media account where further information about the clinic can be obtained 
    - Navigation bar is easily accessible and visible at the top of the page

3. As a potential patient, I want attractive and relevant visuals and colour schemes that work with the content.

    - All pages include images relevant to the content 
    - Colour scheme is pleasing to the eye and easily readible 

#### Returning Patients 
1. As a returning patient, I want to be able to enquire about a follow up.

    - Navigation bar is easily accessible and visible at the top of the page
    - Home page and Treatment page include links to the contact page and the links are easy to notice 

2. As a returning patient, I want the information I seek to be easily accessible and relevant.

    - Treatments page, if the site were real, would be regulary updated with new tretaments information 
    - The footer includes social media icons that user can use to access social media account where further information about the clinic can be obtained 
    - Navigation bar is easily accessible and visible at the top of the page

3. As a returning patient, I want to see instructional images and/or videos with user controls relevant to the information

    - All pages include images relevant to the content 
    - Colour scheme is pleasing to the eye and easily readible 

#### Person with interest in aesthetic medicine
1. As a person with interest in aesthetic medicine, I want to be able to expand on my knowledge by finding factually accurate content.

    - Treatments page, if the site were real, would be regulary updated with new tretaments information 
    - The footer includes social media icons that user can use to access social media account where further information about the clinic can be obtained 
    - Navigation bar is easily accessible and visible at the top of the page

2. As a person with interest in aesthetic medicine, I want to access a sight that offers various top treatments.

    - Navigation bar is easily accessible and visible at the top of the page
    - Treatments page, if the site were real, would be regulary updated with new tretaments information 

3. As a person with interest in aesthetic medicine, I want to easily navigate the entire site intuitively.

    - Navigation bar is easily accessible and visible at the top of the page
    - Navigation bar takes the user to the correct destination and is lebelled correctly
    - Wesbite's layout is easy to navigate 

## Manual Testing

### Common Elements Testing
Manual testing was conducted on the following elements that appear on every page:

- Hovering over the navigation bar to trigger the hover effect and underline the item

<p>
  <img src="assets/readme images/Hovering over nav-bar.png" width="100%" alt="hover test">
</p> 

- Clicking on the navigation bar menu items to take the user to the correct page on the
website

<p>
  <img src="assets/readme images/Treatment Page opening .png" width="100%" alt="nav-bar treatment test">
  <img src="assets/readme images/Contact Page opening.png" width="100%" alt="nav-bar contacttest">
</p> 

- Clicking on the navigation bar menu items to take the user to the correct page on the
website
    Facebook
    Twitter
    Instagram
    LinkedIn

  <p>
  <img src="assets/readme images/Social Media opening in new page .png" width="100%" alt="social media test">
  </p>  

### Home Page
Manual testing was conducted on the following elements of the [Home Page](index.html):

- The responsiveness of the page
<p>
  <img src="assets/readme images/home content responsiveness.png" width="100%" alt="home content reponsiveness test">
  <img src="assets/readme images/home-page responsiveness.png" width="100%" alt="home page responsiveness test">
  <img src="assets/readme images/maps responsiveness.png" width="100%" alt="home page maps responsiveness test">
  <img src="assets/readme images/reviews responsiveness.png" width="100%" alt="home page reviews responsiveness test">
</p>  

- Booking link within the text element on the page

 <p>
  <img src="assets/readme images/booking link in home.png" width="100%" alt="booking link">
</p>  

- Maps open in a separate window and user is able to scroll in and out the map on the page

 <p>
  <img src="assets/readme images/interactive maps.png" width="100%" alt="maps test">
</p>  

### Treatments Page

- The responsiveness of the page

<p>
  <img src="assets/readme images/treatment reponsiveness.png" width="100%" alt="treatment page responsiveness">
  <img src="assets/readme images/treatments  responsiveness.png" width="100%" alt="treatment content responsiveness">
</p>  

- The booking link with the paragraph on the bottom of the page

<p>
  <img src="assets/readme images/booking link in treatments.png" width="100%" alt="booking link treatments">
</p> 

### Contact Page

- The responsiveness off the page

<p>
  <img src="assets/readme images/contact page  reponsiveness.png" width="100%" alt="contact page responsiveness">
  <img src="assets/readme images/contact details reponsiveness.png" width="100%" alt="contact details responsiveness">
  <img src="assets/readme images/enquiry reponsiveness.png" width="100%" alt="enquiry responsiveness">
  <img src="assets/readme images/footer responsiveness.png" width="100%" alt="footer responsiveness">
</p>  

- When filing out the contact form, the user is required to fill out all the field before
submission is possible

<p>
  <img src="assets/readme images/field required contact form .png" width="100%" alt="required contact">
</p> 

- Clicking on the email will atomatically open the email draft

<p>
  <img src="assets/readme images/email automatically opens contact .png" width="100%" alt="email automatically ">
</p> 

## Automated Testing

### Code Validation
The [W3C Markup Validator](https://validator.w3.org/) service was used to validate the `HTML` and `CSS` code used.

**Results:**

- Home Page

<p>
  <img src="assets/readme images/NOVA CLINIC - Home page .png" width="100%" alt="Home Page Validator">
</p> 

- Treatments Page

<p>
  <img src="assets/readme images/HTML Validator Treatments Page.png" width="100%" alt="Treatment Page Validator">
</p> 

- Contact Page 

<p>
  <img src="assets/readme images/HTML Validator Contact Page .png" width="100%" alt="Contact Page Validator">
</p> 

- CSS 

<p>
  <img src="assets/readme images/CSS Validator.png" width="100%" alt="CSS Validator">
</p> 


### Browser Validation
- Chrome

<p>
  <img src="assets/readme images/Chrome view .png" width="100%" alt="chrome test">
</p> 

- Firefox

<p>
  <img src="assets/readme images/Firefox view.png" width="100%" alt="firefox test">
</p> 

- Safari

<p>
  <img src="assets/readme images/Safari view.png" width="100%" alt="safari test">
</p> 

## User testing 
Couple of my family members and a fiend have been asked to review the page for user
experience and to point out any bugs/issues. The input of this group led to small UX adjustments to improve the overall site appearance and user experience.


## Deployment 
This milestone project was developed using [GitPod](https://www.gitpod.io/ "Link to GitPod site"), which was then committed and pushed to GitHub using the GitPod terminals.

### Deploying on GitHub Pages
Below there are instruction on how to successfuly deploy this page to GitHub Pages from its GitHub repository.

1. Sign up to [GitHub](https://github.com/signup "Link to the GitHub Sign Up Page") or if you already have an account, simply [Log In](https://github.com/login "Link to log in to GitHub")
2. Find the [GitHub Repository](https://github.com/juginowakowska/Nova-clinic-project "Link to the Nova Clinic Repository)
3. At the top of the repository, select Settings from the menu items.
4. Scroll down the Settings page to the "Pages" section.
5. Under "Source" click the drop-down menu labelled "None" and select "Main".
6. Upon selection, the page will automatically refresh meaning that the website is now deployed.
7. Scroll back down to the "Pages" section to retrieve the deployed link.

To work on the project code within a local IDE, such as VS code etc :
1. Follow this link to the project [Github Repository](https://juginowakow-novaclinicp-buf53w2mqkz.ws-eu87.gitpod.io/)
2. Under the repository name click "Clone or download".
3. In the Clone with HTTPs section, copy the clone URL for the repository.
4. In your local IDE open the terminal.
5. Change the current working directoryto the location where you want the clone directory to be made.
6. Type - git clone - and then paste the URL you copies in Step 3.
7. Press Enter and your local clone will be created.

## Credits

### Content 
- Text used in the project was borrowed and adapted from multiple different pages, some of them are listed below.
    - [Medical News Today](https://www.medicalnewstoday.com/articles/158647#summary "Link to Medical News Today Article")
    - [Botaniqua Clinic](https://www.botaniqua.co.uk/ "Link to Botaniqua Clinic Page")
    - [Beauty Empire Clinic](https://www.beautyempireclinic.com/ "Link to Beauty Empire Clinic")
    - [Icoon Webpage](https://www.icoone.com/en/news/lymphatic-drainage-the-self-care-trend-to-strengthen-your-health/ "Link to the Icoon Website")

### Code
- Multiple website were consulted and visited whilst developing this project in order to bettter understand the code that is being used and utlise the developers knowledge gained so far. Pages used for reference are included below :
    - [W3Schools](https://www.w3schools.com/ "Link to W3Schools page")
    - [Stack Overflow](https://stackoverflow.com/ "Link to Stack Overflow")
    - [CSS-Tricks](https://css-tricks.com/ "Link to CSS Tricks Site")

### Media
- Various platforms and pages were used for sourcing images included in this project, main page used was [Google Images](https://www.google.com/imghp?hl=EN "Link to Google Images Page")

## Acknowledgements 
- I would like to thank my mentor Owonikoko Oluwaseun for her help and patience, whilts I was preparing this Milestone Project.
- I would also like to thank the coders community who created a various documnts explaining how HTML5, CSS3 and Bootsrap work, so I could use that as a base to create my own, unique website.
- I would like to thank my family for the objective feedback and support.

