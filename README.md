CST 3145 - Coursework 1
MARKING GUIDELINES FOR THIS PROJECT:
Additional requirements
The code must be stored in a GitHub repository with at least 10 commits;
The app must be available online using GitHubP ages;
Display lessons
– There should be at least 10 lessons and each lesson has 5 spaces;
– Each lesson should have at least: subject, location, price, space (how many spaces are left), a Font Awesome icon, and an image.
– The list of lessons must be stored as an array of JSON objects, one object for each lesson, in a separate JavaScript file, such as lessons.js;
– v-for has to be used for the display of the lesson list.
Maximum score4
Sort
– User can choose to sort the lessons by one of the following attributes: subject, location, price, or availability;
– There must be an option to sort in ascending or descending order, regardless of the attribute selected;
Maximum score4
Add to cart
– Each lesson must have a ’Add to Cart’ button;
– The button is only enabled when there is still space available;
– Clicking the button once will add one space to the shopping cart, reducing the remaining space by one;
– Once there is no more space, i.e., space = 0, the ’Add to cart’ button should be disabled but still visible, i.e., clicking it will not further reduce ‘space’ or add a lesson to the cart.
Maximum score4
Shopping cart
– The shopping cart button should only be visible after at least one lesson is added to cart;
– Clicking the shopping cart button should show the cart, and clicking the button again goes back to the lesson page;
– The shopping cart should show all the lessons added;
– User should be able to remove lessons from the shopping cart; the removed lesson is added back to the lesson list.
Maximum score4
Checktout
– The checkout is part of the shopping cart page;
– A user must provide ‘Name’ and ‘Phone number’ before he/she can check out;
– The ’Name’ must be letters only and the ’Phone’ must be numbers only; only; the check
must be done using JavaScript (hint: regular expressions);
– The ’checkout’ button is only visible after both valid ’name’ and ’phone’ are provided;
– Clicking the ’checkout’ button should display a message confirming the order has been submitted.
Maximum score4
Search
– This is the challenge component of this coursework, and it is not expected that everyone can complete it. The solution is not covered in the lecture or lab, so you need to research it.
– The goal is to add a full-text search feature, so user can search for a lesson without specifying which attribute to search on. For example, searching for ‘a’ should return all the lessons with ‘a’ in its title or location (‘price’ and ‘availability’ only have numbers so don’t apply here).
– Using existing library (2%): you can implement this feature using an existing JavaScript library (does not have to be a Vue.js library), in which case you receive maximum 2 marks.
– Writing your own search function (4%): you will receive maximum 4 marks if you write your own search function, which again does not have to use Vue.js.
– Search as you type (1%): in either case, you will get an additional 1 mark if the search supports ‘search as you type’, i.e., the search starts when user types the first letter (displaying all the lessons containing that letter) and the result list is filtered as more search letters are entered (similar to Google search).
Maximum score5