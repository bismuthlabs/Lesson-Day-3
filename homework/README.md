# Homework 1

## Objective
Students will create a webpage using a variety of CSS properties and selectors to style HTML elements, reinforcing their understanding of how CSS is used to enhance web page aesthetics and usability.

Instructions:

# Step 1: Create the HTML Document
- Create a new HTML document with the basic structure:
```
<!DOCTYPE html>
<html>
<head>
    <title>My Styled Webpage</title>
    <link rel="stylesheet" href="homework-styles.css">
</head>
<body>
    <h1 id="main-heading">Welcome to My Styled Webpage</h1>
    <p class="intro">This is an introductory paragraph about my webpage. CSS makes styling easy!</p>
    <ul>
        <li>Item 1</li>
        <li>Item 2</li>
        <li>Item 3</li>
    </ul>
    <div class="content">
        <h2>Subheading</h2>
        <p>This is another paragraph inside a div element. It has its own styles.</p>
    </div>
    <img src="your-image-source.jpg" alt="A description of the image">
</body>
</html>
```

# Step 2: Create the External CSS File
- Create a new CSS file called homework-styles.css in the same directory as your HTML file.
In homework-styles.css, add the following CSS rules to style the elements:
``` 
/* Style for the main heading */
#main-heading {
    color: purple;
    text-align: center;
    margin-top: 20px;
}

/* Style for the introductory paragraph */
.intro {
    background-color: lightgrey;
    padding: 10px;
    font-style: italic;
}

/* Style for the list items */
ul li {
    color: red;
    font-weight: bold;
}

/* Style for the content div */
.content {
    border: 2px dashed blue;
    padding: 15px;
    margin-top: 20px;
}

/* Style for the subheading within the content div */
.content h2 {
    color: darkgreen;
    text-decoration: underline;
}

/* Style for the paragraph within the content div */
.content p {
    color: darkblue;
    background-color: lightyellow;
    padding: 10px;
}

/* Style for the image */
img {
    border: 2px solid black;
    display: block;
    margin: 20px auto;
}
```


# Step 3: Link the CSS File
- Ensure your HTML file correctly links to the homework-styles.css file by including the following line within the <head> section of your HTML document: 
``` <link rel="stylesheet" href="homework-styles.css"> ```

# Step 4: Test Your Webpage
- Save your HTML and CSS files.
- Open your HTML file in a web browser to see the styled elements.

Ensure that: 
- the heading is purple and centered 
- The introductory paragraph has a lightgrey background with italic text 
- The list items are red and bold 
- The content div has a dashed blue border 
- The subheading inside the content div is dark green and underlined 
- The paragraph inside the content div has dark blue text on a light yellow background 
- And the image has a solid black border and is centered.


--------------------------------------------------------------------------------------------------------------------------------------------------------------
--------------------------------------------------------------------------------------------------------------------------------------------------------------
------------------------------------------------------------------------------------------------------------