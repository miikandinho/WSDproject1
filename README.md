# Project 1: Shared shopping list

Name of the application is "Shared shopping lists". It has a main page, in which we can see
the name of the application, a link to the Lists-page, number of shopping lists and number of 
items in shopping lists.

When we click the link, we see a form which can be used to create new shopping lists. Under the form there are all active shopping lists as links. Shopping lists can be deactivated with a button. At the end of te page, there is a link that directs back to the main page.

When we click a shopping list, we see a page with a form to add new items into the shopping list. Under that we can see a list of all items in the shopping list. We can mark an item as collected, and then the name of the item will be striked through.


The app can be found from the site "".

If you want to use it locally, copy your credentials in the database.js file inside the 
"const sql = postgres({});". I don't know if you need credentials if you have docker and walking skeleton, but I am not able to use them so I used ElephantSQL.

Then, run "deno run --allow-env --allow-net --allow-read app.js" in the terminal.
