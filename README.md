Introduction

Learn to use the popular package async via this interactive workshop.

Hopefully by the end this workshop you will understand the main functions that async provides.
Installation

    Install Node.js
    Run npm install async
    Run npm install async-you -g , use sudo if you have permissions issues.
    Run async-you to start the program!

Usage
1. Selecting a problem to work on

Once the workshop is installed, run async-you to print a menu where you can select a problem to work on.

$ async-you

Problems are listed in rough order of difficulty. You are advised to complete them in order, as later problems will build on skills developed by solving previous problems.
2. Writing your solution

Once you have selected a problem, the workshop will remember which problem you are working on. Using your preferred editor, simply create a file to write your solution in.
3. Testing your solution

Use the workshop's run command to point the workshop at your solution file. Your solution will loaded and passed the problem input. This usually won't perform any validation, it will only show the program output.

$ async-you run mysolution.js

4. Verifying your solution

Your solution will be verified against the output of the 'official' solution. If all of the output matches, then you have successfully solved the problem!

$ async-you verify mysolution.js
