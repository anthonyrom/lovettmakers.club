# lovettmakers.club
The Lovett Makers Club website, created using the [Boxify template by Peter Finlan](https://github.com/peterfinlan/Boxify). This website was long overdue: clubs at Lovett are required to have a website including some information about the club. For a shameful amount of time, we left ours as a simple index.html with a background color and some centered text, with a link to sign up on a Google Form. Everything has changed.

Current version hosted at [lovettmakers.club](http://lovettmakers.club).

## Screenshots

#### Top of page:
![makerspace](https://github.com/anthonyrom/lovettmakers.club/blob/master/github-screenshots/makerspace.png)

### What does it draw from the template?
As you can see, if you open [lovettmakers.club](http://lovettmakers.club) and http://tympanus.net/Freebies/Boxify/ up and compare, they are very similar. Peter Finlan did an excellent job making this template. He used libraries and frameworks such as animate.css, retina.js, Modernizr, Bootstrap, and more. By understanding the HTML, CSS, and JavaScript at the foundation of the template, I was able to make the changes I wanted to make.

### So what's different?
Here is an exhaustive list of changes:

- Boxify logo has been replaced with Makers Club logo

- Blue color used throughout site replaced with teal (#009688)

- FontAwesome icons replaced throughout site

- Replaced static HTML5 icon with rotating Makers Club cog logo

- Removed links in the features/projects section

- Heavily modified the section in which the iPhone drops down to display app screenshots
  - Removed the iPhone graphic and animation
  - Removed the image gallery contained within the iPhone
  - Removed the user testimonial
  - Kept the parallax background code, changed image
  - On top of this parallax background, I put more text and a Makers Club logo with animated cog
  
- Removed section between parallax and image showcase

- Removed icons on hover for image showcase

- Code has been minified to reduce page load times. 
  - Note: files hosted here are not minified. I minify the files before uploading changes to the server. Any code you get from this repo will be beautifully formatted and legible.

### Want to help?
Due to the overall complexity and amount of CSS and JS included with this template, I am pretty confident I have not removed all unnecessary code (i.e. code that applied to sections of HTML that I removed). If you see any of these, let me know so I can make the page a bit faster to load!

For example:

- In the image showcase section towards the bottom, I have removed the lightbox feature found in Boxify. Let me know if you see any left over lightbox code!

### Current to-do list:
- Make and upload a favicon that supports all devices/browsers/resolutions
- Let me know of more changes you would like to see!
