# CITY GARDENS

City Gardens is a website designed to connect potential and active users of the community garden allotments available in Dublin city and how to take the best use of them once taking part.

Add an image of the finished site here [amiresponsive](https://ui.dev/amiresponsive) on all device sizes. Test: (update with finihed site)

![City Gardens](docs/city-gardens-mockup-test.png)

Link to the live site here: https://zest-studi-o.github.io/P01-Allotment-gardens/

Add optional [shields.io](https://shields.io) badges to README.

# Table of contents

- [User Experience (UX)](#User-Experience-UX)

  - [Initial Discussion](#Initial-Discussion)
  - [User Stories](#User-Stories)

- [Design](#Design)

  - [Colour Scheme](#Colour-Scheme)
  - [Typography](#Typography)
  - [Imagery](#Imagery)
  - [Wireframes](#Wireframes)
  - [Features](#Features)
  - [Accessibility](#Accessibility)

- [Technologies Used](#Technologies-Used)

  - [Languages Used](#Languages-Used)
  - [Frameworks, Libraries & Programs Used](#Frameworks-Libraries-&-Programs-Used)

- [Deployment & Local Development](#Deployment-&-Local-Development)

  - [Deployment](#Deployment)
  - [Local Development](#Local-Development)
    - [How to Fork](#How-to-Fork)
    - [How to Clone](#How-to-Clone)

- [Testing](#Testing)
  - [Bugs](#Bugs)
  - [Known Bugs](#known-Bugs)
- [Credits](#Credits)
  - [Content](#Content)
  - [Media](#Media)
  - [Acknowledgments](#Acknowledgments)

---

## User Experience (UX)

### Initial Discussion

City Gardens is an initiative created in conjunction with local communities and Dublin City Council, the aim of this initiative is to encourage people who live in the inner city, particuraly in apartment and flat complexes to spend some time outside gardening and socialising using public lands divided into allotments which can be used by members of the public.

People can take an allotment for the purpose of gardening and producing fruit and vegetables, these are located in different parts of Dublin city, to allow people from different suburbs to participate in the initiative.

They is a small fee to be able to join and members need to optimally mantain the plot, optionally fruit and veg can be produced, and 10% of this produce can be sold at local markets so the community gardens can have further social events, core funding is provided by Dublin City Hall and the fees. When first signing up people recieve a free starter pack including a gardening and horticulture book to make the best use of the land.

The websites purpose is to highlight the avilability of the service, where the alotments are located and offer a facility for users to find information such as contact details, growing guides and gardening tips. The alotments are available for people of all ages and skillsets.

#### Key information for the site

- What is City Gardens and what does it offer.
- What is currently going on in the community garden.
- How to take part in the inititative and become a member.
- A way of contacting City Gardens and enquire or provide suggestions.
- Where to find the locations for the allotment.

### User Stories

#### User Goals

- As a user I want to have the site displayed clearly in different devices.
- As a user I want to find information on what is City Gardens and how to participate.
- As a user I want to show exactly where the gardens are located.
- As a user I want to be able to contact City Gardens with any queries or suggestions.

#### First Time Visitor Goals

- As a fisrt time visitor I want to know what City Gardens is and how to participate.
- As a fisrt time visitor I want to find the locations of the allotments.
- As a fisrt time visitor I want to be able to find their contact details.
- As a fisrt time visitor I want to navigate the site easily on all my devices.
- As a fisrt time visitor I want to see the results of the produce with videos and photos.

#### Returning Visitor Goals

- As a returning visitor I want to find images and videos of the allotments.
- As a returning visitor I want to be able to easily contact City Gardens with further questions I might have.

#### Frequent Visitor Goals

- As a frequent visitor I want to see images of the people that participate in City Gardens.

---

## Design

### Colour Scheme

![Eggplant palette](docs/palette-eggplant.png)

The colour palette selected uses a mix of tones based on an eggplant theme, it uses a very trendy bright green colour combined with shades of greys and blacks, to complement the eggplant colour which is used in the imagery. The colours have high contrast and light colours are used gainst dark background colours and vice versa.
The final colour palette was created using the [Coolors](https://coolors.co/) website.
Some other alternatives and shades based on the selected palette were:
[Tomato vine palette](docs/palette-tomato-vine.png)
[Violet field palette](docs/palette-violet-field.png)

The final colour palette was slighly altered after testing validator suggestions of improving the contrast and changed the header and footer for a slighly darker hue colour.

There was some colour exploration using [Adobe Colour Wheel](https://color.adobe.com/create/color-wheel) website, some colours were brought to Coolors website extracted from imagery planned to use on the site to further explore the visual possibilities.

### Typography

The fonts were taken from Google Fonts:

- Karla is used for headings and subheadings on the site. It is a serif font that combines well with the body copy font, which is sans-serif, serif and sans-serif fonts offer good contrast.

- Monstserrat is used for the body text on the site. It is a sans-serif font with good readability optimal to use for web.

- Lobster is used on the logo with a slight drop shadow for better visibility. It is a display cursive font. The logo leaf icon was taken from font awsome and combined with this font.

### Imagery

The images are taken from the royalty free sites credited [here](#Credits).

### Wireframes

Wireframes for desktop, tablet and mobile versions as follows:

![Home Page Wireframe](docs/home.png)

![Locations Wireframe](docs/locations.png)

![Contact Us Wireframe](docs/contact.png)

### Features

#### Existing Features

This website has three pages that can be accessed from the navigation menu (home page, locations page, and contact us page) it also has a thank you page that can be accessed when sending a form.

- All pages have:
- A navigation bar that is responsive and adjusts depending on the screen sizes via media queries.
- A footer with links to social media.

- Home Page.

  - The Sites title.
    This redirects the user to the home page by clicking on the logo.
  - Hero section.
    This shows an image of a member of City Gardens in the allotments.
  - About us section.
    This explains briefly to the user what is City Gardens, and the reasons to have an allotment
  - Video section.
    This links to videos on relevant content such as how is it having an allotment, or harvesting the produce.

- Locations page.
  - Cards with images of the locations.
  - Information with address and contact details and link to a map.

- Gallery.
  - Image gallery.
    This section has a gallery of images from participants and the allotments themselves.

- Contact us page.
  - Form.
    This section has a contact form in which the user can further enquire about how to join or any other queries they might have. The form has input fields for name, surname, email address, and a box in which they can include their question, there is a contact us button call to action, the form uses form validation, so the user must fill up all the information to be able to submit.

- Thank you page.
  - Once the form is succesfully submited the page thanks and redirects the user to the home page in 10s

### Features Left to Implement

Add some animations.

### Accessibility

It is important to have a website that is accessibility friendly, this objective was achivieved by:

- Ensuring that images have an alt atribute.
- Using aria labels.
- Using semantic html.
- Making sure that background and foreground colours have high contracts, after an error returned in the nav bar by the lighthouse validator the darkness background colour was inscreased in order to contrast higher with the white color applied to the font, the logo also has a drop shadow to enhance visibility and the clickable menu for mobile screens uses a visible font size.
- Using a sans serif font recommended for web which are easy to read.
- Adding titles to iframes.

---

## Technologies Used

### Languages Used

HTML and CSS were used to create this website.

### Frameworks, Libraries & Programs Used

Balsamiq - Used to create wireframes.

Git - For version control.

Github - To save and store the files for the website.

Gitpod - To write, edit and save code.

Google Fonts - To import fonts for the wesite.

Font Awesome - To add icons to the website.

[Tiny PNG](https://tinypng.com/) To quickly compress imagery.

[Convertio]https://convertio.co/ To convert to webp format.

[Photoshop](https://www.adobe.com/ie/creativecloud/) To edit, resize, crop to size and web optimise imagery.

---

## Deployment & Local Development

### Deployment

Github Pages was used to deploy the live website. The instructions to achieve this are below:

1. Log in (or sign up) to Github.
2. Find the repository for this project, P01-Allotment-garden.
3. Click on the Settings link.
4. Click on the Pages link in the left hand side navigation bar.
5. In the Source section, choose main from the drop down select branch menu. Select Root from the drop down select folder menu.
6. Click Save. Your live Github Pages site is now deployed at the URL shown.

### Local Development

#### How to Fork

To fork the P01-Allotment-gardens repository:

1. Log in (or sign up) to Github.
2. Go to the repository for this project, Zest-studi-o/P01-Allotment-gardens.
3. Click the Fork button in the top right corner.

#### How to Clone

To clone the P01-Allotment-gardens repository:

1. Log in (or sign up) to GitHub.
2. Go to the repository for this project, Zest-studi-o/P01-Allotment-gardens.
3. Click on the code button, select whether you would like to clone with HTTPS, SSH or GitHub CLI and copy the link shown.
4. Open the terminal in your code editor and change the current working directory to the location you want to use for the cloned directory.
5. Type 'git clone' into the terminal and then paste the link you copied in step 3. Press enter.

---

## Testing

Please refer to [TESTING.md](TESTING.md) file for all testing carried out.

### Bugs

| ID  | CLASS | FEATURE          | DESCRIPTION                                                                          | STEPS TO REPRODUCE                                                                                                                                                           | ACTUAL RESULT                                                                                                                                  | EXPECTED RESULT                                                            | ACTION                                                                                                        | STATUS |
| --- | ----- | ---------------- | ------------------------------------------------------------------------------------ | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------------------------------------------- | -------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------- | ------ |
| 1   | A     | Footer           | Footer not aligning at the bottom                                                    | Go to the website > click on home> Observe the issue with the white space in the footer                                                                                      | Footer correctly positioned                                                                                                                    | Position absolute and work with padding bottom                             | Position absolute and work with padding bottom                                                                | FIXED  |
| 2   | A     | Video section    | Text going to the back of the videos and being unreadable                            | The text is hidden behind the videos                                                                                                                                         | Go to the website> click on home> Reduce screensize to table or mobile version> Observe the issue with the text being hidden behind the videos | Videos and text correctly distributed and centered for all screen sizes    | Add pagging to the videos when they stack one on top of the other for medium and small screen sizes           | FIXED  |
| 3   | A     | Video section    | Issue with media queries; the right video does not accept the style.                 | Go to the website > click on home> Scroll to the video section> Observe the issue with video right not being responsive                                                      | All videos fully responsive                                                                                                                    | Video on the right not responsive                                          | Fixed the typo on "right"                                                                                     | FIXED  |
| 4   | A     | Nav bar          | Nav bar background not taking the grey background colour and floating on a white gap | The nav bar does not display correctly and some content is cropped or with a white gap in certain screen sizes                                                               | The nav bar does not display correctly and some content is cropped or with a white gap in certain screen sizes                                 | The nav bar displays correctly                                             | Fixed by adjusting specified heights, margin and padding on the header element                                | FIXED  |
| 5   | A     | Hero image       | Issue with hero image not centered when reducing screen size                         | Go to the website > click on home> Open dev tools> Select a small screen eg. IPhone12 Pro> Observe the issue with the hero image alignment                                   | The hero image is not aligned                                                                                                                  | The hero image should be correctly aligned for all screen sizes            | Edit image size and add adjusted ones with media queries                                                      | FIXED  |
| 6   | B     | Footer           | Footer after a long gap for small screens                                            | Go to the website > click on contact> Open dev tools> Select a small screen eg. IPhone12 Pro> Observe the issue with the gap not filled with content after the submit button | Some negative spacing after the submit button                                                                                                  | All the content is centered with no extra negative spacing at the bottom   | Delete especified height in one of the media queries                                                          | FIXED  |
| 8   | C     | About us section | Misalignment of the bulleted list in about us section                                | Go to the website > click on home> Swap to different screen sizes with dev tools> Observe the issue with the bulleted list misalligned                                       | The list is not correctly aligned for certain screen sizes                                                                                     | The list is correctly aligned for all screen sizes                         | Worked with padding for the section and added font awsome for bullet points                                   | FIXED  |
| 9   | C     | Locations        | Slight misalignment of the cards group in location page                              | Go to the website > click on locations in desktop view> Observe the issue with the alignment                                                                                 | The cards are not correctly aligned for destop screen sizes                                                                                    | The cards appear aligned and centered                                      | Use of the row css property                                                                                   | FIXED  |
| 10  | A     | Locations        | Issue when reducing the screen to achieve 2 rows centered in locations tab           | Go to the website > click on locations> Open dev tools and select a tablet size> Observe the issue with one of the cards floating down and leaving a white space instead     | Three column cards for desktop, two column cards for tablet, one column card for phone                                                         | Use of the row css property                                                | Use of the row css property                                                                                   | FIXED  |
| 11  | B     | Nav bar          | Active link on the nav menu not working                                              | Go to the website > click on any page eg. home> Observe the issue with the active style not taking effect                                                                    | The active page is not highlighted                                                                                                             | The active page is higlighted to indicate the user what page are they on   | Added !important tab to the css                                                                               | FIXED  |
| 12  | A     | Nav bar          | Wrong order of the listed items when seeing the page in small screens                | Go to the webise> Click on dev tools and select a small mobile screen size> Observe the issue with the listed items in the nav bar being in the wrong order                  | The nav bar displays the items in a not user friendly manner contact, locations, home                                                          | The nav bar will display home, locations and contact                       | Change order in html of the elements, then float left menu li and float right menu for larger screens         | FIXED  |
| 13  | A     | Form             | Some of the radio buttons float to the next line if the screen size it is small      | Go to the website> click on the form page> open dev tools> select a small screen e.g. Pixel 5> Observe the issue with the radio button input not being beside its label      | The radio button input and its label it is not aligned in small screens                                                                        | Ensure that radio button labels and input are aligned for all screen sizes | Add a span to the label and radio button, assign a class and then apply display block for small screens to it | FIXED  |

### known Bugs

There are no remaining known bugs, all of them have been fixed.

---

## Credits

### Content

- [Sdcc](https://www.sdcc.ie/en/services/sport-and-recreation/allotments/#:~:text=The%20annual%20rent%20ranges%20from,on%20the%20size%20of%20plot.)
- [Dublin City Council](https://www.dublincity.ie/residential/improving-my-community/allotments-and-community-gardens)

### Imagery, vectors & videos

- [Pexels - Andrea Piacquadio - woman in blue planting veg](https://www.pexels.com/es-es/foto/foto-de-mujer-plantando-verduras-1023397/)
- [Pexels - Andrea Piacquadio - woman in blue and wheelbarrow](https://www.pexels.com/es-es/foto/foto-de-mujer-sosteniendo-carretilla-1023404/)
- [Freepik - Cookie Studio](https://www.freepik.com/free-photo/rural-morning-close-up-beautiful-bearded-caucasian-male-farmer-blue-t-shirt-black-pants-smiling-working-farm-picking-crop-doing-favorite-job_9696954.htm#from_view=detail_alsolike)
- [Freepik - Prostooleh - Woman working in the garden](https://www.freepik.com/free-photo/woman-hat-working-garden_9659554.htm)
- [Freepik - Prostooleh - Senior holding veg basket](https://www.freepik.com/free-photo/close-up-old-farmer-holding-basket-vegetables-man-is-standing-garden-senior-black-apron_10065490.htm)
- [Freepik - Couple working in the garden](https://www.freepik.com/free-photo/overhead-view-male-female-gardener-working-vegetable-garden_4636256.htm)
- [Unsplash - Elias Morr - Green and purple veg in a bowl](https://unsplash.com/es/fotos/0bA5dqPyLgg)
- [Freepik - Veggies with eggplant](https://www.freepik.com/free-photo/top-view-veggies-with-eggplant_9402961.htm)
- [Pexels - Mariam Antadze](https://www.pexels.com/es-es/foto/patatas-en-velo-transparente-en-campo-5913196/)
- [Youtube - Growing My Own Fruit and Veg - A Visit to my Allotment](https://www.youtube.com/watch?v=Aku-AGbwejw)
- [Youtube - September Allotment Harvest - Homegrown Garden](https://www.youtube.com/watch?v=FbbfeHShIk0)
- [Pexels - July Allotment Tour - Relaxed walk round the fruit and veg](https://www.youtube.com/watch?v=dlxsQxmwV5k)
- [Flaticon - Gardening](https://www.flaticon.com/free-icon/gardening_1973742?term=garden&page=1&position=1&origin=search&related_id=1973742)
- [Allotment garden](https://pixabay.com/photos/allotment-garden-garden-flower-beds-1059/)
- [Organic Aubergines](https://www.freepik.com/free-photo/close-up-fresh-organic-eggplant-garden_11176085.htm#query=aubergine%20garden&position=1&from_view=search&track=ais)

### Reference material. Tutorials & articles

- [Love Running Walkthrough project readme template](https://github.com/Code-Institute-Solutions/readme-template)
- [Bully Book Club readme example](https://github.com/kera-cudmore/Bully-Book-Club/blob/main/README.md)
- [kera Cudmore readme examples](https://github.com/kera-cudmore/readme-examples)
- [kera Cudmore readme template](https://github.com/kera-cudmore/readme-examples/blob/main/milestone1-readme.md)
- [kera Cudmore - The Quiz Arms](https://github.com/kera-cudmore/TheQuizArms)
- [Creating your first readme](https://www.youtube.com/watch?v=XbYJ4VlhSnY&ab_channel=CodeInstitute)
- [How to create a table of contents in markdown](https://www.youtube.com/watch?v=6V5yaVhK_hE&ab_channel=LinuxWorkshop)
- [Markdown table generator](https://www.tablesgenerator.com/markdown_tables#)
- [Stackoverflow: create table of contents](https://stackoverflow.com/questions/11948245/markdown-to-create-pages-and-table-of-contents)
- [Responsive iframe](https://techstacker.com/how-to-responsive-youtube-videos/)
- [Correct embed url](https://total.wpexplorer.com/docs/get-embed-urllink-youtube-video/)
- [Header image sizing guide](https://www.lauraleeflores.com/blog/header-image-sizing-guide)
- [Ultimate Guide to Hero Images](https://blog.hubspot.com/marketing/hero-image#:~:text=The%20ideal%20size%20for%20a,size%20up%20to%201%2C800%20pixels.)
- [Best image size for website](https://tiny-img.com/blog/best-image-size-for-website/)
- [W3 schools](https://www.w3schools.com/)
- [How to keep your footer where it belongs?](https://www.freecodecamp.org/news/how-to-keep-your-footer-where-it-belongs-59c6aa05c59c/)
- [Remove white space from footer](https://stackoverflow.com/questions/34188161/remove-white-space-below-footer)
- [Color hexa](https://www.colorhexa.com/)
- [Styling Placeholder Text with CSS](https://www.samanthaming.com/tidbits/57-styling-css-placeholder/)
- [How to center a HTML form in CSS](https://devpractical.com/center-form-in-html-css/)
- [CSS cards](https://www.w3schools.com/howto/howto_css_cards.asp)
- [Column cards](https://www.w3schools.com/howto/howto_css_column_cards.asp)
- [Flexbox](https://flexbox.malven.co/)
- [Grids](https://grid.malven.co/)
- [Get started with grid WITHOUT being overwhelmed](https://www.youtube.com/watch?v=8QSqwbSztnA&t=1s&ab_channel=KevinPowell)
- [How to hightligh text in CSS](https://alvarotrigo.com/blog/css-highlight-text/)
- [Highlight Text CSS: 7 Cool CSS Highlight Text Effects](https://www.coding-dude.com/wp/css/highlight-text-css/)
- [How to Add Phone Number Validation in HTML: The Essential Guide](https://www.youtube.com/watch?v=fb4QcrpQKUM)
- [Regex: Validate an Irish mobile phone number](https://stackoverflow.com/questions/33061964/validate-an-irish-mobile-phone-number)
- [Bullet points using font awsome](https://hollypryce.com/font-awesome-bullet-points/)
- [Stackoverflow - Font awsome icon bullet points](https://stackoverflow.com/questions/12468359/using-font-awesome-icon-for-bullet-points-with-a-single-list-item-element)
- [Drop shadow for pngs in CSS](https://www.w3docs.com/snippets/css/how-to-create-a-drop-shadow-for-png-image.html)
  https://www.birme.net/?auto_height=true&image_format=webp
- [Grid Gallery - Free code camp](https://www.freecodecamp.org/news/how-to-create-an-image-gallery-with-css-grid-e0f0fd666a5c/)
- [A Complete Guide to CSS Grid](https://css-tricks.com/snippets/css/complete-guide-grid/)

### Acknowledgments

- [Derek MCAuley](https://github.com/derekmcauley7), my Code Institute Mentor.
- Tutor support at Code Institute.
- Alan, course facilitator, for the advice.
- Jarek Bonk, cohort colleague, for his help with the grid when I ran out of tutor hours.
- Paul Treggiden, project-millestone-1 slack member, for his help with fixing bug 12.
