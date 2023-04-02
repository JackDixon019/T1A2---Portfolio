# T1A2 - Portfolio

## Links
[Github repo is available here](https://github.com/JackDixon019/T1A2---Portfolio)

[Website is available here](https://jackdixonportfolio.netlify.app/pages/about.html)

[Presentation is available here]()

## About
This website was developed as a portfolio to showcase myself and my skills to potential employers in the web development industry.
At current, due to my skills being limited, it features only a few webpages comprised of HTML styled by CSS that was written in SCSS. It was deployed via [netlify](https://www.netlify.com/).
It includes 4 pages, each styled with a responsive layout to facilitate viewing on a myriad of devices.


## Pages
This section contains the pages of the website. 
As per the assignment, the pages included will be:
- Home
- About
- Blog
- Contact

## Style
This section contains the stylesheets, default values, and components for the site. 

There are stylesheets for each page, as well as an index partial SCSS stylesheet which is called in each page's SCSS.

- _Index
    * This establishes the default styling for each page, and is imported into each page's SCSS/CSS file.
    * Establishes styling for most shared elements such as the logo, the hamburger menu, the html scroll, the background image, and titles.

The components currently consist of:
- _Header
    * Each page on the site utilises the header
    * Contains the logo of the site which links back to the homepage, as well as a navigation menu containing links to each other page on the site: About, Blog, and Contact
    * The header component features a hamburger menu for navigation that is accesible on smaller devices.
    * This feature utilises a hidden checkbox to display/hide the pop-in menu using the pseudoclass :checked + .hamburger

The defaults currently consist of:
- Colour 
    * This includes the colours used to maintain a consistent styling throughout the website
    * These colours were chosen based on the background image

- Breakpoint
    * This allows elements to change styling based on screen sizes

- Fonts
    * Allows consistent font usage throughout the site

There is also one stylesheet for each page, as above.
- Home.scss/css
    * This page doesn't really feature anything amazing, just the header, a title, and a textbox, serving instead as a basic landing page for the site. 
![Home page screenshot](./docs/home.png)

- About.scss/css
    * This page features 2 articles, one about me personally, and one about my professional history.
    * The about me article contains a textbox with info, and a picture of myself
    * My professional history section contains a textbox with a list of previous roles, and a link to my (mockup) resume
    * On tablets + phones, this page is presented as a column, rather than in rows as on desktop.
![About page screenshot](./docs/about.png)
![About page screenhot 2](./docs/about-2.png)
![About page phone/tablet view](./docs/about-phone.png)

- Blog.scss/css
    * Notably includes blog posts that scale in size upon focus, allowing for the blog post page containing a list of all blog posts to double as the blog pages themselves. 
    * On tablets, the layout of the page is similar to desktop, although I only included 2 articles per row, rather than 3.
    * On mobile, the layout of the page is a singular column of articles that expand on focus, but don't re-order as they do on tablet/desktop. I found that on mobiles, where it was easy to scroll down the page further, it was very confusing when the article I opened would jump to the top, forcing me to scroll back up (sometimes pretty far) in order to read it. 
    * I originally had an animation upon focus, but found that when used in combination with flexbox, it would lead to a bit of jank when the size transition was taking place. Could potentially have been fixed using grid instead, but when I tried this it broke other things, so I decided that the time:effort ratio wasn't worth it over just disabling the animation. I might revisit this in the future.
    * This animation is preserved on mobile screens, due to only having one article per "row"
![Blog page screenshot](./docs/blog.png)
![Blog article expanded view](./docs/blog-expanded.png)
![Blog page tablet view](./docs/blog-tablet.png)
![Blog page phone view](./docs/blog-phone.png)

- Contact.scss/css
    * This page is also pretty bare-boned, containing only a textbox with a little blurb, and the logos of linkedin and github
    * The logos were obtained using [fontawesome](https://fontawesome.com/), and link to linkedin and github respectively.
    * I debated having this content in a footer instead, but I'm not a huge fan of footers and think they take up screen real estate, especially on smaller devices. On larger sites I think they can be useful for providing legal info + a sitemap.
![Contact page screenshot](./docs/contact.png)


## Files
This contains a pdf file of my mock resume. It is linked to in the "About" page.

## Images
This folder contains images used in the blog posts and about page, as well as the background image. 

Also includes a gif from the tv show "The Simpsons" which I was using as a placeholder image and didn't remove because I think it's a funny thing to leave in there. Sue me. 