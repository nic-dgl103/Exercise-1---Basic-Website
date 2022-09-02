# Assignment A - Basic web page
This is your remote assignment A repository readme file. You are seeing this file because you have successfully accepted the assignment link and GitHub automatically created a remote repository for you.
## Objectives
Create a basic folder structure for a website. Use HTML skeleton code to create a simple web page that includes a little content and an image. Apply an external CSS style to the content. Use GitHub and GitHub Desktop to submit the assignment. 
## Instructions

### Step 1: Get set up
Complete the following steps from the GitHub and GitHub Desktop Reference Guide:
1. Clone a remote repository to your local machine

Complete the following steps from the VS Code Reference Guide:
1. Install Visual Studio Code
2. Install the recommended extensions (all of them)
3. Under Tips for speeding up your coding, follow the instructions to turn on word wrap and disable auto-closing HTML tags.

You are now completely set up and can complete the instructions in step 2 but you need to have done the week 1 reading to know how to add the required content to your assignment.
### Step 2: Required content
At the minimum, a website is a repository that includes a file called index.html (the website’s homepage), a file called style.css (where all the CSS is located), and a folder to store the images.
Your repository also includes the assignment readme file. You don’t have to delete the readme file, it does no harm and wouldn’t be visible when visitors view the website through a browser, but know that the readme file wouldn’t be present in a real website’s folder.

In VS Code:
* Read “Add files to your website folder” in the “VS Code Reference Guide”. In your local Assignment A repository, create a new file called index.html, a file called style.css and a folder called images. 
* Read “Add skeleton code” in the “VS Code Reference Guide”. In VS Code, open index.html and add the HTML skeleton code. Add a comment in the head section of the html code including: the term, course code, section number, student name, and the assignment letter. Example:
`<!-- F22 DGL 103 DLU1 - Claire Guiot - Assignment A -->`
* Reference the stylesheet by adding `<link rel="stylesheet" href="style.css">` in the head section of index.html
* Change the page title to assignment A.
* Add the following code where you believe it belongs:
`<h1>Hello World</h1> <p>This is *your name* speaking.</p>`. Make sure you save the document. Note: In VS Code, if the file name in the tab at the top of the window has a white circle next to it then the file includes edits that have not been saved yet.
* Check out what your web page looks like by opening index.html in a web browser: Right-click anywhere in the file > Open in Default Browser (if you don't see this option then you haven't installed the Open in Browser VS Code extension yet - see above). I recommend making Google Chrome your default browser (https://support.google.com/chrome/answer/95417?hl=en&co=GENIE.Platform%3DDesktop).
* Back in VS Code, change the colour of the HTML p element by adding `p {color: orange;}` to the style.css file. Go back to your browser and refresh the page to see the edit. If you can't see the change in colour in your browser then there is an issue with the way you linked the CSS file to the HTML file.
* Change the colour of the HTML H1 element to anything you like.
* Now we’re going to include an image in your webpage. Add an image file to the images folder in your local repository. It can be any image you like but most popular browsers support: BMP, SVG, JPEG, JPG, PNG and GIF image file extensions. Name the image with a filename that makes sense, for ex: smalldog.jpg
* In index.html, add the image below the paragraph content. For ex: `<img src="images/claire-profile.jpg" width="600" alt="Claire Guiot">`. Change the image file name in the src attribute and the image description in the alt attribute to match the file that you added to the images folder. Note that the `<img>` tag is self-closing, it doesn’t need an end tag. Save and go back to your browser and refresh the page to see the edit. If you can’t see the image then the link might be broken, make sure that you’ve used the correct filename and path.
* Commit your changes to your local repository - See the GitHub and GitHub Desktop Reference Guide.

### Step 3: Validate your work
1. Go to https://validator.w3.org/#validate_by_upload 
Choose your index.html file in your local repository and click the Check button. If there are no errors then you should see a green message that says “Document checking completed. No errors or warnings to show.” If you get an error message then troubleshoot your work until you get the green message. 
Take a screenshot of your HTML validation results. 
2. Go to https://jigsaw.w3.org/css-validator/#validate_by_upload 
Choose your style.css file in your local repository and click the Check button.
If you get the green “Congratulations! No Error Found.” then take a screenshot of the screen. If not, troubleshoot your work until you get the green message when you validate it.

### Step 4: Submit your work
Complete the following steps from the GitHub and GitHub Desktop Reference Guide:
1. Commit your changes if you’ve made changes since the last commit.
2. Push your changes to GitHub. Check out your remote repository in GitHub to make sure that it looks the same as your local repository.
3. Submit your assignment in BrightSpace:
You can access the assignment submission tool by navigating to the week’s assignment in the Content Area, or by clicking on Assignments in the main menu. 
    * Click on "Assignment A Submission" and follow the provided instructions. 
    * Don’t forget to answer the questions and attach the screenshots of your final W3 HTML and CSS validation results.
4. If you have been using a lab computer on campus to do your work with GitHub Desktop, remember to shutdown or restart the computer before you leave the room, so that other students won’t have access to your repositories.

Note: After you have submitted this assignment we will do a group code review to help troubleshoot any issues that you ran into. 

## Deadlines
Assignments must be submitted before the end of the week (before the next week’s class) but they will only be graded at the end of every unit. Late assignments will not be accepted and will receive an F. You can complete and submit a contract that allows you to extend the deadline for an assignment but you must email it to your instructor a minimum of 48 hrs before the deadline. Deadline extensions are only allowed for those unplanned, unexpected emergencies that life sometimes throws at us, and they will only be approved by your instructor if you follow the correct process. See the Course Info folder in BrightSpace for more info.
