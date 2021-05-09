# The Tirukkuṟaḷ (திருக்குறள்) project
I am embarking on a passion project on the side and looking for collaborators.

## Concept
Bring classical Tamil literary works to the younger generation in digital / multimedia formats  Works Chosen: To start with we shall begin with the classical work Tirukkuṟaḷ (திருக்குறள்). Other works shall be taken up in due course.  

## Help needed
We need volunteers in multiple skill areas.  
  - **Illustrators:** Each of the 133 chapters and each of the 1330 verses shall be illustrated 
  - **Content editors:** Responsible for formatting and organizing the content under the project's standards and guidelines 
  - **Translators:** Responsible for translating the verses into different languages. Our goal is to make this work accessible in every language. 
  - **Designers:** Responsible for the layout and design of artefacts  
We probably need more roles. This is just a starting list.  

## Targeted Delivery formats
Physical flash cards, eBook, print book, Website, App to start with.

This is a massive project. If you love Tamil language and classical works, have the skills and would like to volunteer or contribute in some form, please mention it in the comment or InMail me. (https://linkedin.com/in/vvgiri) 

This GitHub repository is for managing the collaboration workspace and artefacts.

## Specifications

### Mockups folder

The [`mockups` folder](./mockups) has some examples of how to organize the content. We will use the standard Kural numbering (from the original book). Each verse shall get its own folder that contains the following files:

+ parent_folder
  + verse_number
    + verse_number.jpg  (The illustration for the verse)
    + data.xml          (The verse semantic content)
    + index.html        (The verse document)
  + another verse
  + ...
  + css
    + style.css
  + index.html   (The root document)

See the `mockups` folder for an example for [Kural #291](./mockups/291/index.html). 

> **Tip:**
> To locally serve the HTML files, you can use the NodeJS module `http-server`
> First install NodeJS. Follow [instructions here](https://nodejs.org/en/download/).
> 
> Install `http-server` module [using npm](https://www.npmjs.com/package/http-server).
> 
> You can then run the web server locally from the `mockups` folder

<img src="./mockups/screenshots/running_http_server_screenshot.jpg" alt="Running http-server locally" width="400px"/>

![Homepage mockup screenshot](./mockups/screenshots/homepage_screenshot.jpg "Homepage mockup screenshot")

![Verse 291 screenshot](./mockups/screenshots/verse_291_screenshot.jpg "Verse 291 screenshot")


