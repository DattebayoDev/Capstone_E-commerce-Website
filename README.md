# Capstone_E-commerce-Website



## Git Issues
I created a respository and added a readme file. Then I created a local repo and created html files. When I tried to push my code to github it hit me with fatal: refusing to merge unrelated histories. This was because the remote and local repo had no shared history. So i did git merge origin/main --allow-unrelated-histories to merge everything. I could have rebased but it's only a readme file. Then I was able to push my code into my remote repo. 

I don't know why I created a master branch, maybe during the commit process, i was not able to push so i created a seperate branch. I will delete the branch, eventually. 

## Useful emmett shorcuts 
(div.className>label+input)*5
To create 5 <div> elements, each containing a <label> and an <input>, all with similar class names

## Issues I encountered 
Problem: So i have a file products in a folder pages, i have img in another folder assets. I am trying to call the image from my assets folder into my products page. I am using this path  ./assets/dog_collar.jpg
Solution:  ../ means "go up one folder," so you're moving up from the pages folder to the main project directory, then accessing the assets folder.


### Questions

Why should I use an a tag with btn class rather than a btn with a hyperlink attached to it ? 


## New Information

Cards assume no specific width to start, so they’ll be 100% wide unless otherwise stated. You can change this as needed with custom CSS, grid classes, grid Sass mixins, or utilities.

