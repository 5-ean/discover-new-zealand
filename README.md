
# **DISCOVER NEW ZEALAND** 
---
# INTRODUCTION
---
>
>This project sets out to engage with users on a multitude of devices and encourages them to discover New Zealand. Using UX principles to create a responsive and attractive website, that will increase exposer of the region. Ultimately leading to increased website traffic and an uptake in enquiries satisfying the business objective stated below.
>python3 -m http.server

## CONTENT:
> ## - [UX](#ux-deployment)
> ## - [FEATURES](#features)
> ## - [TECHNOLOGIES USED](#technologies-used)
> ## - [TESTING](#testing)
> ## - [DEPLOYMENT](#deployment)
> ## - [CREDITS](#credits)
---
# UX DEPLOYMENT
---
### **STRATEGY, SCOPE & STRUCTURE**
**Business Objective:**
>The **business objective** is to increase interest in visiting New Zealand through the [*Discover New Zealand*](https://5-ean.github.io/discover-new-zealand/) webiste. The objective is focused on B2C (business to customer) sales, so it will be a more emotive driven experience. Using bold visuals and accessible language will ensure the project reaches the largest possible user base.

**Target User:** 
> * Users curious about New Zealand
> * Users of all age ranges (appropirate content)
> * English speakers & Users with English as second language (minimal wording/complexity to aid accessibility for all)
> * Users from all over the globe with varying internet connection speeds (website optimised to reduce loading times where possible)
> * Users of all platforms (mobile first design)

**User Stories:**
> 1. "As a user who has never been to New Zealand, is the site going to provide relevant information? Will it be easy to understand? Can I see topics that interest me quickly…..or will I have to read pages of information to find out? I don’t want to spend a long time on the site, but I want my experience to be rewarding."
>
> 2. "As a mobile dependent user of this website, I want to have a polished and engaging experience on the website even though I do not have access to a desktop/laptop."
>
> 3. "As a visual user of the website, I want high quality media displayed on the site for my viewing pleasure. I find images & videos more appealing than lots of text."
>
> 4. "As an interested user of the website, I want to send questions if I require more information….is their reciprocation? Can you send me additional information at my request? This will provide me with the extra details to make an informed decision about visiting New Zealand."
>
> 5. "As a less technical user I want an easy to navigate website, over-complicated designs will put me off exploring the site. Which will keep me for recommending and returning to the website in the future."  

**Addressing User Stories & Business Objective**  
> * Home page: basic requirement for all sites, will “sell” experience to user and provide eye catching hero image (addressing business objective).
> * About page: addressing user story 1.
> * Gallery page: addressing user story 3.
> * Get In Touch page: addressing user stories 4.
> * Use of Bootstrap: addressing user stories 2 & 5.

**Project Content** 
>Within [Balsamiq](https://balsamiq.com/) a [table](https://github.com/5-ean/discover-new-zealand/blob/563bcd72d188b530b0f83b66682e1105c0e8078d/assets/ux_assets/images/content-table.pdf) of possible content was created to populate the project. A **wireframe site map** was then created to structure the content and project as a whole.
>
> The [Wireframe](https://github.com/5-ean/discover-new-zealand/blob/7f9d3df776b7bd97d4fdb0b2986230bd2601a7bd/assets/ux_assets/images/sitemap-wireframe.pdf) site map is a rough guide. Some content has been removed, specifically *(content)FAQ's*, *(content)videos* and *(content)links through to booking* because it lacks importance or is not viable at this time. 
 
### **SKELETON & SURFACE**

>The remaining features and content kept in make up the **minimal viable product** at this time. The **MVP** *(minimal viable product)* consists of the [Home](https://github.com/5-ean/discover-new-zealand/blob/7f9d3df776b7bd97d4fdb0b2986230bd2601a7bd/assets/ux_assets/images/index.html-wireframe.pdf) page, [About](https://github.com/5-ean/discover-new-zealand/blob/7f9d3df776b7bd97d4fdb0b2986230bd2601a7bd/assets/ux_assets/images/about.html-wireframe.pdf), [Gallery](https://github.com/5-ean/discover-new-zealand/blob/7f9d3df776b7bd97d4fdb0b2986230bd2601a7bd/assets/ux_assets/images/gallery.html-wireframe.pdf) & [Get In Touch](https://github.com/5-ean/discover-new-zealand/blob/7f9d3df776b7bd97d4fdb0b2986230bd2601a7bd/assets/ux_assets/images/get-in-touch.html-wireframe.pdf) pages respectively.

**Colour Scheme & Background**
> The pictures used for the project were of natural landscapes with high ratios of green, blue, white, and brown colouring. Therefore, the stylistic choice was to use off white/grey colouring with opacity for the nav header & footer elements. This along with subtle, thin borders around content elements gave a natural feel to the site overall.

**Buttons & Links**

>To aid usability links and buttons followed the same style. Notably changing from black to white as a hover element. This is a sharp contrast and a nod to New Zealand Sports and Culture as white and black have long been the colour scheme for the country in many regards.

---
# FEATURES
---
**Home Page / Navigation & Footer Elements -**
> * Bootstrap based Nav header, with collapse function in mobile view.
> * Social links in footer element.
>
>![Image](assets/ux_assets/images/screenshots/index-mobile.png) ![Image](assets/ux_assets/images/screenshots/index-mobile-nav-active.png) ![Image](assets/ux_assets/images/screenshots/index-desktop.png) 

**About Page / Information Content -** 
> * Detailed information section, with Learn more button links to relavent wiki pages for additional information.
>
>![Image](assets/ux_assets/images/screenshots/about-mobile.png) ![Image](assets/ux_assets/images/screenshots/about-desktop.png)

**Gallery Page / Google Maps Location Links -**
> * Three images contained in a bootstrap carousel, caption including breif description & Google maps link to picture location.
>
>![Image](assets/ux_assets/images/screenshots/gallery-mobile.png) ![Image](assets/ux_assets/images/screenshots/gallery-desktop.png)

**Get In Touch Page / User Form submission -**
> * Active user feedback on form submittion status, helpful hints and directions to aid the user.
>
>![Image](assets/ux_assets/images/screenshots/get-in-touch-mobile.png) ![Image](assets/ux_assets/images/screenshots/get-in-touch-desktop.png)
---
# TECHNOLOGIES USED
---
> * [HTML5](https://html.com/html5/) : The markup language used for structuring and presenting content on the Discover New Zealand website.
> * [CSS3](https://html.com/css/) : The language that defines the presentation of a website Discover New Zealand.
> * [BOOTSTRAP V4.6](https://getbootstrap.com/docs/4.6/getting-started/introduction/) : Used in the project to create a mobile-first designed website. It is the most popular front-end open source toolkit.
> * [FONT AWESOME](https://fontawesome.com/) : Used in the project to provide vector icons and social media logos.
> * [GOOGLE FONTS](https://fonts.google.com/) : Provided typography to the project. It is a robust collection of open source designer web fonts.
> * [TINY PNG](https://tinypng.com/) : Used to reduce the file size of PNG files in the project.
> * [BALSAMIQ](https://balsamiq.com/) : Used to create a table and multiple wireframes for the project. Licence provided by [Code Institute](https://codeinstitute.net/).
> * [GITPOD](https://www.gitpod.io/) : The interaction development environment (IDE) used to write the projects code.
> * [GITHUB](https://github.com/) : Provides hosting for software development version control using Git. The host of this project.
> * [GIT](https://git-scm.com/) : Git is a free and open source distributed version control system.
---
# TESTING
---
[**W3C Validator :**](https://validator.w3.org/)

> * Index.html - ![Image](assets/ux_assets/images/testing-images/index.html-w3c-validator.png)

> * about.html - ![Image](assets/ux_assets/images/testing-images/about.html-w3c-validator.png)

> * gallery.html - ![Image](assets/ux_assets/images/testing-images/gallery.html-w3c-validator.png) 

> * get-in-touch.html - ![Image](assets/ux_assets/images/testing-images/get-in-touch.html-w3c-validator.png)

[**CSS Validator :**](https://jigsaw.w3.org/css-validator/)

> * style.css - ![Image](assets/ux_assets/images/testing-images/style.css-jigsaw-validator.png)

[**Google Lighthouse :**](https://developers.google.com/web/tools/lighthouse/)

>Index.html - 
> * [Mobile Test](assets/ux_assets/images/lighthouse-images/index-mobile.pdf)
> * [Desktop Test](assets/ux_assets/images/lighthouse-images/index-desktop.pdf)

>About.html - 
> * []()
> * []()
---
# DEPLOYMENT
---
**How I Deploy The Project To GitHub:**
> 1. Log on to [GitHub](https://github.com/), clicked the repository named [discover-new-zealand](https://github.com/5-ean/discover-new-zealand).
> 2. Select the settings tab and scroll to the section headed GitHub Pages.
> 3. In the sub-heading of Source, select the master branch and then save.
> 4. The site is now deployed and a live [link](https://5-ean.github.io/discover-new-zealand/) is given.

**How To Deploy Locally:**
> 1. Log on to [GitHub](https://github.com/), clicked the repository named [discover-new-zealand](https://github.com/5-ean/discover-new-zealand).
> 2. Select the dropdown tab "Code" and choose Download ZIP.
> 3. Un-zip files and it's ready to use on your local environment.
---
# CREDITS
---





