# Vegan life

Vegan Life is a website that aims to inform users about vegan life style. The site is intended for users who wish to change their life in order to start a vegan life. 

Vegan Life includes step by step info about the vegan stylelife with images and a description of the benefits of this new life style. Users who wish to attend a meeting  can use the Google Maps section to find where there is a meeting in the neighborhood. The site is intended for users who wish to have information about the vegan life in order to change their life style.

The live link can be found here [Vegan Life](https://christiancricchi.github.io/Vegan-Life/)


[Vegan life is responsive](docs/readme_images/responsive.png)

## Site Owner Goals 
- To provide the user with information about the benefits of vegan lifestyle, with a particular focus on philosophy of veganism. 
- To provide the user with clear and instructions as to how to complete the transition to a vegan lifestyle.
- To present the user with a website that is easy to navigate, fully responsive and invokes a sense of calm and and non-violence through the use of appropriate colours and images. 
- To enable the user to find places where the vegan community gathers for meetings and conferences.
- To allow users to contribute their opinions and sign up to the vegan life newsletter.

## User Stories
- ### First time user
  - As a first time user I want to understand the main purpose of the site and learn about the wellbeing of a vegan lifestyle and the health and mental health benefits.
  - As a first time user I want to be able to intuitively navigate the website and have a positive emotional experience. 
  - As a first time user I want to be able to browse vegan life content without having to sign-up / register.

- ### Returning User
  - As a returning user I want to easily navigate to the information of vegan life site.  
  - As a returning user I want to find step by step info in order to complete the transition to a vegan lifestyle .
  - As a returning user I want to be able to find vegan community in my locality to be part of the vegan community in my neighborhood.

- ### Frequent User
  - As a frequent user I want to be able to sign-up to the vegan life newsletter in order to get the latest news and information about the vegan lifestyle.
  - As a frequent user I want to be able to contribute with my opinion regarding the topics discussed in the page.

## Design

### Imagery
The imagery used on the vegan life site is very important to the overall experience of the user. A calm theme is consistently used across all imagery with lots of green and peacefull scenes. This gives the sense of union with nature and animals which has great benefits for health, mental health and is intended to invoke a sense of calm and non-violence in the user. The colour green and nature and anumals theme is also important as this ties into the main colour scheme of the website.

### Colours
The colour scheme of the website is white and green with varying shades of green orange used to tie in with the vegan imagery. A dark grey font is used which has a good contrast with the light green and white backgrounds making it easy to read. 

### Fonts
The Montserrat font is the main font used throughout the whole website. This font was imported via [Google Fonts](https://fonts.google.com/). I am using Sans Serif as a backup font, in case for any reason the main font is not being imported into the site correctly.

## Wireframes
Wireframes were produced using Balsamiq. 

<details>

 <summary>Desktop Wireframe</summary>

![Desktop Wireframe](docs/wireframes/Desktop.png)
 </details>

 <details>
    <summary>Mobile Wireframe</summary>

![Mobile Wireframe](docs/wireframes/Mobile.png)
 </details>

## Features
- ### Navigation

    - The fully responsive navigation bar includes links to the Logo, Home, About, Info, Find Us, Contact Us.
    - The Info navigation link includes a drop down menu which includes further links to each section.
    - The navigation bar has a fixed position so that it remains visible at the top of the page as the user navigates through the individual sections. 
    - A drop shadow was applied to the navigation bar to make sure that it doesn't blend into the other sections of the page upon scrolling.
    - This section allows the user to easily navigate through the site to find content without having to scroll back up to the top of the page or use the browser back button.

![Nav bar image](docs/readme_images/navigation.png)

- ### The Landing Page Image
    - The landing page includes an eye-catching image with a text overlay describing the site's goal.
    - This section provides the user with a clear visual representation of the purpose of the site.

![Landing page image](docs/readme_images/LandingPage.png) 

- ### About Section
    - The About Section gives a brief description of vegan life gives further details about what the site offers to users.
    - Below the About text there are four small images with navigation links to each Info Section.
    - This section will show users the value of vegan life and links invite the user to further explore the site as an alternative to the navigation bar. 

![About section image](docs/readme_images/About.png)

- ### Info Section
    - This section contains four section linked to a different section and type of info. 
    - This section is valuable as the user is provided with step by step instructions and the benefict of a vegan lifestyle. 

![Info section image](docs/readme_images/Info.png)
  

- ### Find Us Section
    - The Practice Section includes an iframe with an embedded Google Map showing the locations of vegan place in Cardiff.
    - This section will enable the user to find a vegan place within their locality should they wish to attend a restaurant or the vegan community.

![Find Us image](docs/readme_images/FindUs.png)

- ### Contact us Section
    - The contribute section includes a background video of a tree with moving leaf.
    - The user is invited to sign up to Vegan Life and contribute their suggestion. The users have the possibility to receive the Vegan life Newsletter by selecting the checkbox provided.

![Contact Us section image](docs/readme_images/ContacUs.png) 

- ### Footer
    - The footer section includes links to Vegan's life Facebook, Instagram, Twitter and Youtube pages.
    - The links will open to a new tab to allow easy navigation for the user. 
    - The footer is valuable to the user as it allows them to find and follow Vegan Life on social media

![Footer image](docs/readme_images/Footer.png)

### Features Left to Implement
- A button for the mobile nav bar.
- The ability to search by Info as the bank of information, books, studies grows.

## Testing

### Validator Testing
- #### HTML
    - No errors were returned when passing through the official W3C Markup Validator
        - [W3C Validator Results](https://validator.w3.org/nu/?doc=https%3A%2F%2Fchristiancricchi.github.io%2FVegan-Life%2Findex.html))
- #### CSS
    - No errors were found when passing through the official W3C CSS Validator 
        - [W3C CSS Validator Results](https://jigsaw.w3.org/css-validator/validator?uri=https%3A%2F%2Fchristiancricchi.github.io%2FVegan-Life%2Fassets%2Fcss%2Fstyle.css&profile=css3svg&usermedium=all&warning=1&vextwarning=&lang=en)
- #### Accessibility 
    - The site achieved a Lighthouse accessibility score of 100% which confirms that the colours and fonts chosen are easy to read and accessible

![Lighthouse score]()

### Form Testing
- The form has been tested to ensure it would not submit without the required input fields being filled in (full name and email address).

### Links Testing
- All navigation links were tested manually to ensure the user is directed to the correct section of the website.
- Social Media links in the footer of each page were tested manually to ensure they direct the user to the correct page and open in a new tab. 

### Browser Testing
- The Website was tested on Google Chrome, Firefox, Microsoft Edge, Safari browsers with no issues noted.
    
### Device Testing
- The website was viewed on a variety of devices such as Desktop, Laptop, iPhone 8, iPhoneX and iPad to ensure responsiveness on various screen sizes. The website performed as intended. The responsive design was also checked using Chrome developer tools across multiple devices with structural integrity holding for the various sizes.
- I also used the following websites to test responsiveness:
    - [Responsinator](http://www.responsinator.com/?url=christiancricchi.github.io%2FVegan-Life%2F)
    - [Am I Responsive](https://ui.dev/amiresponsive?url=https://christiancricchi.github.io/Vegan-Life/)


### Friends and Family User Testing
Friends and family members were asked to review the site and documentation to point out any bugs and/or user experience issues.

### Fixed Bugs

#### Anchor link scroll with a fixed position header
- The header element contains anchor links to allow the user to navigate to different sections within the website. By default, these will scroll so that the target element is flush with the top of the browser window.
- When I updated the header to use a fixed top position, the beginning of each section ended up being covered by the header, which wasn’t ideal.
- To resolve this I created div elements at the top of each section and applied a relative position with a -75px top position (the same height as the header). This way, when the user clicks on a nav link, the browser window scrolls to the top of the corresponding section.

### Known Bugs

- HTML Smooth Scroll does not work on Safari browser.
- When the screen size is reduced, the 4 circular images overlap instead of being in a column.

## Technologies Used

### Languages
- HTML5
- CSS

### Frameworks - Libraries - Programs Used
- [Am I Responsive](http://ami.responsivedesign.is/) - Used to verify responsiveness of website on different devices.
- [Responsinator](http://www.responsinator.com/) - Used to verify responsiveness of website on different devices.
- [Balsamiq](https://balsamiq.com/) - Used to generate Wireframe images.
- [Chrome Dev Tools](https://developer.chrome.com/docs/devtools/) - Used for overall development and tweaking, including testing responsiveness and performance.
- [Font Awesome](https://fontawesome.com/) - Used for Social Media icons in footer.
- [GitHub](https://github.com/) - Used for version control and hosting.
- [Google Fonts](https://fonts.google.com/) - Used to import and alter fonts on the page.
- [TinyPNG](https://tinypng.com/) - Used to compress images to reduce file size without a reduction in quality.
- [W3C](https://www.w3.org/) - Used for HTML & CSS Validation.

## Deployment

The project was deployed using GitHub pages. The steps to deploy using GitHub pages are:

1. Go to the repository on GitHub.com
2. Select 'Settings' near the top of the page.
3. Select 'Pages' from the menu bar on the left of the page.
4. Under 'Source' select the 'Branch' dropdown menu and select the main branch.
5. Once selected, click the 'Save'.
6. Deployment should be confirmed by a message on a green background saying "Your site is published at" followed by the web address.

The live link can be found here - [Vegan Life](https://christiancricchi.github.io/Vegan-Life/)

## Credits

### Content
All educational vegan life content was sourced from the below websites:
- [Vegan food and living](https://www.veganfoodandliving.com/vegan-basics/basic-guides/what-to-watch-out-for-when-going-vegan/)
- [Ong te protejo](https://ongteprotejo.org/ar/)
- [Ekhart Yoga](https://www.ekhartyoga.com)
- [Vegan Society](https://www.vegansociety.com/)
- [VRG](https://www.vrg.org/)
- [The Vegan Hopper](https://www.theveganhopper.com/veganismo-recursos-y-paginas-utiles/#google_vignette)
- [Arango Medina, C. (2016). El mundo vegano: un nuevo estilo de vida, una nueva ética](repository.eafit.edu.co.)[onlineAvailable at:](https://repository.eafit.edu.co/items/68475962-25db-4561-a3da-d4eed08bfb80) [Accessed 23 Jan. 2024].


### Media
All images and videos were sourced from the below websites with thanks to the below amazing photographers/videographers and from my friend Sebastian Fornesi that drawn down the Vegan life image with the fruit.
- [Pexels](https://www.pexels.com/)
  - Tree Video
- [Unsplash](https://unsplash.com)
  - Motivation
  - Practice
  - Principles
  - Veganlige
- [Google Images](https://images.google.co.uk/)
  - Veganlife1
  - Vegano
  - Vegetarianismo
- [Favicon](https://favicon.io/)
  - VLiconGreen
- Sebastinan Fornesi
  -veganF 
 
### Resources Used

- Inspiration for dropdown nav bar - [W3Schools](https://www.w3schools.com/)
- [Stack Overflow](https://stackoverflow.com/)
- Insipration for the layout [AliOKeeffee](https://github.com/AliOKeeffe/mindyoga)

## Acknowledgments

My lovely wife Vivian for her support, advice and help in the crisis moments.

My mentor Antonio for his support and advice.

The Code Institute slack community for their quick responses and very helpful feedback!









