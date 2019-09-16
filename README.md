### RockThePalace

First Mile Stone Project: User-Centric Frontend Development - Code Institute

This is a website built to promote a fictional British band that is specialised in sixties style Rock and Roll. The name RockThePalace came from two parts: Rock&Roll and The Palace, referring to the British Monarchy. The website features 5 pages, and was designed to capture the attention of fans and potential fans to learn about the band’s new albums, past albums, history and members and to contact and book them for shows and private parties.

### Demo

Please follow [RockThePalace](https://ahmedsabik.github.io/Mile-Stone-Project-Trial-2/) to check the live demo. 

![Tux, the Linux mascot](/assets/images/16-responsive.jpg)
  
### UX

The goal of the design, as intended by the original mockup found [here](https://github.com/AhmedSabik/Mile-Stone-Project-Trial-2/blob/master/assets/images/15-mockup.jpg), was to create a visual identity for RockThePalace band, whilst making it easy for the visitor to read about the band members, history and work and navigate through the website. 

The drive behind the main layout was to encourage the visitor to listen to new and old releases and watch the band’s video releases, as well as providing links to the band’s social media profiles.

A reminder of booking and a link to the contact pages was also placed in different locations of the website, to deliver and reinforce the message that the band is available for bookings.

The Home page provided the reader with a brief overview of each of the band members, as well as a link to the music page.

The Music page showcased photos and audio from the band's catalogue.

The Music page showcased video clips embedded from the band's YouTube page.

The contact page offered two options: Either to contact the band directly via email, with links to different email providers, or to contact the band via a contact form that requested necessary information and a hint to remind the visitor that the band is available for booking.

### Technologies

- HTML
- CSS
- Bootstrap 4
- AWS Cloud9
- Adobe Photoshop
- [Google Fonts](https://fonts.google.com)
- [Font Awesome](https://fontawesome.com)
- Google Chrome Developer Tools

### Features

The Design: 5 separate pages with similar two tone colours: black and red, with a main menu situated on the right hand side and social media and contact list situated at the bottom of each page.

The Main menu: utilised CSS3 powered Grow hover effect, with modification to fit layout original design. The menu does not collapse is smaller screen sizes for an easier and a friendlier user experience.

The non-collapsible menu is located in a central location in smaller screen sizes and does not negatively impact the design.

Call to action buttons (such as: Book us now, Listen to .. etc): utilised Bootstrap’s Button Outline, with additional CSS manipulation. 

Social media links: utilised Font Awesome icons with additional manipulation.

### Features Left to Implement

In the future I would like to add further albums and videos to create a more comprehensive content. 

I would also like to replace the main background images with videos of concerts performed by the band. 

Furthermore, I would like to add a separate page that hosts a blog that provides daily updates of the band’s activities and a page dedicated to sell their albums and individual songs online.

### Testing

The website provides a comprehensive content about the band, their history and their work, with reviews about their work being highlighted in the main background image of each page.  

The design of the website is responsive, and renders well on a variety of devices and screen sizes.

The Home page features introduction to the band and its latest album, with 2 working links to Music page, a call to action button to make the visitor aware that the band is available for booking.

The Social media icons at the bottom link to outside resources and to the contact page. The social media and contact icons change colour smoothly upon hovering.

The Privacy link opens a new tab to a privacy policy template. Privacy link also changes colour smoothly upon hovering.

The Call to action buttons smoothly grow in size and change colour, for more attention.

The About page features a different album, and links to the Music page with a call to action button. The social media icons are displayed in two different locations to remind the visitor of the available outside resources. Fans can read information about the four members of the band. Another call to action button leads to the music page.

The Music page features 3 albums, with a poster and a brief introduction to each and 3 working HTML Audio files. The Music page is responsive, and designed to host more albums in the future. Music has been elemets tested manualy. 

The Video page features 3 HTML working video elements, embedded from YouTube. Video page is responsive, and designed to host more videos in the future. Video links has been tested manualy. 

The Contact page provides 2 options: Get in touch via email, using HTML address Tag that defines the contact information for the author/owner of the website. The visitor can choose to contact the band using the contact form, which utilises CSS Forms. The form will not submit if the visitor does not provide the required information, such as name, contact number, email address, etc. Furthermore, the email field is both required and required to be a valid email address format. A reminder message will appear in case an invalid email address provided, and the form will not submit.

On the top right corner of all pages a link to sign in/sign up could be found. The form will not submit if a valid email is not provided. An error message will also appear if the user attempts to submit an empty form.

The Mockup page was built for educational purposes, as I was not able to add a large image to an HTML file. The Mockup page was kept as a reference to the code used to resolve the issue. The Mockup image has been linked through Github as a better practice.

#### Techinal Problems

- A vertical white space could be scene across different screen sizes. The issue was resolved successfully using Google Chrome Developer tools. The website currently covers the whole screen across all platforms and devices. 
- Date input placeholder text in the Contact page form was black, as opposed to the light grey color of the rest of the input placeholder text. Issue researched on [w3schools.com](https://www.w3schools.com) and [stackoverflow.com](https://stackoverflow.com/questions/31706433/how-can-i-change-the-text-color-of-chromes-input-date-placeholder). Default placeholder text color identified and the issue was resolved successfully.
- Only 1 youtube video was working. Issue researched on Stackoverflow and resolved successfully by adding the word embed to the youtube link.  

### Deployment

This site is hosted using GitHub pages, deployed directly from the master branch. The deployed site will update automatically upon new commits to the master branch. In order for the site to deploy correctly on GitHub pages, the landing page must be named index.html.

To run locally, you can clone this repository directly into the editor of your choice by pasting git clone: [https://ahmedsabik.github.io/Mile-Stone-Project-Trial-2/](https://ahmedsabik.github.io/Mile-Stone-Project-Trial-2/) into your terminal. To cut ties with this GitHub repository, type git remote rm origin into the terminal.

### Credits

#### Content

- All content is written by me, with the help of various articles about Rock and Roll bands from Wikipedia. 

#### Media

- The photos used in this site were obtained from [Pexels](https://www.pexels.com/), a stock image library. All photos have been edited and manipulated using adobe Photoshop software.
- All videos used in this site were obtained from [The Muppets YouTube channel](https://www.youtube.com/user/MuppetsStudio).
- The privacy policy template was obtained from [docs.google.com](https://docs.google.com/document/d/1W3INZmdL8T72_HTKPXdC8L1wqXVkkwTdJwfyl0WppaQ/edit), and saved as a PDF file. 
- The audio file used in the music page was obtained from [Zedge](https://www.zedge.net/ringtones).
	
**This website is for educational use**.
