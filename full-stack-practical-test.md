# 1-Hour Practical Test: HTML5, CSS3, and JavaScript

## Part 1: HTML5 and CSS3 (20 minutes)

Create a responsive webpage with the following requirements:

1. Use HTML5 semantic elements to structure the page (header, nav, main, footer).
2. Create a navigation menu with 4 items.
3. In the main content, create a grid layout with 6 cards (2 rows, 3 columns on large screens).
4. Each card should contain an image placeholder, a title, and a short description.
5. Use Flexbox for the header to align the logo (can be text) to the left and the navigation menu to the right.
6. Make the layout responsive:
   - On medium screens (max-width: 768px), display 2 columns of cards.
   - On small screens (max-width: 480px), display 1 column of cards.
7. Use CSS Grid for the card layout and Flexbox for the card content.

## Part 2: JavaScript Fundamentals (20 minutes)

Write a JavaScript program that does the following:

1. Create an array of objects representing books. Each book should have properties: id, title, author, and year.
2. Use `let` to declare a variable `books` and initialize it with at least 5 book objects.
3. Use `const` to declare a function `filterBooks` that takes two parameters: the books array and a callback function.
4. Implement the following operations using array methods:
   a. Use `find` to get the book with id 3.
   b. Use `filter` to get all books published after 2000.
   c. Use `some` to check if there's any book published before 1900.
   d. Use `every` to check if all books have an author property.
   e. Use `map` to create an array of book titles.
   f. Use `reduce` to find the latest published book.

## Part 3: Advanced JavaScript (20 minutes)

1. Create a `Set` of unique author names from the books array.
2. Create a `Map` where keys are years and values are arrays of books published in that year.
3. Write a function `fetchBookDetails(id)` that returns a Promise. The promise should resolve with a book object after a 1-second delay (use `setTimeout`). If the book is not found, the promise should reject.
4. Use `Promise.all` to fetch details of three books simultaneously.
5. Implement a function `raceBookFetch` that uses `Promise.race` to fetch a book detail, but times out if it takes more than 2 seconds.
6. Create a generator function `bookIterator` that yields one book at a time from the books array.

Bonus (if time permits):
7. Use `Promise.allSettled` to fetch details of all books, handling both successful and failed requests.
8. Implement a function using `Promise.any` that tries to fetch a book detail from multiple unreliable API endpoints (simulate with timeouts).

