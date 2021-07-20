# Weather-Widget
Improved version of weather widget assignment

#Technologies used:
-HTML5.
-Bootstrap.
-SCSS / CSS.
-JavaScript.
-jQuery.

#Implementation:
-I used HTML to form the layout of the weather widget app like
where the api information was going to be displayed and in what containers.

-I used JavaScript and jQuery to fetch the Weather Map api data and display it in the 
container.

-I used Bootstrap to give the layout columns and rows as well as styling 
certain elements of the submit button.

-I used SCSS for most of the visual styles as well as adding breakpoint media queries for
better responsiveness. I came to the conclusion to remove the "Weather widget" header once it hit a certain screen size in order to give the user the full mobile experience, similary to how the iphone weather app doesn't have "Weather App" when you use it. 

#What I learned:
Although it might seem obvious and after a few minutes of struggling, I learned that the jQuery script has to go first/above the javascript file that is fetching the data.

I also learned that CSS media queries don't work the same way on SCSS, at least when used in combiation with Bootstrap. To solve this issue I had to create a mixin that had the same functionality as a media query.
