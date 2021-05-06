# Paws and Claws
## About
Paws and Claws is a domestic animal charity in South Wales, created for my msp1 for Code Institute. 
Unfortunately, many domestic animals are relinquished to shelters due to negligence, life changes and ignorance.
This has caused an undoubted strain on shelters who often rely on the general public to donate money or time to run their operations. Paws and Claws is designed to be appealing to the general public and provide them with enough information to decide whether they want to volunteer or donate to the charity.
Due to time or material constraints, many animal charities have out of date, unappealing websites that make it hard to find relevant information due to the sheer quantity of information provided.
While discussing the website design with potential users, it was apparent that it was important to them to know what exactly the charity does (what their aims are), what they have recently been working on, and find information about donating easily. This is why Paws and Claws will keep its design as simple as possible.
Recent research has shown that people are more likely to donate their time or money if the charity in question makes them ‘feel good’ about their decision.  Thus it is important to consider how the website makes the user feel, is it a positive experience for users. The website has room for the charity to expand; there is room to add more campaigns if necessary and additional features can be implemented if necessary, while keeping the most important features the same. 

## User Experience (UX)
### User Stories
Reasons a user might visit the website:
* A user that wishes to donate to the charity immediately. 
* A user that wishes to volunteer with the charity. 
* A user that wishes to find out more about what the charity does. 
* A user might wish to contact the charity for more information. 
* A user might want to know about previous success stories before relinquishing their pet/adopting from Paws and Claws. 

Reasons for the website: 
* Increase awareness of the charity. 
* Showcase previous successes. 
* Increase the amount of donations.
* Increase engagement in volunteer drives. 
* Provide a way for new and existing clients to contact them. 

## Scope
A user may expect:
* Easy to navigate website design.
* Visually appealing and well presented on all screen sizes.
* Well-functioning links and features. 
* Information about Paws and Claws. 
* Contact information. 

A user may want:
* Links to social media pages.
* Examples of previous campaigns.
* The ability to contact the charity online.
* Details of the charity’s location.

As a developer/business I expect:
* To provide information about Paws and Claws.
* To provide an easy way for new and existing clients to contact us.
* To display recent achievements.
* To provide an easy to navigate website with links that work as expected.
* To encourage visitors to donate.

## Structure
This website will consist of 
* A home page with ‘our aims’, ‘our successes’ and ‘our team’ sections.
* An about us page with a run down of the charities history/goals, a location section and a ‘how can you help?’ section. 
* A campaigns page which links to separate pages detailing individual success stories (e.g one dog who they successfully rehabilitated and is now happy in a new home). 
* A support us section which consists of the volunteer/contact us form and a link to paypal for donations. 

## Designs
### Surface
#### Colour 
The main colour for the website is a mid-toned dusky blue. This was chosen as blue is often associated with sincerity and reliability, which are attractive attributes for a charity. Yellow was picked as a contrast colour for call-to-action buttons and important information. This not only makes this information ‘pop’, but it creates a fun, appealing colour scheme that is easy on the eye. An off-white, blue-toned colour was used for the background to main text, which is in a dark blue colour. This is to reduce eye-strain and make sure the website is accessible to colour blind and dyslexic people. 

#### Typography 
Fredoka One and Raleway were imported from google fonts for use in this project. Fredoka One was chosen for its fun appearance and its heavy weight. It was used for titles throughout the project. Raleway was chosen for its readability, and as a sans-serif font, it avoids some of the issues associated with letters blending together for dyslexic readers. 
To further aid readability, I have increased the letter spacing in most instances. 
Call to Action
Call to actions have been designed to be as visible as possible. This includes using yellow as the main colour for buttons, and as a highlight colour when hovering over links in the top navbar. As the footer is a off-white, the social media links change instead to the mid-blue colour on hover so they remain legible. A light grey was used as the background colour for the navbar drop down menus, making it more visible on the mid-blue background.
Call to action buttons are placed at key locations on the website, after information that may make a reader want to volunteer/donate/enquire about adoption. The ‘volunteer’ section in the navbar and the ‘Contact Us’ buttons throughout the website lead to the contact us form. All call to action buttons are placed center, making them easy to find. I also used a subtle animation to make them grow on hover. 

#### Imagery
As this website was for a fictional animal charity, it was important to include many pictures to get users to empathize with the animals. All images were taken from pexels and unsplash. I picked images that were clear and generally uplifting in mood. I resized all images using tiny.png to improve load times, and some were cropped using resize pixel.  
Links to the original pictures are below:

[Marley Jumbo](https://unsplash.com/photos/BLW_KQ0Rkn0)

[Marley Image Bottom](https://unsplash.com/photos/tdmvrjF_14k)

[Home Page Hero Image](https://unsplash.com/photos/9gz3wfHr65U)

[Our Goals Image](https://unsplash.com/photos/Sg3XwuEpybU)

[Our Team Image](https://www.pexels.com/photo/ground-group-growth-hands-461049/)

[Felix Jumbo](https://www.pexels.com/photo/white-cat-with-pink-background-4587970/)

[Felix Image Bottom](https://www.pexels.com/photo/white-short-coated-dog-on-pink-and-white-floral-textile-4588443/)

[Form Background Image](https://www.pexels.com/photo/photo-of-white-and-brown-coated-dog-2820134/)

[Lassie Image Bottom](https://www.pexels.com/photo/brown-and-white-long-coated-dog-on-blue-surface-7516799/)

[Lassie Jumbo](https://www.pexels.com/photo/animal-dog-pet-cute-7516523/)

[About Page Hero Image](https://www.pexels.com/photo/brown-tabby-cat-lying-on-white-floor-5427090/)

I kept the design language similar through-out the website. Each page (apart from the contact us form) has a jumbotron with a background image at the top, followed by sections of text with left aligned titles.
There is a background colour set for all jumbo-images so that the text can still be read if the image fails to load. While all images are set as background images for responsivity, they have alt text as supplied by an aria-label. This fits with most recent accessibility guidelines as outlined here: https://www.davidmacd.com/blog/alternate-text-for-css-background-images.html. 

### Skeleton
#### Layout 
The principles of responsive design was intrinsic to the development of this webpage. Some content changes from a single stack to a row of columns when transitioning from mobile to larger screen sizes. This allows the user to see more of the website on a larger screen. Some unimportant content (such as the background image in the our goals section) disappears on smaller screen sizes. The max-width attribute prevents the website becoming stretched at very larger screen sizes. 
Bootstrap’s grid system was utilized for easy formatting. I also used jumbotrons to provide responsive hero images with text. Chrome dev tools was used to assess changes before altering my code.
Padding and margins were used to keep the text readable and to mark the separation of different sections. This is also responsively sized so that there isn’t excess ‘blank’ areas on smaller screen sizes. 

### Features
#### Universal Features
##### Logo and Navbar 
The logo and navbar is fixed at the top of the page. At lower screen sizes, it includes a navbar toggler on the right hand side, which then expands to show all of the main links on larger screens. The navbar contains two dropdown menus that contain five subsections. These have a lighter background to improve visibility. The navbar toggler has a yellow background to make it stand out. All main links change to yellow on hover. The navbar is mid-blue in colour so it stands out against the off-white colour of the background. 
Responsiveness
The page is scaled up and down for different screen resolutions. This has been achieved using media queries and Bootstraps’ responsive columns.
Accessibility
All images and nav elements have alt attributes or aria-labels. This includes non-important background images that do not add to the understanding of the website but may still be of interest to visually impaired users. Colours of text/backgrounds were chosen for their high contrast ratings, and where the contrast was not sufficiently high, additional background features were added to improve readability. Links are consistent when hovered over. All font sizes are supplied in rem so they resize appropriately when someone has their own settings for font size. 

##### Footer
The footer consists of the social media links and the contact info section. The social media icons were supplied by Font Awesome. They change from a dark blue to mid-blue on hover. They are appropriately sized to be easy to tap when using a mobile/touch screen device. The contact info section was intended for use by users who do not wish to fill out a contact us form for whatever reason. It includes an email address and phone number. It has a mid-blue border at the top to separate it from the rest of the off-white screen.

##### Meta data
Descriptions, author’s name, and keywords were included in the head element to increase traffic to the website. Each page  has a different label so that if a user has multiple tabs open, they can easily identify which tab is which.

#### Page Specific Features
##### Home
* Hero image with text requesting support and a donate button to encourage people to go straight to the donate page. 
* The ‘Our Goals’ section which outlines the major ethos behind the charity, advertises their services and is responsively sized, so on wider screens it consists of three columns (with central image), then decreases to two columns at medium sizes, then one column on small devices. 
* The ‘Our Team’ section which advertises the volunteering program and contains button linking to contact us form for more information on volunteering. Side image slides to the bottom on smaller screen sizes.
##### About 
* Hero image with text, in-keeping with the design language used elsewhere on the website.
* An about section which outlines the history of the charity, who runs it and what facilities they own. 
* A location section which provides textual directions to the facility and iframe map of the area so users can easily retrieve specific directions from their home. 
##### Success Stories Pages 
* All animal pages comprise of the same layout for a familiar feel and easy updating with new information/more pages in the future. 
* Hero image with text that fades in, allowing users to get more of a look at the animal in question. 
* A ‘past’ section which outlines what circumstances the animal comes from, what care it has received. 
* A ‘future’ section which either outlines where and when the animal was adopted, or its suitability for adoption. Contains a call to action button to get people to request information on the adoption process.
##### Support Us Pages
* The donate link goes immediately to paypal for users to choose exactly how much they wish to donate. This opens in another tab to not interrupt their browsing. 
* The contact us form is linked to from various sources on the website, so users with different intentions can find it. 
* Contact form consists of background image and a semi-opaque background for readability. 
* Form elements have a label as well as placeholder text. This is to ensure that screen readers pick up on the text. 
* Appropriately spaced items so they are easily tappable on touch-screen devices and they are easily distinguishable from other form items on the page. 
* A centered submit button which expands on hover. 
##### Future Features
* A Success Stories section on the home page, consisting of cards with background images of the animals which reveal a small amount of text on hover. 
* Gallery jumbotron on home page to highlight other work the charity does. 
* Page describing volunteering and the benefits to the individual. 

### Technologies Used
* HTML5 
* CCS3 
* Gitpod.io 
* GitHub 
* GIT 

#### Design
* Bootstrap 
* jsDelivr
* Google fonts 
* Balsamiq wireframe 
* Font Awesome 
* Tiny PNG 
* ResizePixel

#### Testing
* HTML Validator 
* CSS Validator
* DEV Tools – Lighthouse
* Wave
* Lambdatest

### Testing 
#### Validator Results 

For validation results, please see validator-results folder. 

#### Usability Testing

This website has been tested on screen sizes ranging from 320px to 1693px using developer tools. All links are functional and the website is well presented between these sizes.
On screens bigger than 1500px, the website is still functional and no elements stretch or warp. Text remains clear on very small to very large sizes.

Wave was used to asses the accessibility of the website. No errors or contrast errors were present. 
It also identified that the page structure was adequate with h1 to h4 text present in correct order.

#### Browser Compatibility 

The website has been tested on Chrome, Safari, Mozilla, Microsoft Edge and Internet Explorer using Browserstack and Lambdatest.
The website works as expected on Chrome and Edge. Mozilla presents a slightly different font on the navbar links, but is still entirely functional and readable.
Internet Explorer and Safari do not load the jumbo background-images, but the background colour is present so text is still readable.
Internet Explorer does not load colors changed in the root variable, but instead reverts back to basic Bootstrap styling. This is a known problem with IE and as
this browser is increasingly unpopular, it has been left unchanged.  

#### OS Compatibiility 

The website's functionality on Android and Apple phone products was tested via Lambdatest. Both were functional and well presented, though the products using Safari did not load background images to the jumbos.

#### Performance Testing

Following checks using lighthouse, the footer colour was changed to an off white so there was sufficient contrast between the text and background. 
To ensure it remained distinct from the rest of the webpage, a mid-blue border top was added. Rel=noopener value was added to all external links with a target=_blank attribute
to ensure security. 

##### Lighthouse Scores After Changes

For Desktop: 93 Performance
             100 Accessibility
             87 Best Practice
             89 SEO 
For Mobile: 85 Performance 
            98 Accessibility
            87 Best Practice
            91 SEO

#### User Stories
* A user that wishes to donate to the charity immediately.
The user can find a donate button immediately on the home page in a prominent positon. The button is clearly labelled and in a central position.

* A user that wishes to volunteer with the charity.
The user can find the relevent form quickly by using the navbar. There is also a Volunteer With Us button at the bottom of the home page, under a clear header.
The form has an existing option to request information about volunteering. 

* A user that wishes to find out more about what the charity does. 
The home page hero image has text which makes it explicit what the charity aims to do. The home page has a goals section immediately below the hero image.
This outlines the ethos of the charity and their facilities. There is a clearly named About page in the navbar which explains the charity's history, location and owners.

* A user might wish to contact the charity for more information. 
There are numerous Contact Us buttons on the site that lead to the Contact Us form. The contact us form has an existing option to request more information, and a section to state contact preference.
There is also a free text area where users can write details of their query. There is also contact us details in the footer on the right hand-side, incase users do not wish to fill out the form.

* A user might want to know about previous success stories before relinquishing their pet/adopting from Paws and Claws. 
There is a section detailing the circumstances that have found animals with Paws and Claws. There is a judgement free approach to talking about their previous circumstances. 
Each animal's page details their care, what training they have under gone and whether they are available for adoption. There is also crucial information relating to the animal's care (e.g special dietry requirements).

### Deployment

This site is hosted using GitHub pages, deployed directly from the master branch. The deployed site will update automatically upon new commits to the master branch. In order for the site to deploy correctly on GitHub pages, the landing page must be named index.html.

To run locally, you can clone this repository directly into the editor of your choice by pasting git clone https://github.com/hschafer2017/HSCHAFER-Portfolio.git into your terminal. To cut ties with this GitHub repository, type git remote rm origin into the terminal.

### Credits
All code, unless otherwise specified, was written by me. 
Thank you to Code Institute for supplying the template that this website uses. 
The responsive navbar was initially created from a tutorial w3schools. 
The fade in animations on the Success Stories pages was from https://blog.hubspot.com/website/css-fade-in and used in conjunction with bootstrap. 
The grow animation was found at https://travis.media/how-to-make-an-item-grow-on-hover-with-css*/. 

Thanks to my mentor, Brian Macharia, for excellent support and advice during the creation of this website. 
Thanks to everyone on the Code Institute slack group, especially in #newbies, who were exceptionally helpful in finding solutions to faults. 