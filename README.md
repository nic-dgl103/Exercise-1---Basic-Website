# Exercise - Basic Website
This is your remote repository readme file. You are seeing this file because you have successfully accepted the assignment link and GitHub automatically created a remote repository for you.
## Objectives
Create a basic folder structure for a website. Use HTML skeleton code to create a simple web page that includes a little content and a couple images. Apply an external CSS style to the content. Learn to troubleshoot code.
## Instructions

### Step 1: Get set up
Detailed instructions for the tasks below are included in the References Guides and in the How to Complete your Exercises video.
1. Sign up for a GitHub account 
2. Install GitHub Desktop
3. Install Visual Studio Code on your computer, and customize it by installing the recommended VS Code extensions, turn on word wrap, and disable auto-closing HTML tags.
4. Clone the remote repository to your local machine.
5. Open your local exercise repository (folder) in VS Code.

You are now completely set up and can complete the instructions in step 2 but you need to have done the week 1 reading to understand the exercise.

### Step 2: Create a basic website
At the minimum, a website is a repository (folder) that includes a file called *index.html* (the website’s homepage), a file called *style.css* (where all the CSS is located), and a subfolder called *images* to store the images. 

1. Create the website structure:
    * Read “Add files to your website folder” in the VS Code Reference Guide. 
    * In your local exercise repository, create a new file called *index.html*, a file called *style.css* and a folder called *images*. Notice that these names are all lowercase because that is best practice when naming files and folders. Your repository also includes the assignment readme file and the image of the finished exercise. You don’t have to delete the readme file, it does no harm and wouldn’t be visible when visitors view the website through a browser, but know that the readme file wouldn’t be present in a real website’s folder.
2. Prep your HTML page:
    * Read “Add skeleton code” in the VS Code Reference Guide. 
    * In VS Code, open *index.html* and add the HTML skeleton code. Add an HTML comment in the head section of the HTML code including: the term, the course code, your section number, your student name, and the name of the exercise. Example:
`<!-- F23 DGL 103 CVS1 - Jane Pordor - Basic Website Exercise -->`
    * Reference the stylesheet by adding `<link rel="stylesheet" href="style.css">` in the head section of *index.html*
    * Change the page title to 'Basic Website Exercise'.
5. Add the page content to body element of the page:
    * Write a level 1 heading HTML element
    * Add the following questions below the level 1 heading and include your answers:
        * Who are you? Please write a short bio (include your github username instead of your full name if you are concerned about privacy. GitHub's servers are located in the USA.)
        * Is it your first time in post-secondary education? If no, what did you study?
        * Do you have any past experience of creating websites? If yes, please explain.
        * Do you know any coding languages? If yes, which ones?
        * What are your expectations for this course (or what you would like to learn in the course)? 
    * Format your questions and answers by wrapping them in level 2 heading html elements and paragraph html elements. 
> While you are working:
> - Make sure you save the file regularly. Note: In VS Code, if the file name in the tab at the top of the window has a white circle next to it then the file includes edits that have not been saved yet.
> - Commit your changes to your local repository regularly to document your progress - See the GitHub and GitHub Desktop Reference Guide or the How to Complete your Exercises video for instructions. 
> - Check out what your web page looks like by opening *index.html* in a web browser: Right-click anywhere in the file > Open in Default Browser (if you don't see this option then you haven't installed the Open in Browser VS Code extension yet - see step 1 above). I recommend making Google Chrome your default browser (https://support.google.com/chrome/answer/95417?hl=en&co=GENIE.Platform%3DDesktop).
4. Add an image to your webpage: 
    * Add an image of your favourite place in the world to the images folder in your local repository. It can be any image you like but most popular browsers support: BMP, SVG, JPEG, JPG, PNG and GIF image file extensions. Name the image with a filename that makes sense, for ex: myfavouriteplace.jpg
    * In *index.html*, insert the image below the paragraph element. For ex: `<img src="images/myfavouriteplace.jpg" width="400" alt="Paris, my favourite place">`. Change the image file name in the src attribute and the image description in the alt attribute to match the file that you added to the images folder. Note that the `<img>` element is self-closing, it doesn’t need an end tag. Save and go back to your browser and refresh the page to see the edit. If you can’t see the image then the link might be broken, make sure that you’ve used the correct filename and relative file path.
5. Change the styling of the text:
    * Change the colour of the HTML paragraph element by adding `p {color: orange;}` to the style.css file. Go back to your browser and refresh the page to see the edit. If you can't see the change in colour in your browser then there is an issue with the way you linked the CSS file to the HTML file.
    * Change the colour of the HTML level 1 heading element to any colour you like.

### Step 3: Learn to troubleshoot errors
1. Learn to use the HTMLHint extension:
    * The HTMLHint VS Code extension will automatically underline coding errors with a squiggly line. If the extension has detected errors, a number will appear next to a warning icon in the status bar at the bottom of the VS Code window - See VS Code Reference Guide for details. Click on the warning icon in the status bar to open the Problems Panel. 
    * Type this error in your HTML file: `<image`. The following error message should appear in the Problems Panel "Special characters must be escaped : [ < ]". This error tells you that the HTML element is missing a closing angled bracket. you can click on the error message to highlight the error in your code. 
    * Type a closing angled bracket at the end of the HTML element. Notice that the error message has changed, it is now telling you that the `<image>` element is missing an end tag, yet image elements are self-closing, they don't need an end tag. The syntax is wrong, the HTML for an image is `<img>`, not`<image>`, but the extension isn't smart enough to recognise our mistake. While the HTMLHint extension can save you a lot of time by pointing out errors, it won't solve all your problems. It will take you some practice to be able to understand the error messages and put them in context. 
2. A more robust way to validate your HTML is by using the official W3C Markup Validator: 
    * Go to https://validator.w3.org/#validate_by_upload. Choose your *index.html* file in your local repository and click the Check button. If there are no errors then you should see a green message that says “Document checking completed. No errors or warnings to show.” If you get an error message then troubleshoot your work, save and re-check it until you get the green message.
    * **Take a screenshot of your HTML validation results, you will need to submit it in Brightspace.**

### Step 4: Submit your work
1. Complete the following steps from the GitHub and GitHub Desktop Reference Guide:
    * Make sure that all your files are saved in your local repository and then commit your changes using GitHub Desktop.
    * Push your changes to GitHub. Check out your remote repository in GitHub to make sure that the remote files look the same as your the files in your local repository.
2. Submit your work in Brightspace. Navigate to Exercise 1:
    * Paste the URL to your remote repository (for ex: https://github.com/DGL103-Fall2023-CVS1/Basic-Website-AskClaireGuiot) in the comment field.
    * Read to the rubric provided at the bottom of Exercise 1. Give yourself a grade out of 5 for your exercise.
    * Click "Add a file" to attach the screenshot of your HTML validation results.

Note: If you have been using a lab computer on campus to do your work, remember to shutdown or restart the computer before you leave the room so that other students won’t have access to your repositories.

## Deadlines
Assignments must be submitted before the end of the week (before the next week’s class) but they will only be graded at the end of every unit. Late assignments will not be accepted and will receive an F. You can complete and submit a contract that allows you to extend the deadline for an assignment but you must email it to your instructor a minimum of 48 hrs before the deadline. Students are only entitled to 2 extensions per course. Deadline extensions are only allowed for those unplanned, unexpected emergencies that life sometimes throws at us, and they will only be approved by your instructor if you follow the correct process. See the Course Info folder in Brightspace for more info.
