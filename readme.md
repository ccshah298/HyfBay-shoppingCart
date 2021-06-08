# Readme
Continue work on your homework regarding the Hyfbay from previous week. Please copy the files from last week into this weeks hyf-homework folder and continue working there. If you have not made last weeks homework the solution for it is included in this weeks homework folder in the main.js file.

Filter products
A very normal usecase for a product site is that a user wants to search for some product or find products that are cheaper than a set price. Lets implement that functionality for a user!

BUT first lets figure out what happens on a conceptual level, when a user filters some products:

Some kind of event happens, fx a user searches for a product, we need to listen for that event
When that event happens we need to filter the products the user wants
Then we should render those products
Lets get a little closer to javacript:

.addEventListener on an element
.filter on the products array
renderProducts with the filtered array
Searching for products
A user needs to search for products. That means that we need to add an input element to the html.

When the user writes something in the search input field. The products should be updated to only include the products that match the name.

So what event should we listen for in the addEventListener method? And what element should we listen on?

Use the overview shown above and the renderProducts function.
Filter products based on max price
Lets help a user to find cheap products! When the user writes a maximum price the products should be filtered to match that maximum price

Hint: Break this task into smaller tasks!
Make the website look nicer!
The website looks awful now, but luckily you have had css and html and know exactly what it takes to make this website shine!

Improve it how you see fit. Maybe add a footer, header, logo, title, styling, responsivity. Whatever you feel like would improve the site!

Create some extra feature
No matter how small or how big. Create some feature that would be cool/helpful/quirky/funny.

Sort the products - optional
This task is more open ended! So you need to come up with fx how the user should interact with the functionality.

Give the user the possibility to sort the products. That could fx be on price, name, rating or all of the above!

