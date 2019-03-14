# Pie
One-page locally hosted site to practice arrays and buttons in Javascript.

## Screenshots
![image of pies website](https://raw.githubusercontent.com/bobbybaxter/pie/master/img/pie-screenshot.png)

## Getting Started
Clone the repo:
```
$git clone https://github.com/bobbybaxter/pie
```

### Prerequisites
Download HTTP Server, to be able to serve the site locally in your browser:
```
$npm install -g http-server
```

## Running
Browse to pie directory and run Http Server by typing the following command into the terminal:
```
$ hs -p 5000
```

In your web browser, copy and paste this:

 `localhost:5000`

 ## Explanation
 In **main.js**, we've first defined an array of pies with `const pies`.

 Next, we've written a helper function to print output to the webpage with `const printToDom`.  This works by assigning the text we want to print to the element in the HTML file with the ID tag we specify when calling the function.
 
 Then, we've written a function to build cards out of each of our array items with `const buildPieCards`.  We use a `.forEach` method on the specified array parameter to loop through all of the array items, build a `<div>` element with the pie's name and image, then print to the page using our `printToDom` function.

 *Note: commented out is a simplified version of the above code using a for loop instead of a `.forEach` method.*
