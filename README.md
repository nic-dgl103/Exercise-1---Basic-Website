# Exercise - Basic Website

## Objectives
Create a basic folder structure for a website. Use HTML skeleton code to create a simple web page that includes a little content and an image. Apply an external CSS style to the content. Learn to troubleshoot code.
## Instructions
At the minimum, a website is a repository (folder) that includes a file called *index.html* (the website’s homepage), a file called *style.css* (where all the CSS is located), and a subfolder called *images* to store the images. 
### Step 1: Create a basic website
1. Create the website structure:
    * Read “Add files to your website folder” in the VS Code Reference Guide. 
    * In your local exercise repository, create a new file called *index.html*, a file called *style.css* and a folder called *images*. Notice that these names are all lowercase because that is best practice when naming files and folders. Your repository also includes the assignment readme file, you don’t have to delete the readme file -- it does no harm and wouldn’t be visible when visitors view the website through a browser, but know that the readme file wouldn’t be present in a real website’s folder.
2. Prep your HTML page:
    * Read “Add skeleton code” in the VS Code Reference Guide. 
    * In VS Code, open *index.html* and add the HTML skeleton code. Add an HTML comment in the head element of the HTML code including: the term, the course code, your section number, your student name, and the name of the exercise. Example:
`<!-- F23 DGL 103 CVS1 - Jane Pordor - Basic Website Exercise -->`
    * Reference the stylesheet by adding `<link rel="stylesheet" href="style.css">` in the head element of *index.html*
    * Change the page title to 'Basic Website Exercise'.
5. Add the page content to body element of the page:
    * Write a level 1 heading HTML element
    * Add the following questions below the level 1 heading and include your answers:
        * Who are you? Please write a short bio (you can include your github username instead of your full name if you are concerned about privacy. GitHub's servers are located in the USA.)
        * Is it your first time in post-secondary education? If no, what did you study?
        * Do you have any past experience of creating websites? If yes, please explain.
        * Do you know any coding languages? If yes, which ones?
        * What are your expectations for this course (or what you would like to learn in the course)? 
    * Format your questions and answers by wrapping them in level 2 heading HTML elements and paragraph HTML elements. 
    * Check out what your web page looks like by opening *index.html* in a web browser: 
        * Click File > Save.
        * Right-click anywhere in the editor > Open in Default Browser (if you don't see this option then you haven't installed the Open in Browser VS Code extension yet). This is not a live preview, to see any changes that you make in VS Code, you need to save the file and then refresh the page in the browser for it to show your edits. I recommend making Google Chrome your default browser (https://support.google.com/chrome/answer/95417?hl=en&co=GENIE.Platform%3DDesktop).
6. Add an image to your webpage: 
    * Add an image of your favourite place in the world to the images folder in your local repository. It can be any image you like but most popular browsers support: BMP, SVG, JPEG, JPG, PNG and GIF image file extensions. Name the image with a filename that makes sense, for ex: myfavouriteplace.jpg
    * In *index.html*, insert the image below the content. For ex: `<img src="images/myfavouriteplace.jpg" width="400" alt="Paris, my favourite place">`. Change the image file name in the src attribute and the image description in the alt attribute to match the file that you added to the images folder. Note that the `<img>` element is self-closing, it doesn’t need an end tag. Save and go back to your browser and refresh the page to see the edit. If you can’t see the image then the link might be broken, make sure that you’ve used the correct filename and relative file path.
5. Change the styling of the text:
    * Change the colour of the HTML paragraph element by adding `p {color: orange;}` to the style.css file. Go back to your browser and refresh the page to see the edit. If you can't see the change in colour in your browser then there may be an issue with the way you linked the CSS file to the HTML file.
    * Change the colour of the HTML level 1 heading element to any colour you like.

### Step 2: Learn to troubleshoot errors
1. Learn to use the HTMLHint extension:
    * The HTMLHint VS Code extension will automatically underline coding errors with a squiggly line. If the extension has detected errors, a number will appear next to a warning icon in the status bar at the bottom of the VS Code window (see VS Code Reference Guide for details). Click on the warning icon in the status bar to open the Problems Panel. 
    * Type this error in your HTML file: `<image`. The following error message should appear in the Problems Panel "Special characters must be escaped : [ < ]". This error tells you that the HTML element is missing a closing angled bracket. you can click on the error message to highlight the error in your code. 
    * Type a closing angled bracket at the end of the HTML element. Notice that the error message has changed, it is now telling you that the `<image>` element is missing an end tag, yet image elements are self-closing, they don't need an end tag. The syntax is wrong, the HTML for an image is `<img>`, not`<image>`, but the extension isn't smart enough to recognise our mistake. While the HTMLHint extension can save you a lot of time by pointing out errors, it won't solve all your problems. It will take you some practice to be able to understand the error messages and put them in context. 
2. A more robust way to validate your HTML is using the official W3C Markup Validator: 
    * Go to https://validator.w3.org/#validate_by_upload. Choose your *index.html* file in your local repository and click the Check button. If there are no errors then you should see a green message that says “Document checking completed. No errors or warnings to show.” If you get an error message then troubleshoot your work, save and re-check it until you get the green message.
    * **Take a screenshot of your HTML validation results, you will need to submit it in Brightspace.**

You have now completed your exercise but you still need to submit it in Brightspace. Make sure to follow the instructions in the How to Complete Your Exercises Guide.
