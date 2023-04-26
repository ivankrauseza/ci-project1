# MZANZI Tours
## Code Institute Project 1 - HTML & CSS
A travel website bringing you the very best of Cape Town South Africa for travellers that want everything covered in a simple and affordable package. This website is developed in HTML and complimented by responsive CSS styling. Also included are minor JS packages for display icons (FONT AWESOME).   

![Screenshot](/assets/images/readme/Devices-01.jpg)  
[Image by storyset on Freepik](https://www.freepik.com/free-vector/responsive-concept-illustration_6170520.htm#query=multiple%20devices&position=0&from_view=keyword&track=robertav1_2_sidr)  

## Contents
- Introduction (above)
- Brand
- Features
- Testing Results
- Deployment
- Resources
- Credits

---

## Brand
Basic brand of MZANZI Tours was designed and produced by Ivan Krause.  
![Screenshot](/assets/images/readme/mzanzi-logo.jpg)  

### Typography
[Primary Font: Jost](https://fonts.google.com/specimen/Jost)  

### Colors
[Color Hunt](https://colorhunt.co/palette/f4f6fffbd46d4f8a8b07031a)  

| Color | Hex Value |
| --- | --- |
| Yellow | <span style="background-color:#ffcc00; color:#333">#ffcc00</span> |
| Teal | <span style="background-color:#4F8A8B; color:#fff">#4F8A8B</span> |
| Green | <span style="background-color:#12853F; color:#fff">#12853F</span> |
| Black | <span style="background-color:#000; color:#fff">#000000</span> |
| Dark Grey | <span style="background-color:#333; color:#fff">#333333</span> |
| Light Grey | <span style="background-color:#eee; color:#333">#eeeeee</span> |
| Ultra Light Grey | <span style="background-color:#f6f6f6; color:#333">#f6f6f6</span> |
| White | <span style="background-color:#fff; color:#333">#ffffff</span> |

---

## Features

### Header
The header is in a fixed position so that it is always visible at the top of the page. The content within the main tag has a top padding the same height as the header so that the very top of the content is not hidden under the header.
Navigation
The main navigation will reposition on a mobile device and sit on the bottom of the page like a mobile app. The idea comes from Instagrams default navigation on their app and the text will be hidden so only the icons display. The links have on page styling to indicate it is the active page.
There is a ‘Back to Top’ link in the main navigation but is only visible on mobile.
CTA (Call-To-Action)
The CTA (Call-To-Action) is a link to the booking form and is highlighted as a yellow button.  
  
![Screenshot](/assets/images/readme/header.png)  

### Footer
The footer is designed to be clean and simple and includes the copyright text and social media links. The social media links navigated to live pages within each platform and open in a new tab. The grid is styled using flexbox. The footer is fully responsive and is visible even with the mobile navigation fixed to the bottom of the page.  
  
![Screenshot](/assets/images/readme/footer.png)  

### Home
#### Hero image
The hero banner is a landscape image of Table Mountain which is Cape Town’s most iconic natural feature and includes view of the Victoria & Alfred Waterfront which is another major tourist destination in Cape Town. The section is fully responsive.  
  
![Screenshot](/assets/images/readme/hero.png)  

#### Home USP
Three tabs which give 3 unique selling points about travelling to Cape Town as a tourist with a read more link to the Packages offered by MZANZI Tours and is complimented by an image gallery below. The grid is styled using flexbox with a hover effect for descriptive text about each image. The section is fully responsive.  
  
![Screenshot](/assets/images/readme/usp.png)  

#### Home Gallery
The gallery is intended to give a real world example of the types of things a guest will see and do during a trip to Cape Town. All images in this gallery are provided by the developer Ivan Krause. The gallery is styled as a masonry grid which was inspired by the Love running section in the Code Institute LMS. The section is fully responsive.  
  
![Screenshot](/assets/images/readme/gallery.png)  

#### Home Testimonials and Newsletter
It is always good practice to include testimonials of paying customers on most websites. In this case, space was allocated for 4 testimonials which includes a profile image, quote, and the name of the guest. The grid is styled using flexbox. The section is fully responsive.  
  
The newsletter subscription form is only on the home page above the footer and is highlighted so that is stands out when the viewer gets to the bottom of the page. The section is fully responsive.  
  
![Screenshot](/assets/images/readme/guests.png)  

### Packages
The packages page offers the guest 2 options when making a booking. These are a summer and a winter option where the primary itinerary changes for each season but the guest can still see what else they can do. Each option has a hero image, key feature icons, description text about the package, the hotel, and the activities on offer. 
I included a place for a promotional video of the hotel and embedded YouTube videos.
The grid is styled using flexbox.  
  
![Screenshot](/assets/images/readme/packages.png)  

### Contact
The contact page includes three areas for Office information and contact details, a Google Map, and a contact form. When submitting the contact form, the page is redirected to the Thank You page for the form. This is styled using flexbox.  
  
![Screenshot](/assets/images/readme/contact.png)  

### Booking
The booking pages only purpose is to allow the guest to submit a booking request / inquiry with the most important information for MZANZI Tours to review and respond with the most suitable package quote. All fields are required and the form has a max width on desktop so that it is not too wide on bigger screens.  
  
![Screenshot](/assets/images/readme/booking-form.png)  

---

## Testing Results
I have tested the site in Chrome, Safari, Firefox, and Edge and the website displayed the same in each one.  
I have tested that the responsiveness of the site works accordingly.  
I confirm that the header, footer, navigation and contents match across all pages.  
I tested the form using the Code Institute form dump action, but for deployment I reverted to displaying a thank you page for the Newsletter sign up, Contact Form and Booking form.  
All relevant form fields are required when submitting and this is functioning.  


---

## Bugs

### Solved Bugs
I noticed that in the link tag for the favicon and css, the url needed a relative path for github pages, so the path needed to be href=”./assets/css/style.css” instead of href=”/assets/css/style.css”. 

### Known Bugs
#### Contact Page - Embedded Google Maps
![Screenshot](/assets/images/readme/bugs-google-map.png)  

---

## Deployment
The website has been deployed to GitHub Pages and can be viewed at this URL:  
[Click here to view on GitHub Pages](https://ivankrauseza.github.io/ci-project1/index.html)

---

## Resources
[Fonts : Google Fonts](https://fonts.google.com)    
[Icons : Font Awesome](https://fonts.google.com)     
[Stock Image "Giraffe" : Pexels](https://www.pexels.com/photo/giraffes-standing-on-brown-grass-field-11153531/)   
[Stock Image "Mountain" : Pexels](https://www.pexels.com/photo/scenic-view-of-drakensberg-mountain-ranges-10226222/)    
[Stock Image "Beach" : Pexels](https://www.pexels.com/photo/boardwalk-overlooking-the-beach-13791865/)   
[Stock Image "Founder" : Freepik](https://www.freepik.com/free-photo/woman-handsome-joking-senior-elderly_1088519.htm#query=founder%20white%20background&position=49&from_view=search&track=robertav1_2_sidr)    
[Stock Vector "World Map" : Freepik.com](https://www.freepik.com/free-vector/blue-world-map-design_893721.htm#query=world%20map&position=3&from_view=search&track=robertav1_2_sidr)    
[Stock Vector "Map South Africa" : FreeVectorMaps.com](https://freevectormaps.com/south-africa/ZA-EPS-02-0003)  
[Stock Image "Lions" : Pexels](https://www.pexels.com/photo/lions-surrounded-with-leafless-trees-1617411/)  
[Stock Vector "Devices"](https://www.freepik.com/free-vector/responsive-concept-illustration_6170520.htm#query=multiple%20devices&position=0&from_view=keyword&track=robertav1_2_sidr)
[Favicon Generator](https://www.favicon-generator.org/)  
[Favicon Addition : "W3S"](https://www.w3schools.com/html/html_favicon.asp)  

---

## Credits
[CSS @keyframes : Code Institute - Love Running](https://www.codeinstitute.net)    
[CSS Columns : "Code Institute - Love Running"](https://www.codeinstitute.net)  
[CSS @Media Query : W3Schools](https://www.w3schools.com/cssref/css3_pr_mediaquery.php)   
[CSS Flexbox Tips : "First column 100%"](https://stackoverflow.com/questions/41789278/first-child-full-width-in-flexbox)  
[JS : "Thank you Page redirect"](https://www.javascripttutorial.net/javascript-bom/javascript-redirect/)  
[JS : "Get URL parameter"](https://mrvirk.com/get-url-parameter-values-in-javascript.html)  
[JS : "Display variable in HTML"](https://sebhastian.com/display-javascript-variable-html/?utm_content=cmp-true)  

