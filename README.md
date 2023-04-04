
# Mind&Body Mastery

The Website dedicated to yoga, meditation, and mindfulness provide a range of resources, quotes and pictures to help users motivate, teach and improve their overall well-being.

The aim of the website is to help individuals cultivate greater self-awareness, develop more meaningful relationships, and achieve greater self through the practices of yoga, meditation, and mindfulness.




![Screenshot (7)x](https://user-images.githubusercontent.com/127791713/229752948-19eecc20-81fa-4d20-b338-6e9d9ca92198.png)


## Features

- Navigation Bar.
- Featured on all three pages, the full responsive navigation bar includes links to the Logo, Home page, techniques page, Gallery and Sign Up page to allow for easy navigation.
- Logo will allow the user to easily navigate from page to page across all devices without having to revert back to the previous page via the ‘back’ button.
- The landing includes a photograph with text overlay eye catching animation to motivate and grab their attention.

![Screenshot (14)](https://user-images.githubusercontent.com/127791713/229758070-43d873e1-988d-4866-8171-50dda53ca90d.png)

## Midsection
- This user will see the value of signing up for the Mind&Body Mastery. This should encourage the user to consider trying out as their form of exercise.
- The get started button will send you to sign up page direct.
![Screenshot (10)](https://user-images.githubusercontent.com/127791713/229758491-eb2236bd-7fc7-4ed8-8575-5ee9b0e139c1.png)

## The Footer

- The footer section includes links to the relevant social media sites for Mind&Body Mastery. 
- The links will open to a new tab to allow easy navigation for the user.
![Screenshot (15)](https://user-images.githubusercontent.com/127791713/229762832-8d7b24fd-6c51-440d-93a6-013f8e80d11b.png)

## Techniques page
The techniques page will provide the user with supporting images and text to guide them in their journey.

![Screenshot (11)](https://user-images.githubusercontent.com/127791713/229764746-54053c62-f51a-41ee-bd41-37c5a765b2d1.png)

## Gallery page

The gallery will provide the user with supporting images to see and get motivated.

![Screenshot (12)](https://user-images.githubusercontent.com/127791713/229763246-2e2dd0a1-99c6-48c3-957c-008106671d25.png)

## The Sign Up Page

- This page will allow the user to get signed up to Mind&Body Mastery to start their journey.
- The user will be asked to submit their full name and email address.
![Screenshot (13)](https://user-images.githubusercontent.com/127791713/229765857-c2c6e07e-71ae-479b-b997-62a6222c2df7.png)

## User stories
- As a First Time Visitor, I want to easily understand the main purpose of the site and learn more about your self.
-  I want to be able to easily navigate throughout the site to find content and get motivated.
- I want to sign up to the website so that I am emailed any major updates or events or just to get motivated.
- The main points are made immediately with the hero image.
- The user has two options, click the sign up buttons or scroll down, and click the get started buttons both of which will lead to the same place, to sign up page.

## Languages Used
- HTML5
- CSS3

## Testing
- i tested that this page works in different browsers: Chrome, Firefox, Safari.
- that this project is responsive, looks good and functions on all standard screen sizes using the devtools device toolbar.
- that the navigation, header, gallery, techniques, sign up, and contact text are all readable and easy to understand.
- that the form works: requires entries in every field, will only accept an email in the email field, and the submit button works.
- that the get started button works.

## Validator Testing
- HTML No errors were returned when passing through the official W3C validator.
- CSS No errors were found when passing through the official (Jigsaw) validator.
![Screenshot (5)](https://user-images.githubusercontent.com/127791713/229769391-ef8cea4e-2141-4eed-9bfd-8b4c1120206c.png)

![Screenshot (6)](https://user-images.githubusercontent.com/127791713/229769688-12dea8a1-8fb2-4445-8481-d3ee01d500d6.png)

- I confirmed that the colors and fonts chosen are easy to read and accessible by running it through lighthouse in devtools.

![Screenshot (9)](https://user-images.githubusercontent.com/127791713/229770748-642ddd5e-2473-480e-998e-dc7ae9e0520b.png)
 
 ## bugs fixed
 - 1- in mobile screen the sign up page the form was too big for the screen under 350px the bug happens.
  form {                                            form{
    width: 90%;                                        width:80%;
    margin: 50px auto 0;              TOO              margin: 50px auto 0;
    margin-top: 70%;                                   margin-top: 40%; 
  }                                                  }
 - 2- in mobile screen the #menu li the sign up text position was wrong the (up) text was under (sign) text.
  #menu li {                                                  #menu li { 
    display: block;                                              display: block;
    margin: 5px 0;                                               margin: auto;
    width: 50%;                                                  min-width: fit-content;
    padding: 5px;                                                padding: 1%;
    font-size: 75%;                                              font-size: small;
  }                                                             }
  
## unfixed bugs 
- No

## credits
- love running project for the text overlay in hero image.
- fontawesome.com for the icons.
- freepik.com for pictures.
- google fonts for text style.
- and youtube for research.

## Acknowledgements
My Mentor for helpful feedback.