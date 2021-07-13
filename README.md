# Urban University Dublin Finance Office

The Urban University Finance Office is provides support to the (fictitious) Urban University Dublin staff and students who are required to perform one of the many financial tasks that are part of the daily affairs of the institution. Individuals who require guidance on one or more of the many financial policies or financial processess can use the site for contact information, submit inquiries or find directions to the building if they prefer to do so in person. 

![Responsive Mockup](https://github.com/rch79/MS1-Finance-Office/blob/master/assets/images/readme/responsive-site-mockup.PNG)


### Existing Features

- __Navigation Bar__

  - Featured at the top of all pages, includes links to the logo (home page), home, staff and contact pages
  - The navigation bar enables site users to visit all pages within the site without having to use the back button in their broser.

![Nav Bar](https://github.com/rch79/MS1-Finance-Office/blob/master/assets/images/readme/navigation-bar.PNG)

- __The landing page image__

  - The landing includes a photograph of the building in which the Finance Office is located to provide potential walk-in customers with a visual reference of the office's location

![Landing Page](https://github.com/rch79/MS1-Finance-Office/blob/master/assets/images/hero-image-index.jpg)

- __Our Services Section__

  - It states the role of the Finance Office within the University's organization to give site visitors a broad idea of the functions performed by the office staff
  - It lists the services offered by the Finance Office

![Our Services](https://github.com/rch79/MS1-Finance-Office/blob/master/assets/images/readme/our-services.PNG)

- __The Footer__ 

  - Featured at the bottom of each pages, it provides the users with the office’s main address, and external links to the Finance Office’s social media sites (Linkedin, Facebook, and Twitter)
  - Users who wish to contact the Finance Office on one of these external sites can do so by clicking on the links provided

![Footer](https://github.com/rch79/MS1-Finance-Office/blob/master/assets/images/readme/Footer.PNG)

- __The Staff page__

  - Lists the current staff of the Finance Office, including their contact details (name, job title, email address and phone number).
  - Includes photos of each staff member to serve as a visual cue for walk in customers.
 

![Staff](https://github.com/rch79/MS1-Finance-Office/blob/master/assets/images/readme/staff-page.png)


- __The Contact Us page__

  - The form section enables site users to submit their inquiries to the Finance Office Staff. To submit an inquiry, the user must fill out the first name, last name, email address and the textarea sections. The phone number is optional
  - The map (directions) section notifies site users that walk ins are welcome, and provides users with direftions to the Finance Office. A Google maps iframe is embedded for added convenience.


![Contact Us](https://github.com/rch79/MS1-Finance-Office/blob/master/assets/images/readme/contact-us.png)


### Features Left to Implement

- A Forms page, which would allow site users to search for and download an assortment of financial forms used on many Finance-related tasks in the University (ie, PO request form, petty cash request form etc).
- A Policies page, which would provide site users with links to the varous financial policies in use by the University.


## Testing 

All hyperlinks were tested to see if they are working properly. Internal links open in the same tab. External links (in the footer) open in a new tab.

Google Chrome developer tools were used to test resposive design. All three pages scale correclty on the following screen sizes:

  - Moto G4 (360 x 640)
  - Galaxy S5 (360 X 640)
  - Pixel 2 (411 x 731)
  - Pixel 2 XL (411 X 823)
  - iPhone 5/SE (320 x 568)
  - iPhone 6/7/8 (375 x 667)
  - iPhone 6/7/8 Plus (414 x 736)
  - iPhone X (375 X 812)
  - iPad (768 x 1024)
  - iPad Pro (1024 x 1366)
  - Surface Duo (540 x 720)

The form submit on the Contact Us page is being validated using the [Code Institute's Form Dump Page](https://formdump.codeinstitute.net/) to ensure data is being correctly capture and submitted.

All three pages have ben checked for horizontal scroll bars produced by overflows (on all scree sizes).

Placement of the staff photos on the Staff page using floating divs has proven tricky. Switching to a grid layout turned out to be a much simpler solution.


### Validator Testing 


- HTML
  - __Home page__
    - No errors were returned when passing through the official [W3C validator](https://validator.w3.org/nu/?doc=https%3A%2F%2Frch79.github.io%2FMS1-Finance-Office%2Findex.html).

  - __The Staff page__
    - No errors were returned when passing through the official [W3C validator](https://validator.w3.org/nu/?doc=https%3A%2F%2Frch79.github.io%2FMS1-Finance-Office%2Fstaff.html).

  - __The Contact Us page__
    - Errors were returned on the embedded Google Maps iframe code generated by the Google Maps iframe Generator from [Maps.ie](https://www.maps.ie/create-google-map/). No errors were return on the code written by me by the official [W3C validator](https://validator.w3.org/nu/?doc=https%3A%2F%2Frch79.github.io%2FMS1-Finance-Office%2Fcontact-us.html).

- CSS
  - No errors were found when passing through the official [(Jigsaw) validator](https://jigsaw.w3.org/css-validator/validator?uri=https%3A%2F%2Frch79.github.io%2FMS1-Finance-Office%2Findex.html&profile=css3svg&usermedium=all&warning=1&vextwarning=).

### Lighthouse Reports

 - __Home page:__

<img src="https://github.com/rch79/MS1-Finance-Office/blob/master/assets/images/readme/lighthouse-main-page.PNG" width="400" height="400">



 - __Staff page:__

<img src="https://github.com/rch79/MS1-Finance-Office/blob/master/assets/images/readme/lighthouse-staff-page.PNG" width="400" height="400">



 - __Contact Us page:__

<img src="https://github.com/rch79/MS1-Finance-Office/blob/master/assets/images/readme/lighthouse-contact-us.PNG" width="400" height="400">

### Unfixed Bugs

You will need to mention unfixed bugs and why they were not fixed. This section should include shortcomings of the frameworks or technologies used. Although time can be a big variable to consider, paucity of time and difficulty understanding implementation is not a valid reason to leave bugs unfixed. 

## Deployment

- The site was developed using the Windows 10 version of Sublime Text, in conjunction with the Github Desktop client
- The site was deployed to Github Pages using the following steps:
  - In the GitHub repository, navigate to the Settings tab 
  - From the source section drop-down menu, select the Master Branch
  - Once the master branch has been selected, the page will be automatically refreshed with a detailed ribbon display to indicate the successful deployment. 

The live link can be found here - https://rch79.github.io/MS1-Finance-Office/ 


## Credits 

### Content 

- The text used to describe the role of the Finance Office was based on the website of the [MIT Office of the Vice President for Finance](https://vpf.mit.edu/about-vpf).
- Social media icons in the footer are provided by [Font Awesome](https://fontawesome.com/).
- The grid code used in the Staff page was generated using the [Layoutit Grid tool](https://grid.layoutit.com/).
- This README file was created using the README template provided by the [Code Institute](https://codeinstitute.net/). The language used to describe the GitHub deployment process was copied verbatim from the template.
- Fonts are provided by [Google Fonts](https://fonts.google.com/).

### Media

- The hero image in the home page and the staff photos were downloaded from [Unsplash](https://unsplash.com).
- The background tile pattern used in the Staff page was downloaded from [Toptal](https://www.toptal.com/designers/subtlepatterns/).
- The Google Maps embed code was genereated using the [Maps.ie Google Maps iframe Generator](https://www.maps.ie/create-google-map/).
- The reponsive site mockup was created using the [Multi Device Website Mockup Generator](https://techsini.com/multi-mockup/index.php).


## Acknowledgements

- A huge thank you to my mentor Spence Barriball, who has provided me with invaluable guidance throughout this process.
- Thank you to the Code Institute team for the enjoyable lessons and  excellent reference materials.
