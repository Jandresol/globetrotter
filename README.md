# globetrotter
📝 `NOTE` Use this template to initialize the contents of a README.md file for your application. As you work on your assignment over the course of the week, update the required or stretch features lists to indicate which features you have completed by changing `[ ]` to `[x]`. (🚫 Remove this paragraph before submitting your assignment.)

## Unit Assignment: Globetrotter

Submitted by: **Jasmine Andresol**

Estimated time spent: **10** hours spent in total

Deployed Application (optional): [Globetrotter Deployed Site](https://jandresol.github.io/globetrotter/)

### Application Features

#### CORE FEATURES

- [x] **Home Page**
  - [x] A heading that mentions the destination.
  - [x] An introductory paragraph that welcomes visitors and dsescribes the purpose of the website. 
  - [x] An evocative image that represents the location.
  - [x] Content organized using Flexbox for a fluid layout.

- [x] **Top Attractions Page**
  - [x] A separate page featuring a minimum of three attractions, each including a:
    - [x] Name
    - [x] Photo
    - [x] Brief description
  - [x] Each attraction is styled the same
    - E.g. same font, image size, title size, etc. 
  - [x] Content arranged with Flexbox for consistency and responsiveness.

- [x] **Guide Page (Choose One)**
  - [x] A separate page that is either a Food Guide, Accommodations Guide, or Upcoming Local Events guide.
  - [x] At least three entries thematic to your choice that provide a:
    - [x] Title
    - [x] Address
    - [x] Description
    - [x] Link with more information (e.g. link to a restaurant page)
  - [x] Each entry should be:
    - [x] Catered to a specific type of traveler (families, backpackers, etc.)
    - [x] Styled the same
      - E.g. same font, title size, etc.
  - [x] Content arranged with Flexbox for consistency and responsiveness. 

- [x] **Photo Gallery**
  - [x] Separate page with at least five images related to the site's topic.
  - [x] Each image should include a caption describing the image.
  - [x] Presented in a responsive design using Flexbox.

- [x] **Navigation Bar**
  - [x] Navigation bar with working links to each of the following pages:
    - [x] Home Page
    - [x] Top Attractions
    - [x] Photo Gallery
    - [x] Guide Page (Food Guide, Accomodations Guide, _or_ Upcoming Local Events Guide)
  - [x] Navigation bar can be accessed from each page of the website.
  - [x] Styled with Flexbox that adapts to different screen sizes.  

- [x] **Smartphone Friendly**
  - [x] A design that is fully functional and aesthetically pleasing on smartphones is achieved using media queries.

### Stretch Features

- [x] **Additional Media**
  - [x] Embed a piece of media that is not an image or text and relates to the travel content such as a:
    - Map
    - Video
    - Song

- [x] **Enhanced Layouts**
  - [x] Utilize CSS Grid on one or more pages for a unique layout.

- [x] **Interactive Navigation**
  - [x] Implement a dropdown menu where at least one menu item includes a nested dropdown menu to access additional categories or sub-pages.

- [x]**Travel Newsletter Form**
  - [x] Create a form to allow users to sign up for a travel newsletter, enhancing user engagement.
  - [x] *Note*: You do not have to collect and save the data submitted using the form. 

- [x] **Deployment**
  - [x] Deploy your website so it's accessible to the public outside of your local machine. 
  - [x] **VIDEO WALKTHROUGH SPECIAL INSTRUCTIONS:** For ease of grading, please film yourself using your deployed URL with the URL visible in your video. 

- [x] **Custom Styling**: Add a personal touch to your site's design.
  - [x] Integrate at least one custom font using Google Fonts to add personality to your site.
  - [x] Experiment with at least one CSS property not covered in the lessons or labs to customize your page further.

### Walkthrough Video

[![Walkthrough](https://cdn.loom.com/sessions/thumbnails/2760f392127049a5a6b95e7ace3661b2-with-play.gif)](https://www.loom.com/share/2760f392127049a5a6b95e7ace3661b2?sid=f018d074-e866-473d-94c4-984d667c41f7)

<div>
    <a href="https://www.loom.com/share/2760f392127049a5a6b95e7ace3661b2">
      <p>Globetrotter Project - Jasmine Andresol - Watch Video</p>
    </a>
    <a href="https://www.loom.com/share/2760f392127049a5a6b95e7ace3661b2">
      <img style="max-width:300px;" src="https://cdn.loom.com/sessions/thumbnails/2760f392127049a5a6b95e7ace3661b2-4486c8f02a7b5911-full-play.gif">
    </a>
  </div>

  Deployed Url: https://jandresol.github.io/globetrotter/
  
### Reflection

* Did the topics discussed in your labs prepare you to complete the assignment? Be specific, which features in your weekly assignment did you feel unprepared to complete?

I think the most helpful lesson was the advanced CSS lesson that went with lab 3 and 4. Learning how to use flex-boxes was the most important part of the project for me. Additionally, the lesson 1 topic of HTML/CSS classes v.s. ids was really helpful. From the labs learning the difference between semantic and non-semantic tags was helpful and learning to use section v.s. div v.s. article. I also think the flex-box exercises we did in class as well as the live demonstration was very helpful. The least prepared I felt was actually getting the files set up, and knowing how to navigate using the <head> tag, especially when dealing with uploading google fonts. I think if we went through uploading a custom font that would have been helpful as well as navigating how to embed different types of media.

* If you had more time, what would you have done differently? Would you have added additional features? Changed the way your project responded to a particular event, etc.
  
If I had more time, I think I would have spent time creating a mockup design of the website. This would allowed me to figure out the skeleton of the website early on so I wouldn't run into inheritance issues later down the line, or ensure reusability. I find my biggest issue regarding the design of my code is that I was overly-reliant on IDs rather than combining classes to ensure that my code reduced redundancy. I do think that there are a few lines of code in my CSS file that could be abstracted away.

Regarding features: I would have improved some of the interactivity, such as creating a hamburger button so the menu could be expandable. I also would like to experiment with the photo gallery and see if I could implement a carousel. I would also create new pages to serve as a blog and most likely use a database to serve as a content management system where multiple articles could be written and stored.

* Reflect on your project demo, what went well? Were there things that maybe didn't go as planned? Did you notice something that your peer did that you would like to try next time?

My biggest takeaway from this project is that I got really comfortable with CSS. I became very adept at turning a design into in actual website and putting my vision to the screen. This project tested my ability to code for a prolonged period of time and implement a website from start to finish with about 1000 lines of code. I am really happy with the end-product and believe that the website is well polished, especially regarding the design of the pages.

I got really stuck on implementing an interactive navbar. I believe my issues mainly came from the sheer number of classes I had and it became hard to keep track of what was inherited. I also found myself accidently overriding myself by using different types of selection (element based v.s. class based), for instance I realized I overrided my #navigation class through the nav element, so I learned to avoid using element selectors. The main issue arose from ensuring that the elements were aligned together, I found myself using the attributes display, flex-direction, align-items, and align-text, very frequently in order to ensure my design looked consistent on all pages. Additionally, I did a lot of tinkering with the navbar in the mobile form, performing trial and error to ensure everything looked the way I wanted to. While debugging, I commonly used inspect element to identify which element I needed to modify in order to fix a pressing design issue. I also had issues of overlap with the flex box, so ensuring that all parent elements had display: flex as well as position: relative defined in the css

Regarding inspiration from other classmates, I wish I experimented a bit more with the design. I feel like my color palette was a bit muted and simple, and I could have played around with using the colors of the flag, or created a product that I thought displayed more creativity, similar to some of my other team members. For instance, I noticed someone incorporated the sun from their countries flag as an element of the website. I also like how some of my peers also experimented with their layouts and background.


### Open-source libraries used
None

### Shout out
Thank you Keith and Alex for helping me debug some issues!