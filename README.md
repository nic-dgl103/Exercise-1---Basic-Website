# Exercise 1 - Basic Website

## Objectives
Create a basic folder structure for a website. Use HTML skeleton code to create a simple web page that includes a little content and an image. Apply external CSS styles to the content. Learn to troubleshoot code.
## Instructions
At the minimum, a website is a repository (folder) that includes a file called *index.html* (the website’s homepage), a file called *style.css* (where all the CSS is located), and a subfolder called *images* to store the images. 
### Step 1: Create a basic website
1. Create the website structure:
    * Read “Add files to your website folder” in the VS Code Reference Guide. 
    * In your local website folder (exercise repository), create a new file called *index.html*, a file called *style.css* and a folder called *images*. Notice that these names are all lowercase because that is best practice when naming files and folders. Your repository also includes the assignment readme file and a gitignore file, you don’t have to delete these files -- they do no harm and wouldn’t be visible when visitors view the website through a browser.
2. Prep your HTML page:
    * Read “Add skeleton code” in the VS Code Reference Guide. 
    * In VS Code, open *index.html* and add the HTML skeleton code. 
    * Reference the stylesheet by adding `<link rel="stylesheet" href="style.css">` in the head element of *index.html*
    * Change the page title in the head HTML element to 'Basic Website Exercise'.

### Step 2: Add some content and style it
1. Add some content to the body HTML element:
    * Write a level 1 heading HTML element
    * Add the following questions below the level 1 heading and include your answers:
        * Who are you? Please write a short bio (you can include your github username instead of your full name if you are concerned about privacy. GitHub's servers are located in the USA.)
        * Is it your first time in post-secondary education? If no, what did you study?
        * Do you have any past experience of creating websites? If yes, please explain.
        * Do you know any coding languages? If yes, which ones?
        * What are your goals for this course (Some students need a high GPA to get their funding. Some students need a minimum of a C in DGL103 to get into courses such as DGL113 or DGL203. Some students may be interested in learning specific HTML/CSS topics ...)? 
    * Format your questions and answers by wrapping them in level 2 heading HTML elements and paragraph HTML elements. 
    * Check out what your web page looks like by opening *index.html* in a web browser: 
        * Click File > Save.
        * Right-click anywhere in the editor > Open in Default Browser (if you don't see this option then you haven't installed the Open in Browser VS Code extension yet). This is not a live preview, to see any changes that you make in VS Code, you need to save the file in VS Code and then refresh the page in the browser so that it will show the edits you made since the last save. 
2. Add an image to your webpage: 
    * Add an image of your favourite place in the world to the images folder in your local repository. It can be any image you like but most popular file types for photos are JPEG, JPG, and PNG image file extensions. Name the image with a filename that makes sense, for ex: myfavouriteplace.jpg
    * In *index.html*, insert the image below the content. For ex: `<img src="images/myfavouriteplace.jpg" width="400" alt="Paris, my favourite place">`. Change the image file name in the src attribute and the image description in the alt attribute to match the file that you added to the images folder. Note that the `<img>` element is self-closing, it doesn’t need an end tag. Save and go back to your browser and refresh the page to see the edit. If you can’t see the image then the link might be broken, make sure that you’ve used the correct filename and relative file path.
3. Change the styling of the text:
    * Change the colour of the HTML paragraph element by adding `p {color: orange;}` to the style.css file. Go back to your browser and refresh the page to see the edit. If you can't see the change in colour in your browser then there may be an issue with the way you linked the CSS file to the HTML file.
    * Change the colour of the HTML level 1 heading element to any colour you like.

You have now completed your exercise but you still need to push your edits to GitHub and submit it in Brightspace. Make sure to follow the instructions in the How to Complete Your Exercises Guide.
