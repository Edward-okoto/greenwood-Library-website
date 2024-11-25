# Greenwood-Library-website

## PROJECT OBJECTIVES 
Enhancing  greenwood community website-By adding a Book review section and updating the Events section

## INITIAL SET-UP
 1. We created a repository called the greenwood-library-website,made it public and added a README.md file.

 ![](./img/1.Greenwood%20repo.png)

 2.We cloned the repo into our local machine using git.

 ![](./img/2.Gitclone-URL.png)
 ![](./img/03.GitcloneOnVSC.png)

 TASK 

 1.We created about_us.html  contact_us.html  events.html  Home.html files on VSC and added content to these files

 ![](./img/5.Other_SECTIONS_on_VSC.png)

 2.Added the files to the staging area using the command `git add .`
   ![](./img/7.git%20add.png)

 note: Before adding files to the staging area,the files would show a red coloration in the working area when you run `git status` and after adding the files,it would be green coloration.

Before staging

 ![](./img/7.red%20color%20for%20files.png)

 After staging

 ![](./img/9.green%20color.png)

 3.Commit and push the files to remote repository
 use the `git commit -m 'created-website-file` and use `git push` respectively.
 ![](./img/11.Git%20commit.png) 
 ![](./img/10.Git%20push.png)

# CREATING A BRANCH

## Objective

 In this section,we will simulate how two developers working differently create/update files,commit,push and raise a PR request before their work are merged into the main line of development. 

 ## Procedure

 Developer 1.
 1. Create a branch `add-book-review`
 2. Switch to the branch
 3. Add a new file to represent the book review section and  update the file with content
 5. Stage,commit and push changes with message 'Book review'
 6. Push the `add-book-review` branch to github
 7. Raise a PR for the work
 8. Merge the work to the main branch

 ## Create a branch `add-book-review`
use the command `git branch add-book-review` to create the branch called add-book-review
![](./img/11.git-branch.png)

## Switch to the branch
Use the `git switch add-book-review` command to switch to the branch.

![](./img/12.git-switch.png)

## Add a new file to represent the book review section 
add a file called book_reviews.html using `touch book_reviews.html` command and add content

![](./img/13..new-branchfile.png)

##  Stage,commit and push changes with message 'Book review

Use `git add .` to stage the file
use  `git commit -m 'add book review section`
use  `git push` to push to main branch



 
 



 
