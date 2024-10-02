# Capstone_E-commerce-Website



## Git Issues
I created a respository and added a readme file. Then I created a local repo and created html files. When I tried to push my code to github it hit me with fatal: refusing to merge unrelated histories. This was because the remote and local repo had no shared history. So i did git merge origin/main --allow-unrelated-histories to merge everything. I could have rebased but it's only a readme file. Then I was able to push my code into my remote repo. 

I don't know why I created a master branch, maybe during the commit process, i was not able to push so i created a seperate branch. I will delete the branch, eventually. 

I tried to pull my code from github but it did not allow me. It said 
```json
There is no tracking information for the current branch.
Please specify which branch you want to merge with.
See git-pull(1) for details.

    git pull <remote> <branch>

If you wish to set tracking information for this branch you can do so with:

    git branch --set-upstream-to=origin/<branch> main
```
so i just cloned it

When your git push does not work because of this error
! [rejected]        main -> main (non-fast-forward)
fatal: refusing to merge unrelated histories

git pull origin <branch-name> --allow-unrelated-histories
solution is to merge unrelated histories 

## Useful emmett shorcuts 
(div.className>label+input)*5
To create 5 <div> elements, each containing a <label> and an <input>, all with similar class names

## Issues I encountered 
Problem: So i have a file products in a folder pages, i have img in another folder assets. I am trying to call the image from my assets folder into my products page. I am using this path  ./assets/dog_collar.jpg
Solution:  ../ means "go up one folder," so you're moving up from the pages folder to the main project directory, then accessing the assets folder.


### Questions

Why should I use an a tag with btn class rather than a btn with a hyperlink attached to it ? 

w-40 causing overflow but not w-50? 

should i use fieldset or div to wrap my content in this code. <fieldset>





## New Information

Cards assume no specific width to start, so they’ll be 100% wide unless otherwise stated. You can change this as needed with custom CSS, grid classes, grid Sass mixins, or utilities.

