## 1) If you are collaborating with a classmate what is the first thing that each of the team members needs to do? Why is it important to do this step?

When you are collaborating with a classmate the first thing that each member needs to do is after they make their own codespace is make their own branch. It is important to make your own new branch because it keeps everything much more organized and so nobody edits the main branch. The main branch is only impacted later on when everybody reviews each others work to merge it.

## 2) Why do developers use branches? 

 Developers use branches in order to not impact the main branch when working on a project.

## 3) What is git? What is github? How does git and github work together?

Git is a command line tool and git hub is a platform where you *use* git and you're able to store repos in the cloud and collaborate with other developers. Git and github work together because git is the command line tool that github has for it's users.

## 4) What is wrong with the following command sequence? What should be the correct command sequence?

    git commit -m "saving work"
    git add .
    git push
    
The problem with the command sequence above is that they did git `commit -m "saving work"` before `git add .` The order should be:

    git add .
    git commit -m "saving work"
    git push