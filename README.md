![Responsive website images](/README-attachments/responsive-screenshots.JPG "Responsive website images")

# **MILESTONE PROJECT ONE**

This project is based on my experience as a Quantity Surveyor (QS).  The website presents key data about construction projects, including descriptions,cost data, project timelines and a small gallery of images for users to refer to when needed.

The website can be viewed [here](https://dkeddie.github.io/project-one-v2/)

Whilst I have utilised concepts/names/images from my current employer / project, the data used is not accurate.  If fully implemented, the webpage would summarise and compare a selection of projects from Wembley Park, putting at the fingertips key information that non-QS client body stakeholders can look up on-demand.  The information may be presented to non-project stakeholders (e.g. funders), which will give a snapshot of data that they may compare against other projects.


## **UX**

### **Who is the Website for?**

The Website is primarily for Developer Clients, Development Managers and Project Managers ('clients'), who work alongside the QS.  The QS will ensure the data is correct and up to date.


### **User Stories**

My experience as a QS has led me to the following discern the following objectives:-
 **Item** | **Experience** | **Objectives**
---------|----------------|---------------
1 | Clients regularly ask for high level cost information on projects, they do not store the data themselves | Provide a website that clients have access to which provides past and present cost information from their projects
2 | Clients want to be able to compare projects against one another | Include an Overview page which shows projects lined up against one another
3 | Information is normally maintained offline in a variety of formats and locations, which may not be consistent | Collate diverse pieces of information to provide a means to centralise and standardise data storage
4 | Delivery of information can sometimes be rushed, resulting in poor presentation and / or incomplete information | The website should provide information in a clear and consistent format, so that users will become familiar with the site and the data
5 | Clients will request information; there is often a time-lag to deliver that information due to the need to locate it | The website should be a primary means to store data by QSs

I believe clients will greatly appreciate a hiigher level of access to information which is maintained on their behalf, as the information is often sought for time-critical reasons and ensure that information is presented in a consistent and professional manner.


### **Functions of the Website**

The functions of the website are to:-

1. Provide a 'lite' repository of projects with key information for stakeholders to access data on-demand.

2. Users will be able to discern from each Project page:-

   * A high level description of the project - this will allow users not familiar with the project to learn important information about the project. The content may include a description of the building as a minimum, but may be extended to include other key information like areas of buildings, the number of apartments, tenure types, etc.  This could be included in future interations of the website.

   * The project timeline will provide users with the overall duration of the project, from early design and planning stages through to construction.  The full detail of a project programme is not often recorded, often limited to construction durations, the final, longest and period of greatest expenditure.  However, the overall duration is obviously important and other parts of the programme can be useful and informative, too.

   * The cost breakdown will provide users with high-level, key cost information.  The information is displayed on a cost per sqft basis, rather than the total cost.  Whilst the total cost is obviously important, users will ask for the cost per sqft 9 out of 10 times in order to compare to other projects, and utilise the information for planning future projects.

   * A gallery has also been included so users may see how the project appears.  Some users may use the site to refer for information, but may not have had any involvement in the project, so will be particularly relevant.

3. The Overview page summarises key aspects of the Project pages:-
   * The timeline shows overlapping construction (only) durations. As the construction duration is the most visible and cost significant period of the project, the Overview page limited the timeline to this aspect for comparison purposes.
   * A benchmark of the Projects included displays a comparison of the building costs per sqft.  As noted above, the cost of a project will be frequently sought by clients.  This graph also displays the average cost, which users will also want to know.

4. The footer includes:-
   * A site map of Wembley Park with locations of the Projects, and
   * Website links to the corporate websites.


## **Design**

### **Mobile v. Desktop**

The site was developed with a desktop approach primarily, but still mobile-friendly.  Most users will access the website from their computer whilst working, but there may be occassions when they need to access data on-the-go for quick reference.

With this in mind, the site has two variants to reflect the desktop / landscape and mobile / portrait variants.  As such, I have utilised one breakpoint at Medium / 768px.

The website will still be useable on portrait screen sizes at this size.  The website also has a maximum width of 1200px maintain design ratios on extra large screens.


### **Key concepts**

* Limited scrolling - the page should largely be visible on one desktop screen.
* Continuity of page design across the pages and minimal variation in the design of each page.
* Predominatly white screen and limited colour pallette and backgrounds to focus on the data presented.
* Graphs / Charts - being able to incorporate charts was very important for presenting the cost data.


### **Wireframe**

Use of Figma to develop key concepts into framework to commence web development.  Two pages were worked up, for desktop and mobile, in the knowledge that the basic page design would be replicated across the pages.

A copy of the original wireframe can be found here: [Figma](https://www.figma.com/file/rbTyJlZNq6apXDVEMjG21f/Project-1?node-id=12%3A0) or [PDF](README-attachments/Wireframe.pdf)

Whilst my wireframe did not incoproate the footer, I knew that I would likely want to add this at a later point.  The contents would be minimal and yet to be decided, as the would be subsidiary to the other information provided.


### **Colours**

To maintain a colour theme that is consistent with the logos of Quintain and Wembley Park, a primary colour pallette was developed from the Quintain logo.

The main colour use for fonts and borders is limited to the same colour as the Quintain logo.  Where greater depth or diversity of colours were required for the likes of graphs, a fuller pallette was developed by using Paletton.

The colour pallette can be viewed [HERE](http://paletton.com/#uid=c0w3k0Z3N0k6hjd2BtG4vnW82ekcH9w)

The Wembley Park logo is orange and was not deemed suitable for the primary pallette, but still appropriate for highlighting or drawing attention to items against the primary pallette.


### Typography

The Montserrat font is the main font used throughout the whole website with Sans Serif as the fallback font in case for any reason the font isn't being imported into the site correctly. Montserrat is a clean font used frequently in programming, so it is both attractive and appropriate.

Whilst acknowledged that this font has been used frequently in the Code Institute course to date, after experimenting with a few other fonts, I still felt that it is the most appropriate font to use for this project for the reasons noted.


### Imagery

As the website is meant to be functional, there is no background images and limited background colours utilised to maintain a clear, crisp display that is functional and distraction-free for users.  Whilst images are of course important to provide context and understanding to a user, they are limited to the gallery (images of the Park and the projects) and corporate logos.


## Features

### Responsive

* Site is suitable for mobile through desktop displays.
* Navbar is responsive to the display size.  Whilst a bootstrap navbar could have been implemented for both, I wanted to have the flexibility to implement different features on the Navbar on larger displays.
* Gallery is responsive to display size.  
  * On large screens, the gallery supports a solid background in the container to balance the size of the images with the content above.  The images are close in size to a single column width above, and the addition of the background provides a transition between the 2 columns above / full page width and the image.  To utilise the space, the Prev and Next icons were pushed left and right respectively, and enlarged.  

    ![Gallery on large screens](/README-attachments/gallery-large.png)

  *  On smaller screen, the carousel reverts without a background, and now relates to the single column width of the content above.

        ![Gallery on large screens](/README-attachments/gallery-small.png)

### Interactive Elements

* Dropdown images of projects over Navbar items on medium screens
* Timelines open in Bootrap modals
* Scrollable gallery in Bootstrap carousel
* Map of the project location appears on 'click' by use of Bootstrap collapse


### Existing Features  

#### The Pages

1. **Overview Page**  
Purpose of this page is to provide an overview and comparison of the projects at Wembley Park.

2. **Project Page**  
Included one for each project.  Purpose of these page is to provide further detail and provide specific project images.

#### Key Features of Pages

1. **Navigation Bar**

    On large screens, an image of the Project appears when the cursor hovers over the link:-
    ![Navbar hover](/README-attachments/Navbar.gif)  
    As the project name may change over the lifetime of a project, some users who may not be aware of changes can easily identify the project from the image.

2. **Overview / Project Overview**

    These sections will provide the opportunity to give an overview of the Park and the Projects.  The content type may vary.  For the purposes of this project, I have written fictional text.

3. **Timeline**
    * On the overview, this project compares the project construction timelines.
    * On the Project pages, this provides additional timelines for the planning and design timelines. 
    * Durations were modified from default to Quarters, which is commonly used for measuring time in construction.  
    * Hovering over the bar provides the detailed date information and duration for ease of reference in the Tooltip.
    ![Timeline Snip](/README-attachments/Timeline.png "Timeline")  

4. **Benchmark Comparison / Cost Breakdown**
    * The Overview page has a bar chart that compares the construciton costs on a £/sqft basis of each Project, and the average.  
    ![Bar Chart](/README-attachments/barchart.JPG "Bar Chart")
    * The pie chart on the Projects' pages show a breakdown of that cost into an elemental format.
    ![Pie Chart](/README-attachments/piechart.JPG "Pie Chart")

5. **Dashboard** (Overview page only)

    The Dashboard shows key metrics from across the Park which relates to progress of the development.  

6. **Gallery** (Project pages only)

    The gallery shows a selection of images of each building on the Projects of the website.

7. **Footer**

   The footer contains:-

   * Project Map - a map showing the locations of the Projects will drop down below the footer when activated.  
    ![Project Map Dropdown](/README-attachments/map-dropdown.gif "Project Map Dropdown")
   * Corporate website links - links to the Quintain website and Wembley Park websites are included in the footer.  The logos enlarge when the cursor hovers over:-  
   <img src="/README-attachments/footerWP.gif" height="40" width="40" alt="Wembley Park logo footer GIF">
   <img src="/README-attachments/footerQ.gif" height="40" width="40" alt="Quintain logo footer GIF">


### Features to Implement in the Future

* Nr of Projects - add more projects to the website.
* Addiitonal project information - rather than make the page longer, add further carousels to the two columns so that a user can rotate through.  Aspects may include:-
  * Within the Overview: Building Areas, Apt numbers, tenure types;
  * within the Cost Breakdown: Total Cost, Cost per Apt.
* Link data to a database, so that they can be updated more easily.


## Technologies Used

### Languages Used

* [HTML5](https://en.wikipedia.org/wiki/HTML5)
* [CSS](https://en.wikipedia.org/wiki/Cascading_Style_Sheets) 

### Frameworks, Libraries and Programmes Used 

* [Bootstrap 4](https://getbootstrap.com/)  
Bootstrap was generally used to assist with the responsiveness and styling of the website.  Components which were utilised were:-
  * [Buttons](https://getbootstrap.com/docs/4.5/components/buttons/)
  * [Carousel](https://getbootstrap.com/docs/4.5/components/carousel/)
  * [Collapse](https://getbootstrap.com/docs/4.5/components/collapse/)
  * [Dropdowns](https://getbootstrap.com/docs/4.0/components/dropdowns/)
  * [Modal](https://getbootstrap.com/docs/4.5/components/modal/) 

* [Google fonts](https://fonts.google.com/)  
Google fonts were used to import the 'Monserrat' font into the style.css file which is used on all pages throughout the project.

* [Google Charts](https://developers.google.com/chart/)  
Google Charts was used for displaying data in graphical format, including [timelines](https://developers.google.com/chart/interactive/docs/gallery/timeline), [bar charts](https://developers.google.com/chart/interactive/docs/gallery/barchart) and [pie charts](https://developers.google.com/chart/interactive/docs/gallery/piechart).

* [Google Maps Javascript API](https://developers.google.com/maps/documentation/javascript/overview) including [Styling Wizard](https://mapstyle.withgoogle.com/)  
Google Maps was used in the footer to provide locations for the Projects.  Functionaly of the maps was limited in terms of zoom, map type and points of interest to maintain a simple viewport of the Park and Project locations only.  

* [Popper.js](https://popper.js.org/)  
Popper.js came with Bootstrap to make the popovers operation responsive.

* [jQuery](https://jquery.com/)  
jQuery came with Bootstrap to make some of the components operate in JavaScript.

* [Git](https://git-scm.com/)  
Git was used for version control by utilizing the Gitpod terminal to commit to Git and Push to GitHub.

* [GitHub](https://github.com/)  
GitHub is used to store the projects code after being pushed from Git.

* [Pixlr](https://pixlr.com/)  
Pixlr was used to resize images and editing photos for the website.

* [Figma](https://www.figma.com/)  
Figma was used to create the wireframes during the design process.

* [Paletton](https://paletton.com/)  
Paletton was used to create a pallette of colours that supported the main colour of the website, which is based on one of the company logos.

* [Kapwing](https://www.kapwing.com/)
Kapwing used for editing videos and creating GIFs used in this README file.

* [Screen Recorder](https://chrome.google.com/webstore/detail/screen-recorder/hniebljpgcogalllopnjokppmgbhaden)  
Screen Recorder used for creating videos (edited in Kapwing) of website features in operation.


## Testing

### User Story Feedback and Testing

Responding to the User Story, I believe this website has started to address the conclusions outlined.  Taking each point in turn:-

 **Item** | **Objective** | **Result**
---------|----------------|---------------
1 | Provide a website so clients can access past and present cost data | A *breakdown* of project costs is provided on each 'Project' page. A timeline is also included on each page so that users may check the period of construction
2 | Include an Overview page that compares projects against one another | The landing page is an Overview page. This compares the *total* cost and timeline data at a higher level than the Project pages show.  This allows the client to see the range and average costs at a glance.
3 | Collate diverse pieces of information to centralise and standardise data | Whilst cost data is the primary information, this is supplemented by programme (timeline) data and a Gallery.  This provides context for the client, who may not have been directly involved in the project.  Whilst the data compilation of this data seems logical, it is not often done by the QS.
4 | Provide information in a clear and consistent format | The format of each Project page is the same, so users can become acquainted and familiar with the style, making it very user friendly. The Overview page varies slightly, but still resembles the Project pages.  The presentation is clean and simple, so users can focus on the information.
5 | Primary means to store data by QSs | By exposing clients to the website, there will be an implicit requirement by QSs to utilise the website to store the data.  It will become a requirement as the user base grows.

In summary, the website should be a useful tool for both the QS to store and maintain key information, as well as for clients who reqularly request this kind of information.  Not only will the information be available on demand, but the information should be more readily understood and seen in a consistent, highly professional format.

### Validators

The W3C Markup Validator and W3C CSS Validator Services were used to validate every page of the project to ensure there were no syntax errors in the project.

* [W3C Markup Validator](https://validator.w3.org/)

    Results:-
    * [Overview](https://validator.w3.org/nu/?doc=https%3A%2F%2Fdkeddie.github.io%2Fproject-one-v2%2Findex.html)
    * [Project 1](https://validator.w3.org/nu/?doc=https%3A%2F%2Fdkeddie.github.io%2Fproject-one-v2%2Fproject1.html)
    * [Project 2](https://validator.w3.org/nu/?doc=https%3A%2F%2Fdkeddie.github.io%2Fproject-one-v2%2Fproject2.html)
    * [Project 3](https://validator.w3.org/nu/?doc=https%3A%2F%2Fdkeddie.github.io%2Fproject-one-v2%2Fproject3.html)

There are 3 warnings common to all the pages which are highlighted from the validation.  These relate to the scripts used to import the Google Charts functionality into the website.  As the code has been copied from Google Charts, and not amended by myself, I have not attempted to rectify the issues flagged by the validation service, as they may alter the functionality of the scripts.

* [W3C CSS Validator](https://jigsaw.w3.org/css-validator/) - [Results](https://jigsaw.w3.org/css-validator/validator?uri=https%3A%2F%2Fdkeddie.github.io%2Fproject-one-v2%2Fassets%2Fcss%2Fstyle.css&profile=css3svg&usermedium=all&warning=1&vextwarning=&lang=en)

There are no errors found on the validation service.

### Manual Testing of the Site

The following tests were carried out to ensure functionality before deployment:-

**Test**: Check that website links are functioning (Nav bar)  
* Steps followed:  
  * Clicked first link (Overview) in the Navbar;
  * Checked correct destination/page loads;
  * Pressed 'Back' to return to page under test;
  * Proceeded to next link and followed above steps until all links tested.
  * Proceeded to next page and followed the above steps until all pages tested.
* Results:  All links were functioning.

**Test**: Check that the Timeline button and pop-up are functioning  
* Steps followed:  
  * Timeline button pressed twice on each page in turn;
  * On first press, 'X' to close pop-up pressed to ensure functioning to close the pop-up.
  * On second press, mouse click outside of pop-up pressed to ensure pop-up closes.
* Results:  Timeline button and pop-ups are all functioning.

**Test**: Check that the Gallery carousel cycles through images in a consistent format  
* Steps followed:  
  * Cycled through images on each Project page in both directions.
  * This was carried out on each Project page.
* Results:  Some images were different sizes.
* Fix: Image sizes were checked.  Those that were not 1280 x 720 were re-sized and re-uploaded.

**Test**: Check that Footer Map and Links work as expected 
* Steps followed:  
  * Clicked the 'Project Map' button to show map, and then clicked again to ensure that it hides;
  * Checked that website link images enlarge when they are hovered over;
  * Both website links clicked to confirm correct websites are loaded in a new window.
  * The above steps were repeated for each page in turn.
* Results:  Footer map and links function as expected.

### Further Testing

During the development of the website, and again as a final, comprehensive and in-depth review, the following testing was carried out:-

* The Website was tested on Google Chrome, Internet Explorer, Microsoft Edge and Safari browsers.
* The website was viewed on a variety of devices: Desktop, Laptop, iPhone 8 & iPhoneX.
* Buttons were checked to ensure when hovered or active that they are responsive and operate uniformly.


### Known Bugs

The following issues were identified during development of the site:-

* On the timeline, the dates are a mixture of regular and bold text.  It does not appear possible to format this axis on this particular chart type.
* The Chart size does not respond on page re-sizing without re-freshing.  This is a known limitation of Google Charts.
* The pie chart does not show the Total, only a breakdown of the values.  This is also a limitation of the particular Google Chart type.


## Deployment

The website has been deployed on GitHub and is currently publicly accessible. 

The development of the website has been undertaken on Gitpod.

The steps from start to present were:-

1. Creation of repository on GitHub, utilising Code Institute template.

2. Launch of repository on Gitpod.

3. Utilise Git to push content back to GitHub.  This was undertaken at regular intervals throughout the development of the website.

4. Deployment of the webpage was implemented by
    * Going to the 'Settings' of the repository,
    * Scrolling to 'GitHub Pages' section,
    * Selecting 'master branch' of the Source dropdown menu
        
The website is now deployed and can be viewed at:
    [https://dkeddie.github.io/project-one-v2/](https://dkeddie.github.io/project-one-v2/index.html)

## Deployment of a Clone

Should you wish to deploy your own version of the website, the following steps may be followed to host your own version on GitHub:-

1. Visit my GitHub Repository: [project-one-v2](https://github.com/dkeddie/project-one-v2)

2. Click dropdown 'Code' and copy url to 'Clone with HTTPS'  
![Clone](README-attachments/clone.png)

3. Select 'Import Repository' from the Menu dropdown, paste the url, give your new repository a name and click 'Begin Import'
![Clone instructions](README-attachments/clone2.png)

4. Go to your new Repository.  You may chose to launch the repository in an IDE of your chosing in order to make changes to the website, and customise it to your requirements.

5. To deploy the website, follow step 4 of the **Deployment** section immediately above.


## Credits

### Content

All content was written by the developer.

### Media

All Images are the ownership of Quintain, my employer.

### Acknowledgements

Thank yous to:-

*  My mentor for feedback and advice given throughout the project.

*  Fellow Code Institute students who gave feedback as part of Peer Review:-
    * Liga
    * Simon Vardy