# The title for this project is:"Body Fashion gym" that is the name of a new opening gym.
(The gym is just an imaginary gym opening soon in south east London)
The live Url of this project is https://iacopo454.github.io/Milestone/ it is a responsive website for all devices from extra small to large screens and it has been made using HTML, CSS "cascading styles sheet" and Bootstrap.

# I have personally tested my code using the "Google Chrome Dev tool" for all the screen sizes, also the Url works fine and has been tested on different Browsers such as Google Chrome, Mozzilla Fiefox and Safari.
I have also tested the website from my mobile an Apple Highphone 8 and all is working fine.
The project is deployed on Git-Hub platform where is possible to access to all the relatives files: "https://github.com/Iacopo454/Milestone".
In the next future I plan to add some extra content to the website, new promotions, probably for students in away to attract more new members to join, I also plan to create a photo gallery where to advertise some gym gadgets and products to be on sale online.
I also plan to add a google map to the project in away to make it easier for the users to check where exactly the gym is and in how far they are from their location.Another feature that I might add is an online training plan to watch   and an online booking calendar for some classes activites such as fitness, spinning or yoga, to give a better experience to the users enabling them to use the site also after that they have joined the Gym.

# The purpose of this project is to promote a new Gym opening soon in south east London in away to have a certain amount of memebers alredy to join in a short time from the opening day.
The website shows to the users some photos of the personal trainers team and   of the gym, provides a description of the gym, from the equipment available to a proper introdution of the staff-members working in the Gym. The introcuction of the staff is on meet.html and consist of an indiviual photo for each trainer  with a relative description including their skills. The personal trainers skills area cover, corrective exercise, fitness, recovery from injuries,advanced resistant training, fat loss, nutrition and diet, use of free weight, building mass programs, cardio and body buildings.

The website also expalin in a dedicated page "Learn-more" the phylosophy used to motivate the new members to achieve their goals through two Youtube videos and the relevant text. The Pricing.html  informs the users of the monthly cost or of different subscription available rather than just the gym membership, as it offers also the opportunity to practice boxing.

The Rules.html expalain in details what the users how professional and well organized is the gym to guarantee to their members a friendly and nice environment.  


## Structure  and Sources

# The index.html file is the homepage and welcome the users with a slide Carousel of Images (the code is taken from Bootstrap and then adjusted to add more images to it), the images used are showing some Gym trainers, and a mocking image of a dog in training 

-All the webpages display a Bootstrap Navbar that give the user the opportunity to navigate easily to any page: Home, Learn-more.html, Meet the staff, Pricing, The Gym rules, and the Sign Up form. 

Homepage: "index.html" 
- Introduce the users to the gym providing informations such as: "Why is different from other gyms", what is the equipment available from the functional training equipment to the cardio area, what are the facilities, including the car park and the expert personal training in place, and inform that the Gym is a "charitable trust based"in Lewisham. A separate image with famous Arnold Scwharzneger and some mochking text created using Jumbotron from Bootstrap.
The Arnold Scwharzneger Image is hidden on small devices as the image ratio it was not displaying nicely and so I have decide to do so, also the Jumbotron has a "Learn more" button which links the user to a separate page where is possible to read more informations related to the Gym project and watch two Youtube motivational videos, one external to the gym and one internal.

# The text in the index.html regarding the Gym informations and the introduciton is taken entirely from the website "ourgym.co.uk" 

# The text in the Rules.html is taken from the www.247fitness.co
# The text in Learn-more.html and meet.html is instead written by me.
# The content of the Tab  in the pricing.html is wirtten by me but the code for the tab is taken from the Bootstrap example.

 -Introduction to the gym
 
  Informations provided to the users: 
  - What they can expect from it 
  - What makes it different?
 - The Gym facilities
 - The training equipment
 - Cardio equipment
 - The importance to keep in shape 


Learn-more: "Learn-more.html"
- This page provides more informations on the Gym concepts and has an Iframe with two Youtube links, one motivational about training session in general, and the other one is about a personal trainer of the gym that introduce is method of training. 
The top of the page containt an Aler message that inform the user of a promotion that the gym is currently offering to the new members(this message is displayed also in the Pricing page as it might attract more members I thought that it is better to display it in more than in one page).
After creating the background image and the text that is entirely written by me, I have implemented an overlay using an Id and giving to it a dark grey overlay to make the text more readable and the colours of the page more in contrast for a better view experience.

The background image "sereno.jpg" is taken from Yahoo search engine as for all the other images. 

#The Iframe video is taken from Youtube, the first video source called "motivational" is of Valrocky "Train like a champion" here the link: https://www.youtube.com/watch?v=0UEUjQ546_g&t=8s
#The second video is taken from Youtube too and the source is Criticalbench "Personal Training Workouts - Beginner to Advanced Training" here the link: https://www.youtube.com/watch?v=2U7hY_523eQ.

Pn: "My intention initially was to link a Facebook page and Youtube but apparently after checking an error in the console "X-frames-Options to deny" and searching on Google the error, I find out on stackoverflow.com that it is not possible to add a facebook page because Facebook does not allowed it and block it", perhaps it might be possible to do it with some other code configuration to go around it.
At the end I have linked two youtube videos instead to the same Iframe.


 

Meet the staff "Meet.html"
- This page has been written by me and consist in a description including a short biography of the personal trainer working in the Gym. 
The page contains 6 Images and before each one there is a paragraph introduction, the first one is about the whole team "considerate a Family" as concept of the gym and then as mention earlier, each Personal Trainer  working in the gym with a small biography of their lifes and skills.This gives the user the opportunity to get to know more about the Staff working there even before joining the Gym.
- All the webpage Footers contains Social links such as: Facebook, Instragram, Twitter, Youtube, Linkdin and Pinterest, but the icon are linked only to the official website as the the Gym it is not real and so does not have a real page on those socials. The Footer also contains the full address of the gym and contact e-mail, also those details are not real. 

The Pricing "pricing.html" has been taken from the Bootstrap example documentation, then I have implemented the necessary changes to it such as the card property from Bootstrap to make it look more appealing.
The top of the page display an Aler blue message that inform the users of a current promotion available for the new members, I have created this using the bootstrap alarm property. 
This page give the users all the informations relevant the memberships available in the Gym or the current promotions going on.
- The page displays also a Sign Up button to open the Sign-in form, the same form that is availble from the Collapse Menu button on the navbar in all the pages, this to make sure that in the case the user decide to join the membership he has the Sign Up form always available every page.


The Gym rules "Rules.html" 
- On this page the user can read all the Gym rules and find out what is not allowed to do inside the premises and relevant informations such as: 
an invitation to Read carefully the rules, the main reason to provide these informations is to "guarantee a nice environment" to all the members, a summary of things that are not recommended to do and not allowed at all, also provide informations on how to dress for the Gym, and some important reminder such as "report issues quickly", and to do not leave items in the lockers when finsihed and out of the premises.

- I used two images below the Navbar to introduce the page on large and extra large screen devices, instead on all other screen sizes the page displays with only one image as I have hidden the small one for better visualization.
The image that overlap is blonde-jpg.jpg on the other one called palestra.jpg, I created this effect using two different position for the two images, one relative (for the palestra.jpg) and the other one absolute(for blonde-jpg.jpg). 

## Images 
The Image source for all the images is Yahoo search engine.
Here below all the images file name of the project:
(Arnold.jpg, blonde-jpg.jpg, dog.jpg, Gym-100.jpg, Martin.jpg, Laura.jpg, Michael.jpg, Richard.jpg, sereno.jpg, palestra.jpg, yahoo.jpg, maxresdefault.jpg).
The Carousel Images have been modified and replace after in the project to make sure that were fitting properly together in the carousel slide, the new measures are of 5760x3840 px as you can check in any other software preview "I used my Macbook to makes this changes". 


















