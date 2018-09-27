Files
    hello_world.html
    my_first_form.html

Exercises
Hello World
- Within the Codeup folder on your Desktop, create a file named hello_world.html.
- By hand (please do not copy and paste unless all this has been a review for you!), type out a complete HTML document using the example shown in the previous.
- Change the page title to something creative.
- Replace the comment in the body of the HTML document with text that says Hello from Codeup!.
- View the result in your web browser by dragging the hello_world.html file from your Codeup folder directly into your browser window.

HTML Elements
- Within the Codeup folder on your Desktop, open your file named hello_world.html.
- Add an empty `<div>` inside the body with an id attribute of "wrapper".
Add two paragraphs with a sentence in each. The first paragraph can be something about your favorite vacation spot. The second paragraph about your favorite - actor.
- Add a `<span>` around the first word in your first sentence. Does it cause the display of your page to be different? Do you know why?
- Add a break `<br>` somewhere in your second paragraph. Do the results look different in your browser?

Headings
- Open the hello_world.html file in your favorite editor.
- Experiment with the different heading levels by enclosing your "hello world" message inside heading tags. Notice that even without any styles in the page, the browser provides default styles for the heading elements.
- View the result in your web browser by dragging the hello_world.html file from your Codeupfolder directly into your browser window.
- When you are done experimenting with the heading levels, change the page so that you have your "hello world" message inside `<h1>` tags

Paragraphs
- Open the hello_world.html file in your favorite editor.
- Below the "hello world" heading, create a paragraph introducing yourself - and telling some fun facts about yourself. Use emphasis, strong emphasis, and line break elements within the paragraph. Below the paragraph, create a level 2 heading that says: "My Favorite - Quote". Below that heading, use the block quote element and paste in your favorite quote.
- View the result in your web browser by dragging the hello_world.html file from your Codeup folder directly into your browser window.

Lists
- Open the hello_world.html file in your text editor.
- Below your favorite quote, add a level 2 heading that says: "I'm Learning the LAMP Stack".
- Below the heading, create an unordered list that names each item in the LAMP stack.
- Below the unordered list, create another level 2 heading that says: "My Top 5 Favorite Foods".
- Below the heading, create an ordered list containing your top 5 favorite foods in order.
- Below the ordered list, create another level 2 heading that says: "Questions I'm Often Asked".
- Below the heading, create a definition list containing at least 2 questions you are often asked, along with the answers you generally give. Be creative.
- View the result in your web browser by dragging the hello_world.html file from your Codeupfolder directly into your browser window.

Anchors
- Open the hello_world.html file in your favorite editor.
- Within the body tags of the document, below everything else you have added, create a new level 2 heading that says: "My Favorite Websites".
- Below the heading, use either an ordered or unordered list to list your top 5 favorite websites. Make the names of the sites link to the sites by opening - them in a new window.
- Use what you learned in this lesson to create a "go to top of page" feature within your HTML document.
- View the result in your web browser by dragging the hello_world.html file from your Codeupfolder directly into your browser window.

Images
Open the hello_world.html file in your favorite editor.
Within the body tags of the document, below everything else you have added, create a new level 2 heading that says: "My Vehicle".
Below the heading, create a new paragraph describing the vehicle you own, or the one you dream about.
Browse the web and find an image of the vehicle you described and download the image.
Create a new directory, named img, in your Codeup folder.
Move the image you downloaded into the img directory you just created.
Use what you learned in this lesson to display the image in your web page right below the paragraph describing the vehicle.
View the result in your web browser by dragging the hello_world.html file from your Codeupfolder directly into your browser window.

Tables
- Open the hello_world.html file in your favorite editor.
- Within the body tags of the document, below everything else you have added, create a new level 2 heading that says: "Decimal to Hexadecimal Conversion Chart".
- Below the heading, create a table with a heading row with 2 columns: "Decimal" and "Hexadecimal". Next, create additional rows to show the conversion of the decimal numbers 0 through 15 to hexadecimal.
- View the result in your web browser by dragging the hello_world.html file from your Codeupfolder directly into your browser window.

Forms Intro
Within the Codeup folder on your Mac, create a file named my_first_form.html.
Open the file you just created in your favorite editor. Using what you have learned in the previous lessons, add the necessary HTML document structure to the page with a title of: "My First HTML Form".
Copy and paste the form example in this lesson into the body of your HTML document.
View the result in your web browser.
Next, open a new tab in your browser and go to RequestBin in order to generate a URL that you can send data to. RequestBin allows us to view GET and POST data without the help of a server.
Click 'Create A RequestBin' and copy and paste the generated URL into your `my_first_form.html` file to replace your original form action.
Below is an example. Your RequestBin URL will be unique, but will look very similar to the one below. For a thorough walkthrough of this process, please watch the video for this lesson!

`<form method="POST" action="https://request-inspector.glitch.me">`
Experiment with using the GET and POST methods by submitting the form and viewing the results in your browser. Refresh your RequestBin page to view the data there, too.
Try deleting the name attributes from the inputs and then submit the form. View the results in your browser. What do you observe? Repeat with the id attributes. What do you observe?

Inputs and submitting
- Open the my_first_form.html file in your favorite editor.
- Add placeholder attributes with appropriate values to both the username and passwordinputs.
- Try adding a name attribute to the `<input type="submit>`. Submit the form as a POST request and view the results in your browser.
- Add a value attribute to the `<input type="submit>` to change the button to say "Login". Try submitting the form and view the results in your browser.
- Replace the `<input type="submit>` with a `<button>` element and try submitting the form.
- From the browser, view the results from your file and the data from your RequestBin.

Text and Textarea
- Open the my_first_form.html file in your favorite editor.
- Add a new form below the existing form.
- Add inputs to the form that would allow a user to compose an email (to, from, subject, body, and a send button). Make sure to use the appropriate input types for each form element.
- Put headings above the forms. Label the first form as "User Login", and the second form as "Compose an Email".
- When complete, try submitting the new form and viewing the results on on both your file and your RequestBin page.

Checkbox and Radio
- Open the my_first_form.html file in your favorite editor.
- Add a checkbox to the "Compose an Email" form that asks a user if they want to save a copy to their sent folder. Make the checkbox checked by default.
- Try submitting the email form and view the results in your browser with and without the checkbox checked. What observations can you make?
- Add a new form below the existing forms with a heading of: "Multiple Choice Test".
- Add two or more question and answer sets using radio buttons. Experiment with the naming so that you understand how radio buttons are grouped.
- Try submitting the multiple choice test form and view the results in your browser with and without or without questions answered. What observations can you make?
- Add a question that has multiple answers using grouped checkboxes. Try submitting the form to your browser to see how the inputs work.
- Try removing the `<label>` elements from your checkboxes and radio buttons. Try clicking on the text next to the checkbox or radio button in the web browser. Notice the difference in behavior? Replace - the labels when you are done.
- From the browser, view the results from your file and the data from your RequestBin.

Select
- Open the my_first_form.html file in your favorite editor.
- Add a new form below the others with a heading of: "Select Testing".
- Create a basic select input that asks the user a yes or no question. Try defaulting the answer to yes, and then to no. Try submitting the form to your browser and view the results.
- Change the select input so that when yes is selected, a value of 1 is sent with the form data, and when no is selected, a value of 0 is sent. Try submitting the form in your browser and verify the results.
- Update the "Multiple Choice Test" you made in the last lesson. Add another multi-answer question and use a multi-select input to accept the answer. Try submitting the form in your browser and viewing the results on both your file and your RequestBin page.


CSS Intro
- Create an HTML file named css_intro.html within the Codeup folder on your Desktop.
- Create a folder named css in the same location as the html files you created.
- Inside the css folder, create a file named site.css.
- Use the sample code from the "External Stylesheet" section above to add content to the two files you created.
- View the results in your browser to test for the expected output.

CSS Selectors
- download css_selectors.html from https://www.filepicker.io/api/file/TEIJFmgQOSxmDVIYf87A. In your browser, choose "Save As" and name the file css_selectors.html
- Download css_selectors.html and save it in the Codeup folder on your Desktop.
- Create a folder called css inside the Codeup directory if you have not already done so.
- Download selectors.css from https://www.filepicker.io/api/file/3c2WdaBlRKm0NnEqGvQw. In your browser, choose "Save As" and name the file selectors.css
- Download selectors.css and save it in the css folder on your Mac.
- Open selectors.css in Sublime and replace all the "selector-todo"s with the appropriate selector based on the comment above.
- View the results in your browser.

Basic Properties
- Open up your hello_world.html file from your Codeup folder.
- Add a style to change the color of the headers on your page and make them underlined.
- Add a style to change the background color of the page.
- Add a style to add a background image to your page. Search how to manipulate the position, sizing of this background image.
- Add a style to change the list-style to something other than the default bullet.
- Add a style to change the font for the entire page. Use google fonts if you would like Google Fonts.
- Add a style to change the table, table cells td and rows tr padding and font sizes.
- Add a style to alter the anchor tags and its different states. (e.g. link, visited, hover and active).
- Continue experimenting with styles to increase the visual appeal of the page.

Box Model
https://codeup.teachable.com/courses/175793/lectures/2641630

- Create an HTML file named css_box_model.html within the Codeup folder on your Desktop.
- Title the page "Box Model Exercise".
- box_model.css within your css folder.
- Specifications:
    - Each colored box has a 1 pixel border.
    - The content area of each box is 150 pixels wide by 50 pixels high.
    - The overall size of each box is 172 pixels wide by 72 pixels high.
    - The orange box is indented by 30 pixels.
    - Each subsequent box is indented by 30 more pixels than the previous.
    - There are 10 pixels of space between the boxes.
    - The wavelength text is bold.
    - The header should link to the wikipedia article on the specified subject.

Positioning
- See https://codeup.teachable.com/courses/175793/lectures/2641632
- Create an HTML file named css_positioning.html within the Codeup folder on your Desktop.
- Copy the contents of the css_box_model.html lesson to the file you just created to use as the starting point.
- Title the page "Positioning Exercise".
- You will need to download the Codeup Ribbon and chevron images below to complete the assignment (Right click and save the images to your Codeup directory)
- Open https://www.filepicker.io/api/file/s6PgnjPFSkaubxRpuCiU and Save As codeup-arrow.png
- Open https://www.filepicker.io/api/file/K6BInA5DSsq0Qg3MrjXq and Save As codeup-ribbon.png
- Re-create the image shown here https://www.filepicker.io/api/file/GLENSvvwRXzRzStvUhJ8 as HTML by using the appropriate styling to meet the specifications provided below.
- Add the Codeup Ribbon image to the upper right corner of your page.
- Specifications:
    - No line breaks or paragraphs should be used. Use positioning, floats, and clears as appropriate.
    - Each colored box as a 1 pixel border.
    - The content area of each box is 50 pixels wide by 50 pixels high.
    - The overall size of each box is 72 pixels wide by 72 pixels high.
    - There is 50 pixels of space between the header and the boxes.
    - There is 50 pixels of space between the boxes themselves.
    - The Codeup arrow has been added to each box (download image below).
    - Bonus
        - There are several different ways to move the fourth box to the second line. Research the :nth-child pseudo class and use that to position the second row of boxes.
        - Rearrange the boxes so that they are in three rows of two. Your HTML should stay the same, and there should only be a small change to your stylesheet

JS Intro
    Open Google Chrome and then access the JavaScript Console. Next, execute the following statements:

    // declare a variable called test with a string value of "Hello Codeup"
    var test = "Hello Codeup";
    // print out variable values typing their name and hitting enter
    test <enter>
    // you should see the value of "Hello Codeup" displayed
    var name = "Codeup";
    typeof name;
    var almostPi = 3.14;
    typeof almostPi;
    var success = true;
    typeof success;
    var todoList = [];
    typeof todoList;
    var car = {};
    typeof car;
    var doSomething = function () {};
    typeof doSomething;
    var unassigned;
    typeof unassigned;
    var setToNull = null;
    typeof setToNull;

Booleans
- For this lesson, we will explore what values translate to true or false.
- In the Chrome JavaScript Console, execute the following statements:

    !true
    !false
    !!true
    !!false
    !!0
    !!-0
    !!1
    !!-1
    !!0.1
    !!"hello"
    !!""
    !!''
    !!"false"
    !!"0"
    Now, work through the following logical operator combination examples:
```
    /*
     * Perform the following steps for the statements below.
     *
     * 1) determine what you expect the answer to be.
     * 2) calculate the actual answer.
     * 3) add parenthesis to show expected order of operation.
     * 4) change parenthesis to cause result to be opposite of what it would normally be.
     */
    false && false || true
    true || !true && true && false
```

Exercises: Numbers
For this exercise, we will explore numbers.

In the Chrome JavaScript Console, work through the following examples:

// what do you expect the result of the following statement to be?
5 + 10 * 20;
// add parenthesis to the above statement to get a result of 300.
// execute the following statements:
var a = 1;
var b = a++;
var c = ++a;
// afterwards, what do you expect the values of a, b, and c to be?
// see if you were correct by typing the name of one of the variables and hitting enter.
// now try these. what do you expect to see?
var d = "hello";
var e = false;
d++;
e++;
// execute the following statements, what do you expect?
var perplexed; // perplexed is undefined (no value is assigned)
perplexed + 2;
// use the .toFixed() method display the price with 2 decimal places
var price = 2.7;
// perform the following experiments with the isNaN() function and the NaN constant:
isNaN(0)
isNaN(1)
isNaN("")
isNaN("string")
isNaN("0")
isNaN("1")
isNaN("3.145")
isNaN(Number.MAX_VALUE)
isNaN(Infinity)
isNaN("true")
isNaN(true)
isNaN("false")
isNaN(false)
// to illustrate why the isNaN() function is needed:
NaN == NaN


Exercises: Strings
Using the JavaScript console, execute the following statement, then perform the exercises below:

var sample = "Hello Codeup";
Use .length to calculate the number of characters in the string.
Try to make the sample string all upper or all lower case.
Update the variable sample via concatenation so that is contains "Hello Codeup Students".
Now, replace "Students" with "Class".
Find the index of "c" using .indexOf(), what do you observe?
Find the index of "C" using .indexOf().
Retrieve a substring that contains only the word "Codeup" by using indexOf() and substring().
Try parsing strings to numbers by executing the following:

parseInt("abcd1234");
parseInt("1234abcd");
parseInt("1,000");
parseInt("2.12");
parseInt("0");
parseInt("");
parseFloat("3.14");


Exercises: Javascript and HTML
For this lesson, perform the following tasks:

Within the Codeup folder on your Mac, create two HTML files. Name one inline_js.html, and the other external_js.html.
Create a folder named js in the same location as the html files you created.
Inside the js folder, create a file named external.js.
Use the sample code from this lesson to fill in the html files with the appropriate code.
Add a console.log message in inline_js.html that says "Hello from inline JavaScript".
Add a console.log message in external.js that says "Hello from external JavaScript".
Open the html files and view the JavaScript Console to make sure you see your messages.
Make sure to save your files regularly so that nothing gets unintentionally deleted!
Congrats! You now know how to embed JavaScript in a web page.


Exercise: If/Else
Please follow the instructions below.
Download https://www.filepicker.io/api/file/leCFGhoFSFy9rhXODdlB as if-else.js
Download if-else.js and save it to the js folder within your Codeup folder.
Create an HTML file named if-else-js.html within the Codeup folder on your Desktop.
Add a `<script>` tag to your HTML to link up if-else.js to your file.
Open if-else.js in Sublime and follow the instructions marked TODO:.
Remember to save your work!


Exercise: Switch 
- Download https://www.filepicker.io/api/file/OSdIIY1HTeN4p4j6tHES as switch.js
- We are going to re-build the last exercise using a switch instead of an if-else statement. Please follow the instructions below.
- Download switch.js and save it to the js folder within your Codeup folder.
- Create an HTML file named switch_js.html within the Codeup folder on your Desktop.
- Add a `<script>` tag to your HTML to link up `switch.js` to your file.
- Open switch.js in Sublime and follow the instructions marked TODO:.
- Remember to save your work!

Exercises: While Loops
Please follow the instructions below.

Create an HTML file named while_loop_js.html within the Codeup folder on your Desktop.
Use inline JavaScript to create a while loop that uses console.log() to create the output shown below.
2
4
8
16
32
64
128
256
512
1024
2048
4096
8192
16384
32768
65536

Exercises: For Loops
Please follow the instructions below.

Create an HTML file named for_loop_js.html within the Codeup folder on your Desktop.
Use inline JavaScript to create a for loop that uses console.log to create the output shown below.
Make sure to save your changes before continuing.
100
95
90
85
80
75
70
65
60
55
50
45
40
35
30
25
20
15
10
5

Exercises: Break and Continue
Please follow the instructions below.

Create an HTML file named break_continue_js.html within the Codeup folder on your Mac.
Use Math.floor((Math.random()*50)+1) to generate a random number between 1 and 50. If the number is not odd, keep getting a new random number till it is odd.
Use console.log to log all the odd numbers from 1 to 50, except the random odd number you generated, by using break and continue. Try to match the output shown below (your random number will be different).
```
    Finally, save your work and proceed to the next Lesson.
    Your output should look like this:
    Random odd number to skip is: 27
    Here is an odd number: 1
    Here is an odd number: 3
    Here is an odd number: 5
    Here is an odd number: 7
    Here is an odd number: 9
    Here is an odd number: 11
    Here is an odd number: 13
    Here is an odd number: 15
    Here is an odd number: 17
    Here is an odd number: 19
    Here is an odd number: 21
    Here is an odd number: 23
    Here is an odd number: 25
    Yikes! Skipping number: 27
    Here is an odd number: 29
    Here is an odd number: 31
    Here is an odd number: 33
    Here is an odd number: 35
    Here is an odd number: 37
    Here is an odd number: 39
    Here is an odd number: 41
    Here is an odd number: 43
    Here is an odd number: 45
    Here is an odd number: 47
    Here is an odd number: 49
```


# Exercises: Functions

- Download https://www.filepicker.io/api/file/PmbSElnxTOWL7RJXfw4Q as functions.js
- Download functions.js and save it to the js folder within your Codeup folder.
- Create an HTML file named functions_js.html within the Codeup folder on your Desktop.
- Add a `<script>` tag to your HTML to link up `functions.js` to your file.
- Open functions.js in Sublime and follow the instructions marked TODO:.
- Remember to save your work!

Exercises: User Interaction
- Download https://www.filepicker.io/api/file/IbW4eafSQTWAMAhrtQuq as user-interaction.js
- Download user-interaction.js to the js directory within the Codeup folder on your desktop.
- Create an HTML file named user-interaction.html in the Codeup folder.
- Make sure to include user-interaction.js with a `<script>` tag in user-interaction.html.
- Open user-interaction.js and follow the TODO listed there.
- Don't forget to save your work!

 Exercises: Arrays
- Download https://www.filepicker.io/api/file/oGiaBa0NRDKmGv25nFyW as iterating.js
- Download iterating.js and save it to the js directory of your Codeup folder.
- Create an HTML file named iterating_arrays_js.html within the Codeup folder.
- Add a `<script>` tag to your HTML to include iterating.js.
- Open iterating.js in Sublime Text and complete the TODO items there.
- View the results in your browser to test for the expected output.
- Remember to save your work and continue.

Exercises: Iterating
- Open the iterating.js file that you created in the last lesson.
- Modify the code that logs the names array elements individually to instead use a for loop.
- Below the for loop, use a forEach loop to print the names again.
- View the results in your browser to test for the expected output.
- Make sure to save your file before proceeding.

Exercises: Manipulating
- Download https://www.filepicker.io/api/file/6DdxIKqySmIQZoG0nqh7 as planets-array.js
- Download and save planets-array.js to the js directory in your Codeup folder on the Desktop.
- Create an HTML file named planets-js.html within the Codeup folder on your Desktop.
- Add a `<script>` tag to planets-js.html to include planets-array.js.
- Open planets-array.js in Sublime Text and follow the TODO items listed there.
- View the results in your browser to test for the expected output.

  Exercises: Splitting and Joining
- Download https://www.filepicker.io/api/file/FZ0j5SOHSEYwA87mseVA as planets-string.js
- Download planets-string.js to the js folder in your Codeup folder.
- Create an HTML file named split-join.html within the Codeup folder on your Desktop.
- Just as before, add a `<script>` tag to link planets-string.js to split-join.html.
- Follow the TODO items listed in planets-string.js, and view your results in the browser.
- Save your file before moving on.

