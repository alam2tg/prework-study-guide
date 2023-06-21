# <Prework Study Guide Webpage>

## Description
I created this site to learn the basics of coding, and how coding can turn my ideas into reality (or digital reality). My motivation was to learn I could code with hands-on activity. 
I built this website to learn how to use multiple coding languages, and combine the code into a succinct manner using various tools. Gitbash (CLI / command-line interface), VS Code, and Github
It taught me how to build a website with text, formatting, color, and images.  I did this by using HTML, CSS, and Javascript.
Overall, I learned the basics of how coding functions work, what coding languages are used for different outcomes, and how to combine a project together.

## Installation

The steps to install a project involve using VS Code to write our code in HTML, CSS, and Javascript. HTML structures and writes the content of the website, CSS creates the style/design, and Javascript to create functions, debug, and inspect our website. We then used the CLI to organize our project by making different folders and connect to Github branches. Github allows us to break-down or project into multiple steps, and work on each steps without affecting our main code via the use of branches. We can write code on branches, then merge the information together later if there are no bugs. 

Below are the chronological steps I took to complete this project.

Step 1.0
    Download VS Code and Gitbash

Step 2.0
    Make a Github account
Step 2.1
    Create a new repository 
Step 2.2 
    Create a workflow in Github breaking down the steps of project under "issues".  
Step 2.3
    Create issues by clicking "new issue", and prefixing titles with '#', and headers with '##'

Step 3.0
    Open Gitbash's command-line interface 
Step 3.1 
    Use Gitbash to navigate to correct folders using command 'cd' then 'folder name'
Step 3.2 
    Create a new branch on the Gitbash command line using 'git checkout -b <branch name>'. You will want to create the following <branch names>... 
    feature/add-html
    feature/add-css
    feature/add-js
Step 3.3 
    Create new files in correct folders using command 'touch' then 'style.css' for CSS and 'script.js' for Javascript.
Step 3.4 
    Use cd to navigate to feature/add-html. Open VS Code on the CLI using 'code .' 

Step 4.0
    Create a .HTML file to write text of website, specifying the Header, Body, and Footer
Step 4.1 
    Use VS Code to add your content/notes to the Header, Body, and Footer on the HTML file. 

Step 5.0 
    Complete your Git workflow by doing the following.
        1. Opening gitbash and adding changes using...
            git add -A
        2. Commit changes from VS Code to Github ...
            git commit -m "message describing code added"
        3. Merge main branch with udpated feature branch on your local repository using...
            git pull origin main 
            If the response is "Already up to date"... continue
        4. Merge main branch with udpates to the remote repository on GitHub using...
            git push origin feature/add-html
        5. Go to Github and under tab "Pull Request" click "New Pull Request".
        6. This will create the pull request. After reviewing code, merge the feature branch with main      branch.
        7. Check Github to confirm the file you added is there. In this case, it will be the HTML file.

Step 6.0
    Navigate to style.css on Gitbash, then change branches to feature/add-css
Step 6.1
    Use CSS code to add style to the website
Step 6.2
    Link the CSS file to the HTML file
Step 6.3
    Use gitbash workflow to add, commit, and merge changes. 

Step 7.0
    Navigate to script.js on Gitbash, then change branches to feature/add-JS
Step 7.1
    Add Javascript code to add interactivity to website
Step 7.2
    Link the Javascript file to the HTML file
Step 7.3
    Use gitbash workflow to add, commit, and merge changes. 


The steps to install a project involve using VS Code to write our code in HTML, CSS, and Javascript. HTML structures and writes the content of the website, CSS creates the style/design, and Javascript to create functions, debug, and inspect our website. We then used the CLI to organize our project by making different folders and connect to Github branches. Github allows us to break-down or project into multiple steps, and work on each steps without affecting our main code via the use of branches. We can write code on branches, then merge the information together later if there are no bugs. 

## Usage
To Use this study guide, you can review the notes in each section based on the title. The title should act as a guide to workflows that you want to learn more about. 

## Credits

https://github.com/mhogle25

## License

MIT License

Copyright (c) 2023 Aaron

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.

---