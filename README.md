# porfolio

Originally created for Week 2 HW

[LINK TO PAGE](https://theoriginalison.github.io/portfolio/)

index.html (linked from both "Alison Lubar" and "About Me")
![Screenshot of the "About Me" / "Alison Lubar" page featuring a picture of Alison along with her bio"](./ReadMeImages.AboutMe.png)

contact.html (linked from "Contact")
![Screenshot of the "Contact" page featuring a box to enter name, email address, and a message to Alison.](./ReadMeImages.Contact.png)

portfolio.html (linked from "Portfolio")
![Screenshot of the "Portfolio" page showing grey placeholders where projects will soon be listed!](./ReadMeImages.Portfolio.png)

## Table of Contents

_[Approach](#approach)
_[Problems & Solutions](#changes)
\_[Discoveries](#discoveries)

## Approach & Process

- I began by making the index.html, since I notice that the containers across all three pages looked similar; this way, I could use index.html as a template, and style it exactly as I wanted it, and THEN replicate that for contact.html and portfolio.html. Jumbotron seemed the closest.
- I used bootstrap's navbar, and created a footer that matched it in color by using the same hex name. It was right up against the navbar, so I added a margin.
- I perused Bootswatch and found "Lux." I didn't want to be too bougie, so I kept the nav and footer light-colored.
- I added a background image that's one of my favorite pictures (or at least, one in that subject). I found this on Pexels (free stock photos), and credited the source in the footer, with my copyright. I added this to the background using CSS.
- Added alt text for my profile picture
- After index.html's style was complete, I made two copies, turning one into contact.html and the other to portfolio.html.
- Linked all three pages together not by web address, but by the html file, and made sure navbar button for the current (active) page was bolded.
- To replicate the portfolio.html images as closely as possible, I used Placeholder.com to find 350px grey image squares. I put these in rows, then columns, to mirror the sample photo.
- I use a form from Bootstrap to create the box for contact.html. I also made sure to match the type to the purpose of each box. I also added "Type your message to Alison here." as the grey text for the message box, to be a little more personal.
- I grouped all CSS by common elements (since I stared with the index.html, and many elements were standard across all three pages, this maked this most sense). Then, I added comments to indicate where each page had CSS that was only relevant to that page.
- I checked everything using W3's HTML Validator. It saw my image placeholders in portfolio.html as needing alt tags, which I added. I would rather add more alt tags than not.
- Finally, I wrote the README and, taking feedback from my last homework, tried to add a link and images of the pages.

## Problems & Solutions

- Text in About Me wouldn't wrap around the picture; one line would start, and then the rest of the text appeared below the picture. I fixed this by putting the image directly in the <p> tag and added float:left to the CSS, just for the picture.
- About Me text was jagged on the right side, and I wanted a cleaner look. I used text-align: justify so all lines would be the same length.
- Set zero margin for the footer so it would be flush against the bottom of the page-- I set the bottom margin to zero to fix that.
- I spelled the name of my repo incorrectly at first! It was "porfolio," which was highly embarassing (English teacher here!). So, after pushing all of my changes, I renamed the repo on GitHub, and then pulled from the renamed repo to make sure I had the most current versions. In office hours, I double checked that this was fine, and Anthony suggested that I just create a new location on my computer with the proper name (which I did).

## Discoveries

- Viewport Units are a font-size value that can be used to easily scale to the viewport, making scaling much easier
- Linking files within a folder is made easier when you can directly select them; in other words, the files or folders should pop up in VS Code as you're tying the route
- Using <input> for the placeholder doesn't wrap text inside (like in context.html, and the default info in the form), but <textarea> does! It keeps the text in the boxes responsive. The text withIN the placeholder isn't responsive, but Tani said that it was ok. Also, the W3 Validator didn't like <textarea>, and wanted me to change it to <input>. But, again, it does what I want it to do.
