# Exercise 1 - Basic Website

## Objectives

Create a basic folder structure for a website. Use HTML skeleton code to create a couple simple web pages that include a little content and an image. Apply external CSS styles to the content. Learn to troubleshoot code.

## Instructions

At the minimum, a website is a repository (folder) that includes a file called _index.html_ (the website’s homepage), a file called _style.css_ (where all the CSS is located), and a subfolder called _images_ to store the images.

### PART 1

### Step 1: Create a basic website

1. Create the website structure:
   - Read “Add files to your website folder” in the VS Code Reference Guide.
   - In your website folder (repository), create a new file called _index.html_, a file called _style.css_ and a folder called _images_. Notice that these names are all lowercase because that is best practice when naming files and folders. Your repository also includes the assignment readme file and a gitignore file, you don’t have to delete these files -- they do no harm and wouldn’t be visible when visitors view the website through a browser.
2. Prep your HTML page:
   - Read “Add skeleton code” in the VS Code Reference Guide.
   - In VS Code, open _index.html_ and add the HTML skeleton code.
   - Reference the stylesheet by adding `<link rel="stylesheet" href="style.css">` in the head element of _index.html_
   - Change the page title in the head HTML element to 'Basic Website Exercise'.

### Step 2: Add some content and style it

1. Add some content to the body HTML element:
   - Write a level 1 heading HTML element
   - Add the following questions below the level 1 heading and format each question so that it is a level 2 element:
     - Who are you? Please write a short bio (you can include your github username instead of your full name if you are concerned about privacy. GitHub's servers are located in the USA.)
     - Is it your first time in post-secondary education? If no, what did you study?
     - Do you have any past experience of creating websites? If yes, please explain.
     - Do you know any coding languages? If yes, which ones?
     - What are your goals for this course (Some students need a high GPA to get their funding. Some students need a minimum of a C in DGL103 to get into courses such as DGL113 or DGL203. Some students may be interested in learning specific HTML/CSS topics ...)?
   - Write your answers below each question, and format each answer with a paragraph element.
   - Check out what your web page looks like by opening _index.html_ in a web browser:
     - Click File > Save.
     - Right-click anywhere in the editor > Open in Default Browser (if you don't see this option then you haven't installed the Open in Browser VS Code extension yet). This is not a live preview, to see any changes that you make in VS Code, you need to save the file in VS Code and then refresh the page in the browser so that it will show the edits you made since the last save.
2. Add an image to your webpage:
   - Add an image of your favourite place in the world to the images folder in your repository. It can be any image you like but most popular file types for photos are JPEG, JPG, and PNG image file extensions. Name the image with a filename that makes sense, for ex: myfavouriteplace.jpg
   - In _index.html_, insert the image below the content. For ex: `<img src="images/myfavouriteplace.jpg" width="400" alt="Paris, my favourite place">`. Change the image file name in the src attribute and the image description in the alt attribute to match the file that you added to the images folder. Note that the `<img>` element is self-closing, it doesn’t need an end tag. Save and go back to your browser and refresh the page to see the edit. If you can’t see the image then the link might be broken, make sure that you’ve used the correct filename and relative file path.
3. Change the styling of the text:
   - Change the colour of the HTML paragraph element by adding `p {color: orange;}` to the style.css file. Go back to your browser and refresh the page to see the edit. If you can't see the change in colour in your browser then there may be an issue with the way you linked the CSS file to the HTML file.
   - Add one extra style you would like to try (font-family, background colour, etc.).

### Step 3: Save your work in GitHub

Make sure to follow the instructions in the How to Complete Your Exercises Guide. You don't need to submit your exercise in Brightspace until you've completed all the instructions in parts 1 and 2.

1. Commit your edits in Github Desktop. Give it a meaningful label like "Adds part 1 content".
2. Push your edits to GitHub.

### PART 2 (best to complete these instructions after your second class)

### Step 1: Add another page to your website

1. Create a new file called _page2.html_
2. Prep your HTML page:
   - Add the HTML skeleton code.
   - Link the page to the CSS file.
   - Change the page title in the head HTML element to 'Basic Website Exercise - Page 2'
3. Write a level 1 heading HTML element.
4. Style the content.
5. In _index.html_, add a link to page 2: <a href="page2.html">Visit page 2</a>
6. In _page2.html_, add a link to the homepage: <a href="index.html">Visit home</a>
7. Remember to save both pages then check out your website in the browser.

### Step 2: Add structural elements to the content

1. Code the structural organization of the content. You don't need to include all the structural elements but you should use at least 6 of them:

   - Body
   - Header
   - Nav
   - Main
   - Section
   - Article
   - Aside
   - Footer

2. Write personal content to fill the page, for ex, the page could be about your hobbies.
   **Think about the purpose of each structural element and make sure that the content you add to it is appropriate**, for example the menu should include a menu of links, not a paragraph.
   Use the HTML elements we have learnt about so far to organize the content.
   - Headings (H1 to H6)
   - Paragraph
   - Strong
   - Bold
   - Italic
   - Emphasis
   - Special Characters
   - Hyperlinks (including email links and same-page links)
   - Unordered lists
   - Ordered lists
   - Description lists
   - Image
   - Div and span (you shouldn't need these elements as they carry no semantic meaning and are only used to define areas to which you want to apply styling)
     Look the elements up in HTMLreference.io for details on how to use them. Feel free to experiment using more HTML elements if you like.

### Submit your work

You have now completed your practice exercise but you still need to:

1. Commit your edits in Github Desktop. Give it a meaningful label like "Adds part 2 content".
2. Push your edits to GitHub.
3. Submit your practice exercise in Brightspace.
