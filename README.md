Newsweek Homepage Clone by William Xia

Description: 
This project is a clone of the newsweek homepage using the html/css framework Bootstrap.

What I Learned:
From using bootstrap I learned that creating a grid based layout was very simple. All I needed to do was add classes to elements in order to make them appear smaller or larger based on the size of the screen. 

One issue I had was ordering the columns when the screen size became smaller. For example, one would naturally want the middle column,the main article, and largest column, to appear first on a mobile device. However, I circumvented this issue by creating a clone of the middle column, and putting it before the first column in the DOM. I set the display of the cloned column to zero when the screen was medium or larger. When the screen size became small, the cloned column became visible, and the middle column was set to display:none.
