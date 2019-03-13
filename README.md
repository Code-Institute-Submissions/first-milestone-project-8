<h1>Retro Gaming Website</h1>

<p>Games Revisited is a blog site that I have been contributing to part-time for several years, and in it's current state uses a basic wordpress template. The general
idea behind the site is to create as much community engagement as possible, something that is lacking in it's current form due to it's relatively
clunky interface.</p> <p>It is my hope that by creating a sleeker look and more user friendly navigation; it could potentially become something of a
hub style website containing a forum - allowing for greater engagement between the sites users and content creators, as well as acting as a hosting site for
aspiring game journalists, where they can point to a portfolio of their own published writing.</p> <p>Games Revisited is very much a niche site, so there is something of a focus
on lists and features in order to make the information easily digestible for anyone unfamiliar with the concept.</p>

<h2>UX</h2>

<p>The main goal of Games Revisited is to create a regular interactive userbase. As such, emphasis has been placed on contact pages;
as well as offering users the chance to submit their own writing. Social links have been included for the site, as well as for the writers 
themselves. As Games Revisited exists as a site that I occasionally write for, I had a good idea of how I wanted the site to be laid out, and what funcionality I would like to add. If you <a href="https://gamesrevisited.com/">look to the site in
it's original form,</a> it is visible that I worked to provide a sleeker and more user friendly version of the site that was already in place </p>

<ul>
<li>As an aspiring writer, I want to be able to discuss other people's work and submit work of my own in order to kickstart my portfolio</li>
<li>As a retro game enthusiast, I want to be able to see a variety of games from different years and platforms, so that I can ascertain the level of knowledge posessed by the site's writers </li>
<li>As somebody new to retro gaming, I want to be able to learn as much as possible as quickly as I can, so that I can get started playing the best retro games possible.</li>
<li>As a casual gamer, I'm looking to reminisce about games I've played in my childhood and suggest other titles for writers to review.</li>
<li>As an avid gamer, I'm looking to find niche content that I wont find anywhere else so that I can better understand different franchises</li>
</ul>

<h2>Features</h2>

<h3>Existing Features</h3>

<p>All pages contain a header image, a navbar and a footer. The header image is a smaller version of the front page hero image and text, made using Bootstrap Jumbotron. The navbar contains
links to all pages on the site, and has been tested for responsiveness so that it stacks into a burger menu on smaller screens. The footer also contains links to other page, but in a row instead of a navbar and with
social media links for the site underneath. The footer has also been checked for responsiveness, the text remains central on smaller screens, whislt the links stack nicely underneath.</p>

<ul>
<li>Feature 1 - The Welcome page <p>The user is welcomed to the page by a hero image taking up the entire background (aside from the nav), with the name of the site and it's slogan in the centre. The goals of the site are summed up
in a grid of cards under the hero image, each featuring a FontAwesome glyphicon</p></li>
<li>Feature 2 - The Hall of Fame page <p>A table that allows users to quickly digest bite-sized chunks of information in order to better understand what we find exemplary in retro gaming.
The table also includes hyperlinks to youtube in the first column to show either a commerical or a playthrough of a game so the user can better understand without having to read any content. At the bottom
of the page are two buttons, designed to be a quick jumping point from the Hall Of Fame to the Hall Of Shame page, as well as a quick link to the contact page should any users wish to get in touch with the site.</p></li>
<li>Feature 2 - The Hall Of Shame page <p>Another table, similar to the HOF page, but done with a sense of humour. Includes a hyperlinked contact button at the bottom of the table in order
to try and start a dialogue with anyone who may disagree with the opinions presented, as well as another button linking back to the Hall Of Fame page to create some synergy between the content.</li>
<li>Feature 4 - The Fallout Map Page <p>This page contains some of the more niche content for people who consider gaming to be their primary hobby, in particular fans of the Fallout franchise.
The images have been neatly displayed within a carousel including text boxes on the images. This provides some interactivity for those interested, as well as being condensed enough that the content
will not intrude to anyone who isn't interested.</p></li>
<li>Feature 5 - The About Page <p>The About page contains cards displaying information and social links for everyone who writes for the site, allowing users to contact writers personally. This page also features
a button just above the footer, taking users straight through to the contact page.</li>
<li>Feature 6 - The Contact Page <P>The contact page was initially concieved to be part of the about page, but due to a desire for the contact form to have seperate functions and therefore be split in two, it felt
more aesthetically pleasing to create a singular contact page. There are two froms on this page, one of which is designed for requests and general comments, and so includes a dropdown bar
wherein the user can select a writer to contact. The second form is for potential writers to send in samples of their work, and so works in a similar format, but with an attach button
replacing the dropdown bar</li>

<h3>Features Left To Implement</h3>

<p>There is a large archive of game reviews in the original site that I would like to bring over at some point, but the main feature I would like to implement is some sort of forum. I would like to use this format
to encourage more users to submit reviews, or talk to the people who already review for the site. It would create a more accurate template for UX in future, as it gives readers a platform to comment
on any aspect of the site immediately.</p>
<p>I would also like to implement a feature that makes the entire row on each table into a clickable link. I tried to do this unsuccesfully on this project, as it proved to be too difficult to implement without javascript. 
I would also like to add sorting bars to the table, meaning it can be organised the way the user would like to see it - be it by score or alphabetically - but encountered a similar problem whereing I would need
Javascript to make this possible.</p>

<h2>Technologies Used</h2>

<ul>
<li>HTML 5 - Used for rendering the site.</li>
<li>CSS - Used for styling the HTML and some Bootstrap elements.</li>
<li>Bootstrap 4 - Used for the grid elements on the site, as well as for some of the styling and the site's mobile responsiveness. Certain features on the site were also implemented using Bootstrap, namely the carousel.</li>
<li>Bootswatch - A font palatte for Bootstrap 4, used for it's particular colour scheme.</li>
<li>JQuery - Used for animation functionality in some of the Bootstrap elements, such as the carousel and the hamburger button</li>
<li>FontAwesome - Used for glyphicons</li>
<li>Google Fonts - Used to find fonts that better suited the retro feel of the site</li>
</ul>

<h2>Testing</h2>

<ul>
<li>Games Revisited has been tested on Mozilla Firefox and Google Chrome internet browsers, with no differences between the two, full funcionality, and no issues with the design or Bootstrap. These
tests took place on a 15" Macbook Pro in full screen.</li>
<li>Tests have also taken place on a Samsung Galaxy S7, Samsung Galaxy S7 Edge, Samsung Galaxy S10, an IPhone 7 and an Ipad. There were some issues with the hero image on a smaller device wherein there was a permananent 
gap at the side of the page - this was fixed and then tested on each device once more with no issues. Full functionality is present on all of these devices.</li>
<li> A <a href="https://jigsaw.w3.org/css-validator/"> CSS validator </a> was used. It was slightly confused by Bootswatch, but found no other issues.</li>
<li> A <a href="https://validator.w3.org/"> HTML validator </a> was used. Only issues found were an invalid space in the name of a Google font, and a couple of anchor elements
not being allowed as direct children of their parent ul element. There are no issues with the site's functionality in these cases</li>
<li>The carousel works on all devices, though is somewhat difficult to read on mobile devices.</li>
<li>The tables on the Hall Of Fame and Hall Of Shame pages have been thoroughly tested - when the screen begins to shrink, the Bootstrap responsive table creates a scroll bar at the bottom of the table
for easier readability. In addition, the tables disappear completely on mobile devices, replaced with a card column that is much easier to read</li>
<li>The cards on the About page are fully responsive, and stack similarly to the tables on smaller screens. The social media links included within are equally responsive and remain grouped together</li>
<li>All social links, hyperlinks, and links in the navbar and footer have been tested and work on all devices. All links utilise target=blank in order to open in new tabs.</li>
<li>The contact forms on the Contact page have an email prompt when the bar is clicked on, and the attach file buttons works as it should.</li>

<h2>Deployment</h2>

<p>Games Revisited is published <a href="https://scrambles86.github.io/first-milestone-project/"> here.</a><p>
<p>The development version of the site can be found <a href="https://github.com/Scrambles86/first-milestone-project"> here.</a></p>
<p>There are no difference between the development version and the deployed version,
and there are no special requirements for running the code locally.</p>

<h2>Credits</h2>

<h3>Content</h3>

<ul>
<li>All content was written either by myself or by Jamie Lepiorz, who is contactable through the site</li>
</ul>

<h3>Media</h3>

<ul>
<li>The hero/header image is a free image taken from <a href="https://unsplash.com/"> Unsplash</a>.
<li>All other images are edited images taken from <a href="https://gamesrevisited.com/">Games Revisited</a> in it's original form. These images were edited/created by Jamie lepiorz, and are intended for educational purposes only.</li>
</il>

<h3>Acknowledgments</h3>
<li>Thank you to Jamie Lepiorz and David Lovejoy, both of whom write the site with me and were very encouraging in their feedback.</li>
<li>Thank you in particular to my mentor, Simen Daehlin, who encouraged me to rework Games Revisited in the first place, and whose constructive feedback only served to make the site better. He also convinced me to lose
the original header image from Games Revisited, and for that he should be commended.</li>




