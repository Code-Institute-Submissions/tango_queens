## Tango Queens Website

Tango Queens is a networking group that was started by a long-time friend of mine, Monika Jurkiewics who as a tango lover found that there was a lot of unspoken politics in tango which she personally found difficult to deal with when she joined the very insular community. After having some fairly bad experiences she created a networking group on Facebook and the concept gained in popularity such that they ran an in-person event earlier this year (2020). 

She created an initial website using a Wordpress template, however still basic, inelegant and lacking in functionality. It was important to me when choosing the topic of this project that there is potential for the site to be used so that when I add it to my portfolio, that my potential future employers will be able to see a live website that is functional and currently in use. Additionally, I wanted to create a project where I could potentially add more complex features once I have learnt them and use this as an ongoing opportunity to practice my development skills. 


## The UX process
As this is a niche website, the majority of site users are ones that would be directed to the site from the community activities, rather than through search therefore it was important that the site focus on content and experience that is appropriate for the members.

The primary user of this site would be a tango dancer who is part of the international tango scene. This group of people (specifically in Europe) travel around the world monthly, bi-monthly to attend tango marathons called milongas.

The user stories are as follows:
* The user can find out information about Tango Queens
* The user is able to identify who the managing members of the Tango Queens community
* The user can connect to the social pages for the group as well as email them directly
* The user is able to see upcoming events and register for these
* The user is able to see pictures from past events

The basic design of the website and overall aesthetic follows the existing Tango Queens website here: https://www.tangoqueens.com/. 


## Features

### Existing Features
**Feature 1:** The user can come to the site to find a welcome note from the founder of Tango Queens (on index.html).

**Feature 2:** The user can navigate to the groups Facebook and Instagram pages as well as emailing to open an email link to the group (all pages).

**Feature 3:** The user can find the background information of the concept behind Tango Queens (on concept.html).

**Feature 4:** The user can find information on the founder of Tango Queens (on concept.html).)

**Feature 5:** The user can find information on upcoming events and navigate directly to the registration page for that event. (on events.html).

**Feature 6:** The user can see an automated carousel of images from previous events (on events.html).

**Feature 7:** The user can navigate from index.html to Features 4 & 6 directly through navigation cards. 

**Feature 8:** The user can navigate around the site using the nav bar at the top of each page. 

### Features Left to Implement

The design of this site is intended to be scalable in the long term as there are additional features that would make this ideal for the site owners. These are beyond the scope of the current project.

These could include:
* A registration process that links to a database
* An event registration page
* Integration with a live video player so that they can deliver their video content directly on the site
* A members only portal with access to online resources
* Payment gateway integration so that they can charge for their membership directly on the site


## Technologies Used
### HTML
HTML5 has been used as the markup language of the site.
### CSS
CSS3 has been used to style the HTML elements on this site.  

### Bootstrap
Bootstrap has been used as the CSS framework for this site. It was particularly useful as a means to ensure that the site was responsive from the outset in the design/development phase. A number of elements have been taken directly from the Bootstrap framework including the headers, the jumbotron, the cards, the toggler button and image carousel. 

Using bootstrap has also allowed me to incorporate two JQuery elements despite not having learned this framework yet. 

### Javascript 
In the introduction modules of the course, there was an overview instruction on how to incorporate javascript in front end development and it seemed appropriate to use Javascript for two of the elements in site - the toggle button in the header and the image carousel. Although this was technically beyond the scope of the website, using bootstrap to implement these features was simple enough and seemed appropriate. A static page of tiled images seemed a bit lack lustre and one of the tutorials already demonstrated how to incorporate the hamburger button. 

In regards to these two elements, it is commented in the code however to emphasise that these elements were taken directly from Bootstrap, including the class names and ID's for the sake of functionality. 

The carousel code used is here: https://getbootstrap.com/docs/4.0/components/carousel/

The toggle button used is here: https://getbootstrap.com/docs/4.0/components/navbar/#toggler 

### Font Awesome 
Font Awesome was used for the social media icons found in the footer.

### Google Fonts
Roboto, a Google Font was used as the base font for the site. 

Links to all of these sources can be found in the header of the site. 


## Testing
Through the development of the site, there has been ongoing testing. 

All links have been tested to ensure that they work and open on blank pages where appropriate including:
* Social links in the footer
* Internal links in the nav bar 
* Internal links in the cards at the bottom of index.html 
* Register button in the event card on events.html 

Additionally, extensive testing has been done across mobile resolutions this has included:
* Manually manipulating screen size in order to see where resolution bugs arise
* Changing the margins and padding to use % instead of pixels to ensure that the width of certain elements is easy to read across different resolutions
* Removing certain images on smaller resolution mobile to make site more legible
* Adding the JS nav bar toggle button to keep navigation simple when on mobile resolution



## Deployment
This project has been pushed to Github, the link to which is here: https://github.com/kberanoyd/tango_queens. 

I have used this project as an opportunity to learn/test best practice with regards to github version control and have tried different methods of doing so, including add/committing only pages to add/committing the whole project repeatedly. Towards the end of the project this is what I tended to need to do increasingly as I was changing things across all of the pages often. 

This is now deployed on gitpages. 

## Credits

### Content, Media and Inspiration
The content for the entire site was obtained directly from and with the permission of the founder of the Tango Queens community, Monika Jurkiewics. All photographs, content and links were used with her permission. As a close friend, I am very invested in her message of empowerment which she provides for this community through this site and wanted to give her something that she can use in furtherance of this message. 

I tried as much as possible to stick to the aesthetic that she had created in her initial website, however making this more professional looking. 


python3 -m http.server