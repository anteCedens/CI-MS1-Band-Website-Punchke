# **"Punchke" Band Website**


This website was built for the purposes of my first personal project ("milestone project") at Code Institute.

This was a static front end project: the requirements were to write HTML5 and CSS3 code to bulid a website of my own choosing i.e. design.

The general idea, or rather the subject matter - to choose to build a band website - stemmed from one of Code Institute's suggestions for the project's topic: to design a website for either a real or a fictional band.

Firstly, choosing a real band seemed easier to do - there could be actual band photos, record covers, music, and overall band esthetic to draw upon. And this band - Punčke ("Punčke being the original spelling, to be pronunced as if it was spelled "Punchke") - might have the first band to come to mind to me.

I would consider myself a longtime fan of the band: listenintg to their music and gong to their shows over a span of years. 
Being a part of their audience, I figured I have an impression and have formed a view of their esthetic that would help in making the design choices for the website.

Furthermore, the band didn't have a website that I was aware of - so I couldn't have been "too much" influenced by that, which made things additionally interesting; the band did have a social media presence on sites like Facebook, Instagram, Twitter, and Youtube, as well as a Bandcamp page.

Additionally, it was not a high-profile band, so I didn't think they'd mind in me using the for my project like this. 
I also have at one point in the past exchanged some emails with the band, and even met them on one occassion - all of this, again, aiding to the overall impression they wouldn't mind me using them for this project.
But I have not contacted to check this.

To mention lastly that the band was recently retired.

---


## **UX**

Should a student choose to a band website for their project - the way I did - Code Institute's guidelines were as follows:

>**External user’s goal:**
>
>* The site's users are fans and potential fans who wish to learn more about the band's history and the band members, and possibly book them for shows.
>
>**Site owner's goal:**
>
>* The band are interested in selling more of their music/merchandise and getting more gigs.

In other words, straight up common sense of what one would expect of a band website: users would expectedly go on the website to find out information about the band, and the site is suppose to provide that information.


### ***Structure***

The main structural decision posed from the get-go (posed in the official project requirements) was to either:

>1. create a website of at least 3 pages, or
>
>2. (if using a single scrolling page), at least 3 separate page areas

I opted for the former.

With that choice made, next thing was to choose the topics or the subject matter or the content of those pages - i.e. what will they be about.

I decided to do five pages, for structural symmetry reasons: the navigation bar at the top of the website (viewed in desktop mode) would 
contain centered within it the links to the five pages, the main page (index.html) being in the middle, with two of the other pages (lets refer to those as "subsites" - as opposed to the "main page")
on either side of it.

The topics for the subsites changed throughout the project, with this being the final choice:

* news

* about

* PUNČKE (main site, i.e. index.html)

* merch

* gallery

So, this would compose the navbar, which would make up the header.


### ***Header***

The skeleton of the header is described above.

Each of the websites five pages would contain the same header - for consistency reasons - apart from the "merch" page, 
which would not in fact exist (within the confines of my project) - in the sense that it is not made by me - I rather just link to the band's existing merchandise website.


### ***Footer***

Footer consist of links to the band's social media sites, where the links as represented as Font Awesome's corresponding icons.

Social media sites represented are:

* Facebook
* Instagram
* YouTube
* Twitter

The links all lead to actual accounts the band has on these platforms.

Although the conceptual contents of the footer don't differ for any of the pages (i.e. every footer on the website, no matter what page it's on, contains said links to the band's social media profiles), the footer doesn't look the same for all of the pages,
for reasons that will be spoken about when speaking about each of those pages further down.


### ***index.html / Punčke***

The main idea for the index.html page - the "main page" of the website - stems from the band's album cover for their "Sunčano s povremenom naoblakom" LP.

The title is a Croatian weather report phrase, which translates as "sunny with occassional cloudiness".

Page is executed fairly sparse, consisting only of a header - styled identically as on all other subsites - and of a so-called "crossfade" animation of two images:
one - the first one that's loaded with the page - which is a pixelated image which is the band actual cover for the aforementioned album; and the other which a photo a blue sky interspersed with patches of clouds.

The second image is not initially visible. As the user opens the website and starts hovering over it, it triggers an animation where the first image slowly fades into the second, and then vice versa.
The direction of the fading keeps alternating *ad infinitum*.

There is no footer on this page, as it might take atenttion away from the images, and might not "fit" so well with them - especially 
as the band's name and record's title are located at the bottom of the cover, and it's desirable that they both catch and occupy the user attention, as the title of record corresponds semantically with the crossfaded imagery.

There is plenty of chance to use the footer's links on other pages of the website.

Also, let's say this is an actual website for the band available on the internet: if a user googles the band, he or she should see all their social media profiles come up in the search results: nobody's at much of a loss if links to all those profile 
don't also come up right on the first page of the website.

This particular "sparseness" of the index page, along with the open space implied by the photo of the sky, evokes a kind of a "entry" effect - like if it was a doorway of sort: here's our website, feel free to come in to find out more.
Which also urges user to browse the remainder of the website if he or she indeed wishes to find out more.

The header is not "sticky" on this particular page - it does not scroll down with the user. Which also seems favorable: so there is nothing to "obstruct" or "take away" from the imagery/animation.

The photo of the cloudy sky was taken by me.


### ***News***

Header is identically styled as elswhere on the website, and is "sticky" (it scrolls with the user).

Footer is styled as on the "About" page. Icons in the footer are styled identically as elsewhere on the website - the difference between
the footer on the "News" and "About" pages, and on the "Gallery" page is that the former have a green background that corresponds to the background of the header;
whereas the Gallery's footer has no background color set (i.e. it has the same black background color as is present in the Gallery's body's background).

Background for the "News" page is the design of the band latest (and last) EP's title, set to repeat horizontally.

Upper half of the page juxstaposes the image of the band's aforementioned latest EP (image is that of the EP's physical copy - as is evident by the wraping creases on the sides - as opossed to just a copy of the cover design), 
with a text announcing that that latest EP is up, and also containg a clickable button that links to the band's Bandcamp page where that EP can be heard.

The bottom half of the page juxstposes in a corresponding manner an imbedded YouTube video for a single of the latest EP, with a form with which user can subsribe for newsletter if they wish to be kept up to date with more news about the band.


### ***About***

Header and footer identical as on the "News" page.

Page has a tet about the band, wrapped around a photo of the band.

The photo is from their latest EP's photo sessions, and thus depicts the bands latest lineup and look.

The text is taken almost verbatim from the About section of the band's Facebook site, with only some minor typo corresctions made.

Page contains info about the current band memebers, their hometown (hometowns) and current location, and contact details - also all takne from the band's Facebook page - as well as a link to their discography, via a link to their Bandcamp page.

The background is something that I tried to "force" onto the page - I cared that used this particular background.

The background is a image from a tea towel I have at my home (I'm not even a 100% sure anymore at which store did I buy it). It depicts three lemons (with the words "so fresh" repeated three times beneath).

I took this to be a metaphor for the band. The band is a trio; and the lemons, three lemons should be a metaphor of the detractors and the put-downs that I read thorugh their interviews that they were faced with throughout their career as band: 
to be percieved as "lemons", three lemons, three "bad eggs", that nothing will come out of, etc.

Lemons are also evocative of the phrase: "When life gives you lemons...". Which corresponds to DIY nature: they're a self-released, self-made, DIY band.

The fact that the background image is made by me from a tea towel - a dirt-cheap, ordinary-supermarket, everyday, "found object" - also corresponds well with the DIY esthetic and ethic.

Plus it's an image depicting fruit - which might also kind of invokes a "grass-roots" type of thing connotations, which also plays into the whole picture depicted here.

Anyway, I quite liked all of this semantical strands intertwining and coming together, so I tried to keep that background image and make it work with the color scheme and typography, if in any way possible.

This is to explain that I'm aware that green and dark tones of the leaves of the lemons clash somewhat with the text - making it harder to read - and to explain why this is so.

The white and the yellow pose no such issues and work quite nice; as do the textures and the creases of the actual tea towel, in my opinion.

I finally decided to cut the "so fresh" words from the background, as it's dark color clashed to much with the text on the page; and I set the background to repeat horizontally, resulting in a quite nice effect on mobile phones screen sizes.


### ***Merch***

As mentioned earlier, the "merch" page isn't a part of this website, but rather external to it: if you click on the "merch" 
link in the header, it open a bands pre-existing merchandise site in a new tab.


### ***Gallery***

The "Gallery" section consisit of band photos style into a so-called *masonry* style look.

The photos were chosen by me out of what I could find on the internet.

I chose photos that seemed appealing to me for various reasons, and I think I managed to obtain a good balance between 
different photo sizes, live performances, press realease photos and more spontaneous, more private looking photos, black and white and color photos, 
photos from various stages of the band (encompassing different lineups), etc.

Background is composed out of one of the band's designs used for one of their songs. The design is a rehashing of one their earlier designs (which is I'd say my 
favorite design of theirs, for on of my favorite songs of theirs).

This new take on the design that was used for the background here utilizes a pitch black background with a neon white bright glowing image over it, which I think goes well with 
the photos in the gallery.

The footer for the gallery was styled to accompany the chosen background: footer has no background, and the social media links icons it containts are rendered in neon white, with 
some shadow effects.

This styling evokes a kind of a "dark room" feel to it, which goes with the content being entirely photos.

The background image is set to repeat horizontally.

Styling of the header is the same as on other pages of the website.

---


## **Technologies and Tools Used**

* HTML (HTML5)

* CSS (CSS3)

* Repl.it

* Font Awesome

* Google Fonts

* GitHub

* GitPod

* Chrome DevTools

* HTML Validator

* CSS Validator

* SCSS to CSS Compiler - CSS Portal

* Windows Snipping Tool

* Canon MG3650 Scanner

---


## **Testing**

This project was manually tested as it was buing built.

Project was primarily built using Repl.it, before being "migrated" (retyped) to GitPod, and stored on GitHub.

Different features, ideas, and variants of the projects could be quickly tested out in different "repls", as the project overall 
wasn't too demanding for Repl.it's capacities.

Project was presented to my mentor at various stages, with invaluable feedback taken into account (for instance, that I should, as a rule of thumb, 
avoid using more that three font families - I had four at the time, shich I then reduced to three).

W3C HTML and W3C CSS Validators were also use to asses the code.

Use of Chrome DevTools was indispensible throughout the project.

I tries using Bootstrap to solve some the issues croping up and/or expected to crop up during the development of the project,
but gave up on that eventually, as Bootstrap was seemingly causing more issues for me than it was solving, and making me rather stuck than making headway.


---


## **Deployment**

**Deployment To Github Pages**

- In my account GitHub website, I selected Repositories

- I selected CI-MS1-Band-Website-Punchke from the GitHub Dashboard.

- I navigated to Settings and to the GitHub Pages section.

- From the Source section, I clicked on the drop-down menu and selected Master Branch.

- Once Master Branch is selected, the page has been automatically refreshed, with a detailed ribbon display GitHub Source Saved Pages indicating the successful implementation.

The live link can be found here - https://clairelally8.github.io/TravelDiary/


**Local Deployment**

 - To run locally, you can do one of the following two options 
    
    - Clone the repository using the `git clone https://github.com/clairelally8/traveldiary.git` command

    - Download the zip file, unzip and run it in your favourite local IDE (such as VS Code)

---


 ## **Credits**
 

 ### ***Content***

 The text and all the info that comprise the "About" page were taken from the band's Facebook profile


 ### ***Media***

 - Photos used for the "Gallery" page were used in the form of https links pointing to external sources - rather than downloaded to a project file folder -
  and their sources can be tracked down through those links in the code.

- Same as above goes for the background at the "Gallery" page, and the one on the "News" page, as well as for the first image (the pixelated one) used in 
the crossfade animation on index.html

- As for the rest images, that are used via the project's img folder:

    - photo used on the "About" page was cut by me from the band's video that can be found here: 

    - photo used on the "News" page was cut by me from a photo on the band's Bandcamp page:

    - the second image - the one of the cloudy sky - from the crossfade animation at index.html was taken by me

    - the background image for the "About" page was made by me by scanning a tea towels I have with a Canon MG3650 scanner, and then cutting the scan using Windows' Snipping Tool.
    I think I bought the tea towel at my local Lidl store. It says "Meradiso" on the label 

- Google Maps API documentation was used in the creation of the Script for this site. 


### ***Acknowledgements***

I used many sources of inspiration and help, for each of which I am thankful for:

 - Code Institute's excercise/tutorial project, named "Love Running" - for the gallery's masonry style look idea, and the code - https://repl.it/@jjuric13/Love-Running

- http://css3.bradshawenterprises.com/cfimg/#cfimg1 - for the code for the crossfading animation, which I tweaked only slightly

- https://www.lebutcherettesofficial.com/ - for many ideas that ended up shaping the look of the "News" page: basically all of the textual content on the page (text used there is more or less a carbon copy of the Le Butcherettes' website), as well as the way that text is structured - structure of the form very much included

- https://css-tricks.com/centering-list-items-horizontally-slightly-trickier-than-you-might-think/ - this particular article is referenced in the code

- https://teamtreehouse.com/community/reordering-li-elements-to-float-right) - article also referenced in the code

- https://www.freecodecamp.org/news/how-to-keep-your-footer-where-it-belongs-59c6aa05c59c/ - article referenced in the code

- https://css-tricks.com/responsive-menu-concepts/ - for solutions for the navbar responsiveness I was looking for - article also referenced in the code

- https://codepen.io/TimPietrusky/pen/gqlhA - author of my chosen solution for the navbar responsiveness - I tries to tweak his code a bit - original author referenced in my project0s code

- Claire Lally - for being kind enough to send me a link to her readme.md file, to assist me in writting mine - https://github.com/ClaireLally8/TravelDiary/blob/master/README.md

- https://www.w3schools.com/ and https://css-tricks.com/ in general - for all the time I spent there

