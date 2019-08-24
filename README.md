# Project 0

This project represents the first instance of what will evolve into a fully fledged web application.
Currently the project has five static html pages. But over time it will grow into a proper web application using python, javascript, flask and other technologies where users can interact with the website in order to book lessons from music teacher Stuart Andrew. Additionally they will be able to see a list of performances that Stuart will be involved in.
As the first instance, this project is closer to a 'mock up' of what's to come.


Files includes:

*Common Header*: 
Each file contains bootstrap 4 (downloaded version) and it's dependencies

*Common Body*: 
Each file body section contains a bootstrap navbar, and Jquery scripts required to operate navbar toggle features

index.html: 
This is the main landing page for the site. It includes the common navbar, and uses the bootstrap grid and columns to display piano images

stuart.html: 
This page represents a simple page about Stuart, it will grow to include a full biography of his career
It includes the common navbar, and uses the bootstrap grid and columns to display imgaes of Stuart performing.

services.html: 
This page lists the services (mainly teaching) that Stuart offers.
It includes the common navbar, and uses the bootstrap grid and columns to display piano images.
Currently it uses a simple table to group services with their descriptions

lessons.html: 
This page is intended to give current and future students the ability to book a lesson with Stuart
Currently it uses an html form styled with bootstrap classes to expose a form to capture student details.
Over time this will be connected to a back-end database to actually capture real lesson requests.

shows.html: 
This page is intended to display Stuart's upcoming performances.
This page includes a list that is currently empty, but will grow to be come populated with future performances.
It may evolved into more of a calendar format, and it ideally will reference other website APIs to compile a complete list.


styles.scss: 
This is the main stylesheet for the site

styles.css: 
This is the resultant stylesheet when styles.scss is compiled using the sass command

styles.css.map: 
This is generated when styles.scss is compiled, it maps between the original scss sheet and the output css sheet
