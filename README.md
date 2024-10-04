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

Why does this code create overflow of the background color          
 <div class="form-group text-center my-2"  style="background: lightblue; padding-right:135px;">
answer: In simpler terms, if the width of the element plus 135px of right padding exceeds the available width of the viewport or the container, the element will overflow and cause horizontal scrolling.

why is my padding not working               
class="form-group text-center pr-5"
To use the pr-5 class effectively, you need to ensure that the element you're applying it to is within a container that has a fixed width or is part of a Bootstrap grid layout.

answer: Padding on Block-Level vs Inline Elements: Padding works better on block-level elements (like div), but the content inside .form-group (the radio button and label) are inline elements. Inline elements don't respect padding the same way block-level elements do, so it might not be obvious.

I am not able to put two form inputs next to each other and i dont know what is causing the issue?
bruh, i just had to take out the form out of the form-row

why does form-check-input make it inline but not form-check, what is the difference between form-check-input and label

When you use the w-50 class, Bootstrap directly sets the width to 50%. However, for other percentages, like 80%, you don't have a predefined Bootstrap class to handle that, so you need to use inline styles or a custom class.

use ps intsead of pl-5 for bootstrap 5

My form inputs were overflowing so i did form-control-small ang changed their col width

flex-column and justif-content center interferring with each other 

why is my img-fluid not working for index.html

## New Information

Cards assume no specific width to start, so they’ll be 100% wide unless otherwise stated. You can change this as needed with custom CSS, grid classes, grid Sass mixins, or utilities.

