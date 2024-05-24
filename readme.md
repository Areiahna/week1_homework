Steps to creating a gitRepo 

#1 ---- Login to github & click "Dashboard" next to github logo in the upper left corner. There should be a big green button that says "New" underneath the words "Dashboard".Click on it...

#2 ---- Name your repo. I HEAVILY reccomend leaving a description for your sake & others. Something short & straight to the point.
    - ALWAYS make repos PUBLIC for instructors to view
    - DO NOT add README or gitIgnore files (you can do that yourself (better practice))
Scroll down & click big green button that says "Create repository"

#3 ---- Page should have reloaded & display a "Quick Setup" guide highlighted in BLUE. From that copy the SSH key

*The following steps are to be completed in the terminal*

#4 ---- cd into directory of project 

#5 ---- "git init"
 (*this will initialize that directory*)

#6 ---- git remote add origin [SSH KEY]

#6 ---- git add .
    (*It is important to add the "." because it will add everything in the current directory to your repo!*)

#7 ---- git commit -m "[ENTER MESSAGE]"
    (*MUST ADD MESSAGE describing what your pushing to the repo! "First commit" is always a go to for your initial commit"*)

#8 ---- git push origin main



