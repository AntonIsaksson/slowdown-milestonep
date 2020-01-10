SLOW DOWN RESORT

The project of my choosing is to make a website of the Resort "Slow Down" which is located at Koh Lanta in Thailand. The owners are looking to improve their branding and marketing and the first big step for them is to get a User Friendly and proffesional website. On the website you will get a good picture of what kind of resort Slow Down is, in the combination of pictures and text. You will be able to book a room, and follow links to Slow Downs social pages. 

UX

The main UX goal with the website, is to give the visitor a quick overlook to an “easy escape”. Let’s say that the viewer is a middle-aged man or women, 2-3 kids, sitting at home on yet another dark and rainy January day in Stockholm. They start looking around for a well needed break in a warmer climate. Once they reach Slow Down Resort they will hopefully get a quick overlook and an insight to a “easier” life and a quick escape. 
With as little information as possible, an easy-to-follow structure and simple navigation; there shouldn’t be too many steps between arriving at the website, and send a booking request.  

User Stories:

1.	As a visitor looking for appropriate accommodation in Thailand, I am looking for a quick overview of the resort, so I at a first glance can decide if this is a place to consider and find out more about.. 

2.	As a visitor who wants to book a room, I would like to fill out a booking request to see if the resort has anything available that would fit my specific needs. 

3.	As a visitor looking for a place to have dinner, I would like to contact the restaurant to see if they have any tables available for a specific date/time.                 

Strategy

I wanted to make a website that would capture the visitors attention at a first glance, and from there get the urge to dig deeper and read/discover on further.

Scope

A simple structure, easy overlook and a warm representing was the starting plan. Making it a one single scrolling page was something I decided to do early on.

Structure

To fulfill my goal for an easy overlook of the resort and what it represents, I decided that the first thing that meets the eye should be both beautiful and something that includes as much as possible from the resort. I finally found the picture to accomplish this which is the covering image on the landing page in the final project. 
Next, I wanted the visitor to see what types of accommodations Slow Down is offering.  After that, quiet naturally, comes the possibility to make a booking request. 

Skeleton

Wireframe: https://github.com/AntonIsaksson/slowdown-milestonep/blob/master/assets/wireframe/Wireframe-SlowDownResort.pdf

Surface

I wanted the surface to represent warmth. I had a lot of pictures from the resort to inspire to the color scheme which I decided would be some kind of “easy on the eye” blue combined with a nice beige color. 


Features

Existing Features

     -     Bootstrap ScrollSpy: when you scroll down the page and reach different sections, these will light up in the navbar. Vice-versa, when you click on any menu item you will be directed to that section. 
-	Smooth Scroll: to make things scoll more smoothly with the ScrollSpy function, some Javascript was needed. 
-	Image Slider: This is used both in the room page and the restaurant page, using Bootstraps Carousel class. 
-	Booking Form: let’s the visitor fill out and send a form to request a booking.

Features Left to Implement

In the future:
- I would like to add a page showing the activities that takes place on the resort. Perhaps by showing videos of when these activities (beach volleyball for example) is practiced. 
- I would like to evolve the booking system so that the visitor can check the availability right there on the website. 


Technologies Used

-	HTML
-	CSS
-	Bootstrap 4.1.0: https://getbootstrap.com/
-	Javascript (for smoothscroll and datepicker functions)
-	Font Awesome (for social icons): https://fontawesome.com/
-	Balsamiq (for wireframe): https://balsamiq.cloud/


Testing

The code and website have been tested through-out a number of different Browsers (Chrome, Firefox, Explorer) and on a number of different devices via Google Chromes Developer Tools, to check responsiveness (different mobile devices like Iphone & Samsung Galaxy, Ipad, etc.)

The fallout went as I had hoped following the planed UX and User Stories. 

User story 1; this was accomplished with the landing page image, which shows a big part of what the resort has to offer (pool, ocean-view, villas, beach volleyball courts, etc.)
User story 2; this was accomplished with the booking form.
User story 3; this was accomplished with the restaurant page, following the contact page with the phone number to the restaurant.

Testing the Booking Form: the attribute ‘required’ is added to the following input fields: ‘name’, ‘email adress’, ‘number of people’, ‘from date’ and ‘to date’. That means, if any of these fields are empty you will get an error message pointing out which field you have missed to fill in. 
If the email address field is filled in the wrong structure (xxx@xxx.xxx is the right way) you will get an error message as well. 
If all ‘required’ fields are filled in the right way, clicking the ‘Send Booking Request’ button will take you to the top of the page.

When clicking on the social icons in the ‘Contact’ page, a new tab will open because of the ‘ target=”_blank” ‘ attribute. 

Errors/Problems: One thing I struggled most with was the navbar-collapse class combined with the ScrollSpy function. When clicking the toggler-icon on smaller devices to collapse to show the menu items it works well. But then, when clicking on a menu item, the menu does not subtract back into the toggler-icon and is still visible. I tried different solutions which fixed this problem but made the navbar “jumpy” when clicking or scrolling. In the end, I decided that this was worse than having the menu-items show, so I let it be that way for now. 

Deployment

The website is hosted using Github pages

Credits

Acknowledgements

Inspiration and in particular the ‘ScrollSpy’ function was taken from this youtube tutorial: https://www.youtube.com/watch?v=V_lAhqLXT9A

Content

All written content is from myself.

Media

All pictures is taken by my colleagues and myself for the purpose to market Slow Down Resort. Some of them are used on Slow Down Resorts official web-page.  
