# example-repository
 Currently learning how to host a website on GitHub Pages by following the Flatiron School lesson.

First step was creating a repository folder by doing the following
"mkdir example-repository"
then getting into the file by using "cd" to confim it exits 
"cd example-repository"

Next, was creating the a new GitHub Repository on the GitHub Website by going to the "plus sign(+)" in the top right corner, creating a name, and a description if im feeling spicy. 

We contiune along the path of optaining a repository by adding the new remote to my local repo. This can all be done by copy pasting the following command lines,
echo "# example-repository" >> README.md
git init
git add README.md
git commit -m "first commit"
git branch -M main
git remote add origin git@github.com:LoopFruits/example-repository.git
git push -u origin main

This is where i will build and sucessfully publish a website. Over time i will be adding new code from what i've been learning and improve old code. 