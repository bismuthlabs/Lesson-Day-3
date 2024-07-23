# Exercise 1

## Objective
Students will create a visually engaging event invitation webpage reflecting Ghanaian culture using a variety of CSS properties and selectors. This assignment will focus on making an invitation page look festive and appealing, incorporating elements of Ghanaian culture.

Instructions:

# Step 1: Create the HTML Document
- Create a new HTML document with the basic structure:
```
<!DOCTYPE html>
<html>
<head>
    <title>Ghanaian Festival Invitation</title>
    <link rel="stylesheet" href="invitation-styles.css">
</head>
<body>
    <header>
        <h1 id="event-title">You’re Invited to the Ghanaian Cultural Festival!</h1>
    </header>
    <section id="details">
        <h2>Event Details</h2>
        <p class="info">Join us for a celebration of Ghanaian culture, with traditional music, dance, and food!</p>
        <ul class="details-list">
            <li><strong>Date:</strong> September 21, 2024</li>
            <li><strong>Time:</strong> 4:00 PM - 10:00 PM</li>
            <li><strong>Location:</strong> Independence Square, Accra</li>
        </ul>
    </section>
    <section id="rsvp">
        <h2>RSVP</h2>
        <p class="rsvp-text">Please let us know if you can join us for this joyous celebration!</p>
        <button class="rsvp-button">RSVP Here</button>
    </section>
    <footer>
        <p>&copy; 2024 Ghanaian Festival Committee. All rights reserved.</p>
    </footer>
</body>
</html>

```

# Step 2: Create the External CSS File
- Create a new CSS file called invitation-styles.css in the same directory as your HTML file.
In invitation-styles.css, add the following CSS rules to style the elements:
``` 
/* Style for the event title */
#event-title {
    color: green;
    text-align: center;
    font-family: 'Arial Black', Gadget, sans-serif;
    margin-top: 20px;
    background: linear-gradient(to right, #FFB100, #F8931D); /* Ghanaian flag colors */
    padding: 10px;
    border-radius: 10px;
}

/* Style for the event details section */
#details {
    text-align: center;
    margin: 20px;
}

.info {
    background-color: lightyellow;
    padding: 15px;
    border: 2px solid gold;
    border-radius: 5px;
    font-style: italic;
}

.details-list {
    list-style-type: none;
    padding: 0;
    font-size: 1.2em;
}

.details-list li {
    margin: 10px 0;
}

/* Style for the RSVP section */
#rsvp {
    text-align: center;
    margin: 20px;
}

.rsvp-text {
    background-color: lightblue;
    padding: 10px;
    font-weight: bold;
    border: 2px solid deepskyblue;
    border-radius: 5px;
}

.rsvp-button {
    background-color: deepskyblue;
    color: white;
    border: none;
    padding: 10px 20px;
    font-size: 1em;
    border-radius: 5px;
    cursor: pointer;
}

.rsvp-button:hover {
    background-color: dodgerblue;
}

/* Style for the footer */
footer {
    text-align: center;
    padding: 10px;
    background-color: darkred;
    color: white;
    position: fixed;
    width: 100%;
    bottom: 0;
}

```


# Step 3: Link the CSS File
- Ensure your HTML file correctly links to the invitation-styles.css file by including the following line within the <head> section of your HTML document: 
``` <link rel="stylesheet" href="invitation-styles.css"> ```

# Step 4: Test Your Webpage
- Save your HTML and CSS files.
- Open your HTML file in a web browser to see the styled elements.

Ensure that: 
- The event title has a gradient background in Ghanaian flag colors and festive colors
- The event details are centered with a golden border
- The RSVP section includes a button that changes color on hover 
- And the footer is styled with a fixed position at the bottom of the page.


# Additional Challenge (Optional):
- Add an image of traditional Ghanaian art or kente cloth to the webpage and position it creatively using CSS.


--------------------------------------------------------------------------------------------------------------------------------------------------------------
--------------------------------------------------------------------------------------------------------------------------------------------------------------
--------------------------------------------------------------------------------------------------------------------------------------------------------------