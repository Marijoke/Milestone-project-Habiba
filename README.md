# Habiba Music

Habiba Music is to showcase Habiba, an up-and-coming UK R&B musician. The website will give new and existing fans the opportunity to hear her latest music and learn a bit more about her as an artist while being able to see upcoming shows and book tickets. The website was built mobile first and is responsive across all devices.
[](assets/images/Multi-device-Mock-up.png)
[Please see the deployed site here](https://marijoke.github.io/Milestone-project-Habiba/)
## UX
 This website is for existing and potential fans of Habiba. The website is to help Habiba build a relationship with fans by sharing images, music and information about her personal life. Visitors benefit from the ability to the sign up to the Habiba Music mailing list giving them exclusive access to her latest content and pre-sale tickets. 
I discussed the purpose of the website with the artist and spoke to a few fans which led me to the current build. Habiba wanted to keep the relationship she has with her fans as authentic as possible which is why there was a first-person biography included with the Music Monday videos Habiba creates for fun sometimes based on fan suggestions. 
The Home page must feature the most important content which in this case is the latest music and upcoming shows. During my research this was the most important for fans. The Gallery page was added as artist photos are popular amongst fans and were a popular feature on other artist pages within the same genre. The final page. Focuses on more on Habiba as an individual, her inspirations and the things she enjoys. This was the last page because designing mobile first forced me to chose what was the most important and put that first. The Modal Sign up in the Navigation Bar meant that it was always present across all pages just like the contact info in the footer. 
###Wireframes
I created the wireframes using [Balsamiq](https://balsamiq.com/)

#### Font 
The fonts chosen for the website are Montserrat (https://fonts.google.com/specimen/Montserrat?query=mont) for headings and Raleway (https://fonts.google.com/specimen/Raleway?query=ralewa) for body text. The fonts are from Google fonts where they were recommended as a popular pairing. I chose Montserrat because the text is clean and clear yet warm and friendly which is what attracts Habiba’s fans to her and what represents her music well.

#### Colours
The website was designed with the original branding in mind. Habiba’s logo is pink and white as is the aesthetic of her Instagram where I drew inspiration. I matched the Navigation bar and Footer to the logo and used [Coolers] (https://coolors.co/) to come up with complimentary colours that are used throughout the website. 
[insert coolers photo]
##User Stories 
As an existing fan, I want to hear Habiba’s latest music, get exclusive updates and access ticket pre-sales, so that I can keep my favourite playlist up to date, have updates on Habiba to share with my friends and see Habiba perform live.
As a potential user, I want to know more about Habiba and check out some of her music, so I can decide if I like her music enough to maybe see her live or add her to my music library.

## Features
### Existing Features
- Collapsible Navigation menu – allows all users to easily access the menu when viewing from a small screen, by selecting the hamburger menu that allows users to navigate between pages.
-  Modal sign-up – All interested fans can select the sign-up button in the Nav bar that pops up to avoid taking away from the page. Filling the form give the user exclusive contact.
- Footer – features contact information such as an email link and social media links to Habiba’s pages. 
-  Events widget – allows interested users to see upcoming performance dates and click through to venue location and get tickets. 
- Mobile first design – allows users to view the website across multiple platforms without compromising usability.
- Gallery Page – allows users to see artist photos is a visually pleasing way.
- All images including the logo have alternative text or assistance for screen readers to ensure website is accessible. 
### Features Left to Implement
-	Future developments will have a video carousel on the home page
-	 Additional page featuring the lyrics and explanations inspired by Genius (https://genius.com/) that allows the fans to get to know Habiba and develop a greater understanding of their favourite songs. 
## Technologies Used
- HTML5 
- CSS3
- [Bootstrap 4.5.3] (https://getbootstrap.com/)
    - Used to simplify layouts and create consistency of design while enabling responsiveness. 
- [Balsamiq](https://balsamiq.com/)
    - Created Wireframes for the project prior to development
Elfsight https://apps.elfsight.com/
-	Create the upcoming events section on the homepage 
Github https://github.com/ & Gitpod https://www.gitpod.io/
-used to write, store and view code
Google fonts https://fonts.google.com/
-	Used Montserrat (https://fonts.google.com/specimen/Montserrat?query=mont) and Raleway (https://fonts.google.com/specimen/Raleway?query=ralewa) fonts as described earlier. 
Font awesome 4.7
-	Used for contact icons in the footer

## Testing
In this section, you need to convince the assessor that you have conducted enough testing to legitimately believe that the site works well. Essentially, in this part you will want to go over all of your user stories from the UX section and ensure that they all work as intended, with the project providing an easy and straightforward way for the users to achieve their goals.

Whenever it is feasible, prefer to automate your tests, and if you've done so, provide a brief explanation of your approach, link to the test file(s) and explain how to run them.

For any scenarios that have not been automated, test the user stories manually and provide as much detail as is relevant. A particularly useful form for describing your testing process is via scenarios, such as:

1. Contact form:
    1. Go to the "Contact Us" page
    2. Try to submit the empty form and verify that an error message about the required fields appears
    3. Try to submit the form with an invalid email address and verify that a relevant error message appears
    4. Try to submit the form with all inputs valid and verify that a success message appears.

In addition, you should mention in this section how your project looks and works on different browsers and screen sizes.

You should also mention in this section any interesting bugs or problems you discovered during your testing, even if you haven't addressed them yet.

If this section grows too long, you may want to split it off into a separate file and link to it from here.

## Deployment

This section should describe the process you went through to deploy the project to a hosting platform (e.g. GitHub Pages or Heroku).

In particular, you should provide all details of the differences between the deployed version and the development version, if any, including:
- Different values for environment variables (Heroku Config Vars)?
- Different configuration files?
- Separate git branch?

In addition, if it is not obvious, you should also describe how to run your code locally.
## Bugs
The Bootstrap collapsible menu was not showing the preview. When selected in mobile mode nothing happened. After some assistance from my tutor the bootstrap CDN was updated and the menu was able to display properly in the previews.
Making the YouTube video responsive was a challenge. Thankfully, I found a YouTube tutorial (https://www.youtube.com/watch?v=9YffrCViTVk&feature=emb_logo) that worked perfectly. 
The logo would not stay in the centre and adjusting any aspect of the box model was a temporary solution. After trying to float the image and changing the position to relative of an absolute container with no luck, I got help from W3schools.com (https://www.w3schools.com/howto/howto_css_image_center.asp)

## Credits
### Content 
-	Habiba Biography was written alongside the artist to ensure accuracy and tone of voice. 
-	Mail to links https://www.w3docs.com/snippets/html/how-to-create-mailto-links.html 
learned mail to for contact in footer
- I used my love running project to help me create a gallery page (https://repl.it/@Marijoke/Love-Running#gallery.html)
- I used bootstrap to help with help the logo in the Navigation Bar
https://stackoverflow.com/questions/18474564/bootstrap-3-navbar-with-logo
-	Readme template (https://github.com/Code-Institute-Solutions/readme-template/blob/master/README.md#existing-features) and peer example (https://github.com/adowlin/project-1-dungeons-dragons/blob/master/README.md)

### Media
- The photos used in this site were either taken by me or obtained from the artist herself. I have been granted permission to use them for the purpose of this project. Selected Photos are featured here (https://photos.app.goo.gl/xAYMJZRdzJdymJRs7)
YouTube Tutorial for responsive video https://www.youtube.com/watch?v=9YffrCViTVk&feature=emb_logo
Classy Nemesis (https://www.classynemesis.com/projects/ytembed/) was used to add auto play and change a few of the colours on the YouTube iframe. Auto play was later removed after user feedback.
Elfsight (https://apps.elfsight.com/panel/applications/) was used to build the upcoming events calendar
Font Awesome (https://fontawesome.com/icons?d=gallery) for the footer icons 
Youtube Videos were sent via private link from the artist or located on Habiba’s YouTube page (https://www.youtube.com/c/HabibaAdamu/videos)
### Acknowledgements
- I worked closely with the artist to ensure I was creating something that she felt suited her brand.
- I used Slack to help troubleshoot issues I has as well as many google searches. 
- My Tutor Spencer for patiently giving me his time to help me work through any issues
- My mother for making sure I eat when I get too carried away with work.
- Habiba & her fans for helpful feedback.
- I received inspiration for the website from other artist sites like [Summer Walker](https://www.summerwalkermusic.com/) and [H.E.R](https://www.her-official.com/home/). I used the website to help me decide what features to have and what features I did not like.
