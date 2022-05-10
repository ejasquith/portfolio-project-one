# Kendal Chess Club

# Site Overview

The chess community in Cumbria and the South Lakes is thriving, but poorly designed and rarely updated websites may not reflect this to the uninitiated.  
Especially given the massive uptick in interest in and popularity of chess since the pandemic and the release of The Queen's Gambit on Netflix, local clubs need to be keeping up with current UX and web design principles to attract members, especially of a younger generation.  
This site aims to introduce prospective members to the Kendal Chess Club, offering information about meetings, venues, and contact details, as well as providing relevant information to current members, such as news and events.

![Screenshot of the site on ami.responsivedesign.is](docs/images/screenshots/am-i-responsive-screenshot.png)

# Table of Contents

[to implement]

# Planning Stage

## Stakeholder Interviews  

In order to inform my decisions in the planning stages of this project, I conducted interviews with a number of potential stakeholders and users. These can be found in [INTERVIEWS.md](docs/INTERVIEWS.md)

## Target Audiences

The first stage in planning this project was to identify the stakeholders - those being, the site owner and end users of the site. End users can further be split up into three categories: 
- Users who do not play chess but are interested in starting;
- Users who do play chess and are looking for a club to play with (either after moving to a new location or having played solely online and wanting to experience "over-the-board" chess for the first time);
- Users who are an active member of the club.  

The demographic of these users is extremely broad - anyone from 12-70+ can (and does) attend the club, and members are a mix of men and women. Therefore, the site has to have wide appeal.  

## User Stories

- As someone new to chess, I want to learn the basic rules of the game. 
- As a prospective member, I want to find out when and where the club meets.
- As a prospective member, I want to contact the club organisers.
- As a parent of a young prospective member, I want to know the club's child safety guidelines and policies.
- As a current member, I want to be updated on any club news.
- As a current member, I want to see the status of any ongoing events or competitions.
- As a user, I want to be able to find relevant information quickly and without hassle. 
- As a user, I want to learn about the history of the club.   

## Site Aims

- To provide information on the club and its meetings.
- To allow users to keep up with club news and events.
- To allow users to contact club organisers quickly and easily.
- To educate new players on the rules of chess.
- To showcase the club's history and unique offerings.

## How This Will Be Achieved

- The home page will provide a brief introduction to the club and its meeting times and venue.
- There will be a dedicated news & events page, detailing news from the club and the wider chess world.
- There will be a contact form page where users can provide personal details and a message for the administrators.
    - There will also be details on the club managements' contact details.
- There will be a "how to play" page, which will include the basic rules of chess and other information for beginners.
- There will be a dedicated about us page, which will expand on the introduction on the home page and include some of the club's history.

## Out-of-Scope Features

There are a number of features that would ideally be added to the site but at present are out of scope, either due to knowledge gaps or time restrictions.

In particular, the implementation of a blog or news feed (and an admin login to manage the feed) - this is a big part of the site owner's goals for the site, but without knowledge of backend languages and frameworks (eg. Python and Django), this is currently impossible. However, I can simulate a news feed by creating static content and pages for the purposes of this project.

## Wireframes

In order to organise my thoughts and provide a basic design scheme to work with, I created a number of wireframe diagrams.  

### Mobile wireframes
![Home Page wireframe for mobile](docs/images/wireframes/homepage-mobile.png)

### Desktop wireframes
![Home Page wireframe for desktop](docs/images/wireframes/homepage-desktop.png)

## Colour Palette

For the colour palette of my site, I decided to stick with white, black, and greys for a modern, minimalist feel (which also reflects the obvious white/black theme of chess), while relying on hero images to provide a pop of colour. To lessen the harshness of the palette, I used the off-white #FAFAFA and the off-black #0E0E0E.  
I then ran these colours through [Contrast Grid](https://contrast-grid.eightshapes.com/?version=1.1.0&background-colors=&foreground-colors=%23FAFAFA%2C%20Off%20White%0D%0A%23CCCCCC%2C%20Light%20Grey%0D%0A%235E5E5E%2C%20Medium%20Grey%0D%0A%232B2B2B%2C%20Dark%20Grey%0D%0A%230E0E0E%2C%20Off%20Black&es-color-form__tile-size=compact&es-color-form__show-contrast=aaa&es-color-form__show-contrast=aa&es-color-form__show-contrast=aa18&es-color-form__show-contrast=dnp) to ensure that the site has sufficient contrast for accessibility.

![A colour palette consisting of white, black, and greys](docs/images/colour-palette.png)
![A grid showing the contrast between the above colours](docs/images/contrast-grid.png)

## Fonts

Taking inspiration from the [St. Louis Chess Club](https://saintlouischessclub.org/), I have decided to use a mixture of serif and sans-serif fonts in my design.  
Headings will use the Merriweather font, while paragraph text will use Merriweather Sans. These two typefaces have been specifically designed to complement each other well.

# Development Stage

## Deviations from Planning

- After many hours of research, I decided to scrap the idea of a dedicated "about us" page. A lot of the history of the club is unfortunately completely lost, and there simply wasn't enough information to fill a whole page - instead, I expanded on the about section on the home page slightly.

- I largely followed my wireframe diagrams, with a few small changes.
    - I decided to implement a hamburger menu on small screens to save screen real estate.
    - I removed the logo from the header, because I couldn't find an appropriate image to use and don't have the skills to create one myself.
        - For a future release, I may have a logo custom-made.

## Libraries

- The only external library used in this project was [Bootstrap](https://getbootstrap.com/), which I used only to create a dropdown hamburger nav menu, which was impossible to do using only HTML and CSS.
    - Bootstrap also included some basic global styling rules, such as line breaks between \<p> tags.

# Credits

- Screenshots in [COMPETITORS.md](docs/COMPETITORS.md) taken from: 
    - [https://saintlouischessclub.org/](https://saintlouischessclub.org/) 
    - [https://www.glcc.org.uk/](https://www.glcc.org.uk/)
- Colour palette generated with [Coolors](https://coolors.co/?home)
- Fonts sourced from [Google Fonts](https://fonts.google.com/)
- Icons from [Font Awesome](https://fontawesome.com/)
- Special thanks to Jonathan, Hana, and Tim for agreeing to be interviewed.