# Prevent Default Lab

# Objectives
+ Use `preventDefault()` to stop unwanted default browser behavior

## Intro

You are going to be building a mini single page to-do list app. You'll want to use preventDefault to prevent the form submission from refreshing the page. Remember, this app is only running client-side code. We don't have a database, so if that page refreshes, you'll lose all your items on your list.

## Instructions

You'll be coding your solution in `js/script.js`. We've already built out the HTML for you in `index.html`.

You'll need to define a function `submitForm` which binds a `submit` event to the form. The event should add the user's input to the list. You'll want to make sure the page doesn't refresh so that you can add multiple items to the list.  The function should be defined outside the document ready and called inside of it.

There are tests, so make sure your work passes the tests!