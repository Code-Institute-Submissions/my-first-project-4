## My First Project

# Motivation 


_I have created this for mini project where I had to build a site that has content
for its users, more than a few pages on the site, a form which allows users to sign up
with a required field making sure you cannot submit without entering details._



### Navigation Bar
_I chose to give my navigation jump links allowing the sections of my page to jump to another instead
of having my different pages and then linking them together. Also, by having my links jump I feel it gives my sites 
a clean and smooth transition as the user can scroll to see the whole site if they wish._

#### 1st Content 
_This the part where my the visitor of the site can see a full width image bringing thier attention to
what the page is really about. I chose to have h1 element along p element including a lead class to provide 
the company name within the picture. I feel this blends in nicely with the 1st content section._

#### 2nd Content 
_I chose to list this section as photojournalists just showing the visitor images and quotes from the
people involved in the photography, using bootstrap helped me give the images a rounded look 
by using "image-circle". The h2 class uses a "text-uppercase" to make my letters all capitals
Also, the hr element i have modified gives this section some style by underlining my header but also creates a 
column style for my pictures._

#### 3rd Content
_This section is labeled models as i want a section to showcase photography using people who are employed by the
company. I decided to use a carousel from bootstrap to give me this section that allows users to click images with responsive 
arrows and this was achieved by using a "carousel-control" class. The glyphicons in this section allowing users to click to move back 
or forward have been put inside a span class for them to be responsive._

#### 4th Content

_I chose to use this section just showing the visitor what we can do for them again using glyphicons
in a span class I changed the size of these using its font size and giving them a colour to make them stand out
.Also, like previous sections I have chosen to use hr elements to give my header an underline._

#### 5th Content

_This image just I feel stands out before the visitor reaches the contact form section. The coloring scheme from the image I feel works really
well with the overall theme of the site. I have use a div class "img-fluid contact-container" to give this image full width so it grabs attention of the visitor._


#### Contact Section

_This section allows the visitor to contact us by email and to leave a message as well. This section uses a simple "form action"
and underneath this you will find socials links that have been created using font awesomes graphics
and four links with an i class encloses the social media class._



## Credits

_As this is a project all the names and images have been used created and I do not 
take credit for any of the content. The content was just used as I created a modelling  
agency site for the purpose of a project._

## Backgrounds

_For this project I trialled a number of backgrounds but I decided to go with some animations using different 
colours that interchange as time elapses. I first used a "linear-gradient" which allowed the colours
to change over time, using css I made the animation transition smoothley (This you can find more in my technologies 
section.) Also, by using keyframes I change the background position to start with 
0% 50% then move to 100% 50% and finish with 0% 50%. This allowed me to have the transition
change created the colour effect that runs throughout page._




# Technologies

#### HTML

_This was used to create a structure for my website, what is more like building blocks to
my site which which will allow me later to style using css (see below)._

#### CSS

_I implimented the css style sheet which is more like a file that basically includes all my
styles that will take my site from being totally text base to one that includes different colours
images, fonts etc. The css used on here gave my page styling for my text that you see in the first image underneath
the navigation bar, the colour and sizes of buttons and also styling for all of my sections._

#### BOOTSTRAP

_This for me was one of the most effective technologies, maybe even the most important as it totally
allowed me to add a navigation bar that is responsive on mobile by using bootstrap own stylesheet, this allowed my sections
to have a full width by simply preceding my container class with the word "fluid". By adding the word "inverse" to
my navigation class it gave me a darker colour. My picture slideshow has been made easier by using "carousel slide carousel-fade"
which allowed to create the slideshow you see. Bootstrap was also great for my quotes 
section as it allowed me to have rounded images using "image-circle" and even the glyphicons
I have used throughout have been made possible because of bootstrap and they were applied   
simply by putting the command for each image by placing them in a span class._

#### ANIMATIONS

_This is what is allows me page to have coloured backgrounds that alternate over a period of time.
The backgrounds were made possible by using a name for the animation such as "gradient" which allows to
apply the animation css positioning which allows the backgrounds to change colour. Also, the animations 
have given my slideshow text an effect by using animation css stylesheet and using the command
for each style which proceeds the class "div class="animation"._

# TESTING

#### Navigation Buttons

_I had some issues with this at the start as my buttons did not appear as links first off. I played around 
to find out how I could make them jump. This was achieved by using a id as a span within my 
my h1 elements this allowed me to jump to different sections of my page by associating this with my links 
a href with an id that matches the one within my h1. I did have issues with this at first as my span 
classes were above my div but after working it out by watching videos on divs and parent-child
relationships credit goes ""._

#### 1st Contact Section

_This was hard as for me as at first I could not work out why my image would not show this was down to 
an error in my file destination. I decided to change this as adding ../ before the my images folder 
this allowed the image to be located allowing it to appear within my callout container. Using css I 
applied the picture using background (url) along with display: flex which allowed it become much
more responsive._

#### Contact Us Section
_I did find this extremely difficulty at first as when I pressed the submit button the my input sections would not 
show an error. This resolved by just going back to the videos I have watched in the module section and remembered that  
I had to apply the word required before closing my tag. This proved to be succesful as now my sections show error  
"please fill in this field".



