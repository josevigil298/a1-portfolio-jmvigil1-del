--Readme document for *YOUR NAME*, *YOUR_EMAIL@uci.edu*--

A reminder on academic integrity, as described in the syllabus.

In general, the course staff expects that you will look at code and examples from many online resources as part of the assignments, particularly to resolve syntax and understand frameworks. We expect that you'll use other libraries you find, and will even require it in some assignments. These practices are often critical to the work of developers today. The best developers are adept at interpreting the examples they see, customizing them to their specific situation, and citing their sources so they can find them later. We expect you to do the same.

While learning from examples is encouraged, attempting to pass an existing project or example from the web as your own is not allowed. If you ever have a question about what is or is not appropriate, feel free to ask the course staff!

Talking to classmates about class material, assignment requirements, etc. is a great way to verify ideas and get feedback. But this distinctly does *not* permit attempting to pass off someone else’s code as your own. Talking over ideas and approaches is allowed, but the work that you produce and submit must be your own.

1. How many assignment points do you believe you completed (replace the *'s with your numbers)?

*/10
- 1/1 Readme
- 2/2 Basic HTML content
- 1/1 Basic CSS styling
- 1/1 Advanced feature
- 1.5/2 Responsive layout
- */1 Passes validation checks
- 0.5/2 Embraces spirit of the assignment

2. What (a) basic features, (b) CSS features, and (c) advanced features did you include in your portfolio?

(a) Basic features

For my basic features, I chose to include 3 seperate images which correlated to my projects. I included their corresponding alternative text
for accessibility purposes with two of these images being primarily logos, and the other image being a project mock-up showcase.

I also included appropriate headings to describe the different sections in my portfolio for both pages. These headings described sections such as
education, skills, about me, and projects.

I also included links, one for my LinkedIn, and two others for my resume which leads to another page where users can view the pdf and choose to download my resume.

I also included multiple pages! In total I included 3. The first is the home page, the second being the about me page, and the third is a pop-up
window for my resume which is just the pdf of my resume. But all of these are easy to navigate to from the top navigational bar.

I did use an aside tag for my contact me section! Not sure if it was used properly, or as intended, since it was my first time using it. But,
I am pretty sure it was after constant web searches and coding.

I also included custom icons from bootstrap itself which required another stylesheet aside from mine which was a CDN:
  <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/bootstrap-icons@1.13.1/font/bootstrap-icons.min.css">



(b) CSS features

I modified padding for headers and paragraphs so that they did not seem to cluttered within the page. I also added padding for sections for the same reason
so that they were not too close together. I included some padding from the top for the whole body of the html in order to account for the navigational bard.
I also included padding and margins for certain text such as the list items in my skills section or the heading in the contact me aside tag.

I modified links and text color for those links in the contact me section and skills section to make them look exactly like the other text in the the 
p tags in the rest of the body of the html. I also modified the background colors for those same sections, and also the color of the entire body.
I honestly wasn't sure what how to design my portfolio so I simply just chose these two colors instead of having it all white.





(c) Advanced features

I included a navigational bar! It only has 3 links for navigation and even the navbar brand is a navigational link. It also collapses correctly, from my testing,
on mobile devices and opens up vertically.




3. Did you ignore any of the warnings or errors presented by the accessibility checker? If so, why does this not seem like an accessibility concern? If it's useful, you can consolidate your thoughts on multiple warnings/errors if the rationale is similar.

One of the known problems in my index html had to do with the way the icons were added into the html body. Because bootstrap uses the i tag for its icons the accessibility checker
believes that it is meant to be italics but is just technically an image or icon. I tried using different methods to see if it would stop identifying as italics but it did not. It was the same for both html
files as well. There was also a plethora of potential problems but a lot were about keyboard accessibility with my navbar, which required javascript from what I learned and I have no prior experience with it.
Instead of taking to much time fixing these potential issues or risk breaking what I already have I chose to leave it alone. There was also potential problems concerning images and the alt text.
It would say that it was not as descriptive as it needed to be, but I was not sure what it meant as there was not much to describe in the images other than that they were logos or project mock-ups. I'm not sure if
it is because the images are not able to be viewed since they are not within the file and are outside files.



4. How long, in hours, did it take you to complete this assignment?

About 20 or more hours I believe. A lot of the time actually was just thinking of layouts and designs but in the end I just ended up doing something pretty simple for
the amount of time I kept thinking of what to include and how to lay it out.



5. What online resources did you consult when completing this assignment? (list specific URLs, describe queries to Generative AI, or use of AI-based code completion)
I used a lot of help from the BootStrap website, w3schools, and ChatGPT. The first two websites were most for tutorials on how to use certain layouts or how to make everything more
responsive. If anything was broken or the layout began to glitch out in certain dimensions I would consult ChatGPT on the next steps. Honestly, ChatGPT would not be as helpful with CSS
since its always hard to describe whats going on but it did help in some aspects such as when text was overflowing from out the contact me box section.



6. What classmates or other individuals did you consult as part of this assignment? What did you discuss?

N/A. I didn't really ask anyone for help although I should have especially from TA's. But it was honestly all just me, and the overall design
and layout came out pretty simple and basic because of it.



7. Is there anything special we need to know in order to run your code?
Nothing that I can think of as of right now. I will mention that I did use two CDNs which were for bootstrap, and bootstrap icons. There was also a script
that I put at the end of every body tag from bootstrap in order to get my navbar to collapse in mobile devices. These are the CDNs:

<link href = "https://cdn.jsdelivr.net/npm/bootstrap@5.3.8/dist/css/bootstrap.min.css" rel="stylesheet" integrity="sha384-sRIl4kxILFvY47J16cr9ZwB07vP4J8+LH7qKQnuqkuIAvNWLzeN8tE5YBujZqJLB" crossorigin="anonymous">
<link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/bootstrap-icons@1.13.1/font/bootstrap-icons.min.css">
 <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.8/dist/js/bootstrap.bundle.min.js" integrity="sha384-FKyoEForCGlyvwx9Hj09JcYn3nv7wiPVlz7YYwJrWVcXK/BmnVDxM+D2scQbITxI" crossorigin="anonymous"></script>

