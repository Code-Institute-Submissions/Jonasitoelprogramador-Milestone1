#Journeyman Tapenade

  Journeyman Tapenade is a brand that specialises uniquely in high-quality tapenade (olive paste) for gross consumption.
The idea behind the creation of this brand and website is that tapenade is an incredibly tasty product, however, relatively 
few people know of it/eat it regularly.  A gap in the market methinks (a "tap gap" as I like to call it)!  Journeyman aims to 
bridge the tap gap both by increasing awareness of tapenade, and by producing a line of tapenade products.  

##UX

Given this context, 
the aim of this website is threefold:

1.  Educate the masses about tapenade - what it is and how it came about.
2.  Showcase and promote the upcoming line of tapenade related products.
3.  Explain how Journeyman the brand was conceived and provide people with the possibility of getting in touch.

This website targets food-enthusiasts, amateur/professional cooks and travel-oriented people.  People who are always on the look-out
for a new ingredient to spice up their cooking or who are adventurous when it comes to food and enjoy seeking out different flavours. 
The website helps this cross-section of people by informing users about tapenade (what it is, where it comes from, 
the different types) and by showcasing and promoting the upcoming line of tapenade products (as well as perhaps to suggest a few recipes 
involving tapenade!).  

###User Stories

####First-time-users
As a First Time Visitor, I want to have a positive emotional response when visiting the site (be impressed with the quality of the website) to that I am encourgaed to return.
As a First Time Visitor, I want to be able to move through the website in order to access the site's content.
As a First Time Visitor, I want to be able to understand the basics of the brand and the products that are being promoted.

####Returning-users
As a Returning Visitor, I want to be able to contact the bussiness and be able to find their social meadia links.
As a Returning Visitor, I want to be able to access the website on various different screen sizes and for it to evoke a positive response.

An example of a user visiting the site for the first time could be someone who arrives on he landing page, reads the blurb about what tapenade is,
looks through the product list and send Journeyman a message asking when the products will be availiable. 

###Design

####Colour Scheme
There are three main colours: white, olive green and dark purple.  The latter two are the same as the colours of the hero image on the index page
thus producing an olive influenced colour harmony.

####Typography
The main font used in the site is "Noto Serif KR".  After experimenting with various fonts I found that this one had the right balance of 
being both classical and understated.  I added the backup font "serif" which will return the operating system's fallback serif font in case of the
primary font not loading.

####Imagery
The website makes use of lots of olive-related imagery as olives and olive trees/branches are more aesthetically appealing than pictures of tapenade.
That said, there are images of jars of tapenade on the product info page as it is important to give a visual representation of the product being promoted.

###Wireframes
[Wireframes] (./wireframes/wireframes_journeyman.pdf)

##Features
  The site is compromised of 4 separate pages: "Home" page, "Product Info" page, "Videos" page and "About Us" page.  
  
  All three pages are responsive (computer, ipad, smartphone or anything in between!).  This responsive design is achieved through a combination of 
bootstrap columns which alter their widths as viewport size changes and media queries at different intervals.  This allows users to access the site 
on all devices and ensures that they will have a positive emotional reaction when they do so.  

  Each page has a header that contains the navigation links for navigation within the site.  This allows users to navigate quickly and easily through
the application.  In addition, there is footer on each page that contains contact info as well as links to social media that open in a new tab.  The 
latter ensures that users are able to see public opinions about the brand without forgetting where they were directed from.


The index/home page contains a hero image and two responsive bootstrap rows, the first of which explains what tapenade is and the second contains 
a quote.  The hero image is designed to entice the user further into the site by soliciting in them a positive opinion from the outset the bootstrap rows
encourage the user to educate themselves about tapenade and thus understand the aim and content of the website as a whole.


The Product Info page is split into 9 bootstrap rows which are grouped into 3s where each group relates to a Journeyman Tapenade product.  Each group 
contains a row for the title of the product, a row for an image of the product and a row that contains text about the product.  This number of rows is 
employed in this page in order to allow for maximum responsiveness in on the page.  This allows for the products to be preseneted in the best possible
light across all device sizes. 


The "About Us" page is comprised of a bootstrap row split into three bootstrap columns containing an image, text and a form respectively.  The form clearly
allows the user to contact Journeyman Tapenade quickly and easily without having to leave the site.  The placement of the "Our Story" section next to the 
form gives the user more information as to the nature of the company that they are contacting.

##Technologies

###Languages 
HTML5 was used in order to provide the text content the structure of the site.
CSS3 was used to add styling.

##Frameworks, Libraries and Programs

Bootstrap: was used to add responsivess and to aid with the structure of the site. (link: https://getbootstrap.com/docs/4.4/getting-started/introduction/)
Hover.CSS3: was used on the nav links in the header and the social media links in the footer in order that they take on the olive green colour in the colour scheme. 
when hovered over. (link: https://ianlunn.github.io/Hover/)
Google Fonts: was used in order to import the font that is used across the website ('Noto Serif KR'). (link: https://fonts.google.com/)
Font Awesome: was used in order to add icons to the nav-bar in the header as well as the social media icons in the footer. (link: https://fontawesome.com/)
Git: was used to save changes in the website's files.  Gitpod terminal was used to save changes to Git and Push to send these changes to GitHub. (link: https://git-scm.com/)
GitHub: where the files are stored after being "pushed". (link: https://github.com/)
Canva: was used to edit some of the photos on the site  (link: https://www.canva.com/photo-editor/)
Balsamiq: was used to create wireframes of the website to serve as a reference point when coding. (link: https://balsamiq.com/)
Shutterstock: was used to source some of the images for the site. (link: https://www.shutterstock.com/)
Unsplash: was used to source some of the images for the site. (link: https://unsplash.com/)

##Testing

###Manual Testing

1. As a First Time Visitor, I want to have a positive emotional response when visiting the site (be impressed with the quality of the website) to that I am encouraged to return.
    1. The landing page has a hero image designed to attract the user's attention and to give the impression of quality.
    2.  The website follows a strict colour schemata designed to give the impression of control and attention to detail.
    3.  The website combines humour and a light-hearted tone e.g. in the "quote" section on the home page and the "fact file" section on the product info page.  The aim of this is 
    to entertain users as well as to educate them about Tapenade adding to their positive experience.  

2. As a First Time Visitor, I want to be able to move through the website in order to access the site's content.
    1. There is a clear and intuitive navigation bar that provides clear links to the 3 pages of the site.
    2. The links change colour when hovered over in order to assure the user that the links work and that they are fully responsive.
    3. The nav-bar occurs across all three pages of the website so as to always give the user the option of navigating to another page. 

3. As a First Time Visitor, I want to be able to understand the basics of the brand and the products that are being promoted.
    1. The landing page of the site has a lot of imagery which ties into the overall theme of the brand (olives and tapenade) and there is an explanation of tapenade (the main product)
    below the hero image.  The top of this section is visible in order to show the fitst-time user that there is more content on the page.
    2. There is a clearly labelled "about us" page which contains text detailing the history and aim of the brand.
    3. There is also a clearly labelled "product info" page which showcases the 3 products with images and text description.  


1. As a Returning Visitor, I want to be able to contact the business and be able to find their social meadia links.
    1.  In the footer, which exists across all three pages, there is a phone number and email address of the business so that users are able to find the information to contact the
    company whichever page they are on.
    2.  The footer also features social media links which are in the format of icons in other make them more eye-catching and also change colour when hovered over in the same way
    as the nav-bar links. 
    3. Furthermore, there is a "Contact Us" section of the "About Us" page which allows the user to contact the company without having to leave the site.
2. As a Returning Visitor, I want to be able to access the website on various different screen sizes and for it still to evoke a positive response.
    1. By implementing a combination of bootstrap responsive design and media queries at varying viewport widths, the website is fully responsive with regards to the viewport 
    size of the device that it is being viewed on.  
    2. Thus, the site will be aesthetically pleasing to the user on matter the viewport size.

###Automated Testing

  The HTML and the CSS code were put through the W3C schools HTML and CSS validators respectively to eliminated any potential syntax errors. 