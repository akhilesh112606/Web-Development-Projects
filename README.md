# Web-Development-Mini-Projects - TOTAL (25)
## PROJECT - 1 : Movie Ranking Webpage (HTML)
## Algorithm

1. **Start** by creating an HTML document.
2. **Define** a `<h1>` header with the title "The Best Movies According to Akhil".
3. **Add** a `<h2>` subheader with the text "My top 3 movies of all-time." to introduce the list.
4. **Insert** a `<hr />` tag to create a horizontal line separator between the title and the movie entries.
5. **For each** movie in the list of top 3 movies:
   1. **Create** a `<h3>` header with the name of the movie.
   2. **Add** a `<p>` paragraph with a short description of why the movie is favored.
6. **End** the document.
<img width="731" alt="pic4" src="https://github.com/user-attachments/assets/ad1241a8-1c73-433c-8bbc-543d82535e98">

## PROJECT - 2 : Birthday Invitation Webpage (HTML)
## Algorithm
1. Start with the basic HTML structure containing headings, an image, and a list.
2. Identify the unordered list `(<ul>)`.
3. Replace the `<ul>` tag with an ordered list `(<ol>)`.
4. Keep each list item `(<li>)` the same.
5. Save and load the HTML to display numbered bullets instead of regular bullets.

<img width="716" alt="pic5" src="https://github.com/user-attachments/assets/0a67ca9a-1ebc-43ac-96c5-7cc729daab68">

##  PROJECT - 3 : Spanish Color Learner Webpage (HTML & CSS)
## Algorithm
1. Create an HTML file `(index.html)`.
2. Create a CSS file `(style.css)`.
3. Link the CSS file to the HTML file using `<link>` in the <head>.
4. In the CSS file, assign colors to each heading using their id.
5. Set all headings to have "font-weight: normal" using the .color-title class.
6. Set all images to be 200px in both height and width using the img selector.

<img width="272" alt="image" src="https://github.com/user-attachments/assets/0754ef86-2bae-4c24-bcb1-9303f6e990de">

##  PROJECT - 4 : Motivational Poster Webpage (HTML & CSS)
## Algorithm
1. Set up the HTML structure with a `<div>` containing the image and text.
2. Add CSS for styling the body, image, and headings.
3. Link Google Fonts for the Libre Baskerville font in the `<head>`.
4. Insert the image using the `<img>` tag.
5. Style the image with margin-left, margin-top, height, and a yellow border.
6. Set the color of the h1 heading to yellow and apply the Google font.
7. Style the h3 subheading with white color and the same font.
8. Set the body’s background color to black using CSS.
9. Ensure the external CSS file is linked in the <head> section.
10. Save and run the HTML file in a browser to display the styled content.

<img width="960" alt="pic4" src="https://github.com/user-attachments/assets/5c116fd0-8d2b-4c1d-8f3f-78227f825af1">

## PROJECT - 5 : Name Card Webpage (FLASK)
## Algorithm
1. **Initialize Flask Application**:
   - Import the `Flask` class from the Flask package.
   - Create an instance of the `Flask` application.

2. **Define Route**:
   - Set up the root URL route (`'/'`) with a function `greet()`.
   - Use the `render_template` function to return the `index.html` file when the route is accessed.

3. **Run Application**:
   - Use the `app.run(debug=True)` method to start the Flask server with debugging enabled if the script is run as the main program.

## PROJECT - 6 : Blog Website (FLASK)
## Algorithm
1. **Import Required Libraries:**
   - Import `Flask`, `render_template`, and `url_for` from the Flask framework.
   - Import the `requests` module for handling HTTP requests.

2. **Define Constants:**
   - Set `API_ENDPOINT` to the URL of the API that provides JSON data.

3. **Initialize Flask Application:**
   - Create an instance of the `Flask` class.

4. **Fetch Data from API:**
   - Use the `requests.get()` method to fetch data from the API endpoint.
   - Parse the JSON response and store it in `server_data`.

5. **Define Routes:**
   - **Root Route (`/`):**
     - Render the `index.html` template and pass `server_data` to it.
   - **About Route (`/about`):**
     - Render the `about.html` template.
   - **Contact Route (`/contact`):**
     - Render the `contact.html` template.
   - **Post Route (`/post/<int:index>`):**
     - Extract the post ID (`index`) from the URL.
     - Search for the post in `server_data` that matches the provided ID.
     - Render the `post.html` template and pass the matched post to it.

6. **Run the Application:**
   - Check if the script is run directly (i.e., `__name__ == "__main__"`).
   - Start the Flask development server by calling `app.run()`.



https://github.com/user-attachments/assets/4eb139bd-db16-4ee7-ad36-b48e9f6244d7

## PROJECT - 7 : To-Do List Web App (HTML, CSS, JS)

## Algorithm

1. **Start** by creating the HTML structure with a `<div>` container for the app.
2. **Add** an `<input>` field for entering new tasks and a button labeled "Add Task".
3. **Create** an empty `<ul>` list element to display the tasks dynamically.
4. **Style** the app using CSS to enhance visual appearance (e.g., layout, colors, completed task styles).
5. **In JavaScript**:
   1. **Select** the input, button, and list elements using `document.getElementById` or `querySelector`.
   2. **Add** an event listener on the "Add Task" button:
      - **On click**, get the input value.
      - **Create** a new `<li>` element with a `data-id` and task text.
      - **Append** it to the `<ul>`.
   3. **Attach** a click event to each `<li>` to:
      - **Toggle** a `completed` class using `classList.toggle()`.
      - **Optionally**, apply styles like `line-through` for completed tasks.
   4. **Add** a delete button in each `<li>`:
      - **On click**, use `e.stopPropagation()` to prevent bubbling.
      - **Remove** the task from the list.
6. **Store** tasks in `localStorage` (optional) to retain them after refreshing the page.
7. **Retrieve** and render stored tasks on page load.
8. **End** the script.
"""

<img width="534" height="356" alt="image" src="https://github.com/user-attachments/assets/cd78c526-2f45-4680-bfc3-726b5d064f86" />

## PROJECT - 8 : Weather Finder Web App (HTML, CSS, JS)

## Algorithm

1. **Start** by creating an `index.html` document with:
   1. An `<input>` element to enter the city name.
   2. A `<button>` with the text "Get Weather".
   3. Hidden `<div>`s for displaying weather data and error messages.

2. **Create** a `style.css` file to style the layout and hide elements using a `.hidden` class (`display: none`).

3. **Create** a `script.js` file and write JavaScript logic:
   1. **Wait** for the DOM to load using `DOMContentLoaded` event.
   2. **Grab** necessary DOM elements using `getElementById`.
   3. **Attach** a click event listener to the "Get Weather" button.
   4. **Extract** the city name from the input field and trim whitespace.
   5. **Use** `fetch()` to make an API call to OpenWeatherMap using the city name and API key.
   6. **If** the API responds with valid data:
      1. **Destructure** data like city name, temperature, and weather description.
      2. **Convert** temperature from Kelvin to Celsius.
      3. **Update** the DOM with city, temperature, and weather info.
      4. **Show** the weather info section and **hide** the error message.
   7. **If** the city is invalid or API fails:
      1. **Hide** the weather info section.
      2. **Display** an error message.

4. **Test** the application by entering valid and invalid city names.

<img width="397" height="273" alt="image" src="https://github.com/user-attachments/assets/baa9978c-d0ec-4285-876c-21c8dc7e414d" />

## PROJECT - 9 : Simple E-Commerce Web App (HTML, CSS, JS)

## Algorithm

1. **Start** by designing a basic HTML structure:
   - Use a `<div class="container">` to hold the entire content.
   - Add an `<h1>` for the "Products" heading and an empty `<div id="product-list">` where products will be dynamically added via JavaScript.

2. **Create** a section for the shopping cart:
   - Add an `<h2>` labeled "Shopping Cart".
   - Include a `<div id="cart-items">` to list cart items.
   - Use a `<p id="empty-cart">` as a placeholder for an empty cart message.
   - Create a hidden `<div id="cart-total">` to display the total price and a "Checkout" button once items are added.

3. **Style** the page using `styles.css`:
   - Apply styles for layout, spacing, button design, and visibility toggling using `.hidden` class.

4. **In JavaScript**:
   1. **Define** a list of products as objects with properties like name, price, and image.
   2. **Render** products in the `#product-list` dynamically using JavaScript DOM manipulation.
   3. **Add** a button to each product to allow adding items to the cart.
   4. **Handle cart state**:
      - Use an array to store added products.
      - Update the cart items list and total price dynamically.
      - Show/hide the `#cart-total` and `#empty-cart` based on cart contents.
   5. **Attach event listeners** to "Add to Cart" and "Checkout" buttons:
      - On adding, update the cart array and UI.
      - On checkout, clear the cart and display a thank-you message (optional).

5. **End** the script.

<img width="902" height="419" alt="image" src="https://github.com/user-attachments/assets/88388bbd-e1cf-4951-8a5a-c373fb61ed1d" />

## PROJECT - 10 : Number Adder (HTML, CSS, JavaScript)

## Algorithm

1. **Create** a basic HTML layout with a container and heading.
2. **Add** two number input fields (`num1`, `num2`).
3. **Place** an **Add Numbers** button to trigger calculation.
4. **Create** a result display area.
5. **Style** the UI using CSS for clean layout and icons.
6. **Use JavaScript** to:
   - Read input values
   - Convert them to numbers
   - Add them on button click
   - Display the result dynamically
7. **End**.
<img width="954" height="473" alt="image" src="https://github.com/user-attachments/assets/4ae324eb-b6f7-4814-813e-258b7bc956cd" />

## PROJECT - 11 : Guess the Number Game (HTML, CSS, JavaScript)

## Algorithm

1. **Create** a basic HTML structure with a container and heading.
2. **Display** instructions to guess a number between **1 and 10**.
3. **Add** a number input field for the user’s guess.
4. **Place** a **Guess** button to submit the input.
5. **Create** a result display area to show feedback.
6. **Style** the UI using CSS for a clean, centered card layout.
7. **Use JavaScript** to:
   - Generate a random number between 1 and 10
   - Read the user’s input
   - Validate the input
   - Compare the guess with the random number
   - Display appropriate feedback:
     - **Too Low** if the guess is smaller
     - **Too High** if the guess is larger
     - **Correct Guess** if the number matches
8. **Repeat** the process on every button click until the correct number is guessed.
10. **End**.
<img width="1894" height="940" alt="image" src="https://github.com/user-attachments/assets/5601d9e4-824a-4238-bce0-4b5f6192b6a8" />

## PROJECT - 12 : Profile Card Generator (HTML, CSS, JavaScript)

## Algorithm

1. **Create** a basic HTML structure with a container and heading.
2. **Add** a **Generate** button to trigger profile creation.
3. **Select** required DOM elements using JavaScript.
4. **Create** a function to generate a profile card dynamically.
5. **Inside the function**:
   - Create a `div` element for the profile card
   - Create an `img` element for the profile image
   - Create a heading element for the name
   - Create a paragraph element for the description
6. **Append** all created elements to the profile card.
7. **Insert** the profile card into the main container.
8. **Display** each new profile card below the previous one.
9. **Repeat** the process on every button click to generate multiple cards.
10. **End**.
<img width="565" height="729" alt="image" src="https://github.com/user-attachments/assets/44d05b46-dd57-4d64-86fe-a7743b976fea" />

## PROJECT - 13 : Loan Calculator (HTML, CSS, JavaScript)

## Algorithm

1. **Create** a basic HTML structure for the loan calculator interface.
2. **Add** input fields for:
   - Loan Amount
   - Annual Interest Rate
   - Loan Term (Years)
3. **Add** a **Calculate Loan** button to trigger the calculation.
4. **Select** all required DOM elements using JavaScript.
5. **Create** a function to calculate loan details.
6. **Inside the function**:
   - Read loan amount, interest rate, and loan term from inputs
   - Convert annual interest rate to monthly interest
   - Convert loan term from years to months
7. **Apply** the loan EMI formula to calculate the monthly payment.
8. **Calculate** the total payment and total interest.
9. **Display** the calculated values using animation for better user experience.
10. **Repeat** the process on every button click with updated inputs.
11. **End**.
<img width="1224" height="898" alt="image" src="https://github.com/user-attachments/assets/3fec5df6-59cf-4732-8b24-6899c0c0e18f" />

## PROJECT - 14 : Countdown Timer (HTML, CSS, JavaScript)

## Algorithm

1. **Create** a basic HTML structure for the countdown timer interface.
2. **Add** input fields for:
   - Target Date & Time
3. **Add** buttons for:
   - Start Countdown
   - Pause Countdown
   - Resume Countdown
   - Cancel/Reset Countdown
4. **Select** all required DOM elements using JavaScript.
5. **Create** a function to start the countdown.
6. **Inside the start function**:
   - Read the target date & time from the input
   - Calculate the remaining time in milliseconds
   - Validate that the date is in the future
7. **Create** a function to update the timer every second:
   - Convert remaining time to days, hours, minutes, and seconds
   - Update the respective HTML elements
8. **Add** Pause and Resume functionality:
   - Pause stops the timer without resetting remaining time
   - Resume continues the countdown from remaining time
9. **Add** Cancel/Reset functionality:
   - Stop the timer
   - Reset remaining time and display to zero
   - Disable/enable buttons accordingly
10. **Trigger** all actions via button clicks and repeat the process for new inputs.
11. **End**.

<img width="1227" height="688" alt="image" src="https://github.com/user-attachments/assets/7dea098f-3536-4375-a5be-4c3a62e60ccf" />

# PROJECT - 15 : Tip Calculator (HTML, CSS, JavaScript)
## Algorithm

1. **Create** a basic HTML structure for the Tip Calculator interface.
2. **Add** input fields for:
   - Bill Amount
   - Service Quality (Tip Percentage)
   - Number of People
3. **Add** output fields to display:
   - Tip Amount
   - Total Amount
   - Amount Per Person
   - Tip Per Person
4. **Select** all required input and output elements using JavaScript.
5. **Create** a function named `calculateTip()`.
6. **Inside the function**:
   - Read the bill amount, service percentage, and number of people.
   - Convert input values to numbers using `parseFloat`.
7. **Validate** inputs:
   - Ensure the bill amount is a valid finite number greater than zero.
   - Ensure the number of people is at least 1.
8. **Calculate**:
   - Tip amount using bill × service percentage.
   - Total amount by adding tip to the bill.
   - Per-person total amount.
   - Per-person tip amount.
9. **Format** all calculated values to two decimal places using `toFixed(2)`.
10. **Update** the respective HTML elements with calculated values.
11. **Attach** `input` event listeners to all input and select elements.
12. **Recalculate** the values automatically whenever the user changes any input.
13. **End**.

<img width="1666" height="892" alt="image" src="https://github.com/user-attachments/assets/211e0655-962d-4e41-bb14-208966779243" />

# PROJECT - 16 : Auto Typing Effect (HTML, CSS, JavaScript)
## Algorithm

1. **Create** a basic HTML structure containing an element to display the typing text.
2. **Add** a class (e.g., `.auto-type`) to the target element.
3. **Include** the Typed.js library using a CDN.
4. **Initialize** the `Typed` object in JavaScript.
5. **Provide** an array of strings to be typed dynamically.
6. **Set** typing speed using `typeSpeed`.
7. **Set** backspacing speed using `backSpeed`.
8. **Enable** looping to repeat the typing animation continuously.
9. **Add** a delay before backspacing starts.
10. **Customize** the cursor character.
11. **Enable** smart backspacing for smoother transitions.
12. **Render** the typing animation on page load.
13. **End**.
<img width="679" height="250" alt="image" src="https://github.com/user-attachments/assets/99049098-2e85-4b48-8274-d071ddfb0c4b" />

# PROJECT - 17 : PERCENTAGE CALCULATOR
## Algorithm
1. **Create** a basic HTML structure containing input fields for number and percentage, a calculate button, and elements to display results.
2. **Select** DOM elements using `getElementById` and `getElementsByClassName` for inputs, button, result displays, and error message.
3. **Define** a function `calculatePercentage()` to handle the calculation logic.
4. **Clear** any previous error messages at the start of each calculation.
5. **Parse** the input values from the number and percentage fields using `parseFloat()`.
6. **Validate** the inputs to ensure they are non-negative and the percentage is within 0-100 range.
7. **Display** an error message if validation fails.
8. **Calculate** the percentage amount using the formula: `(percent * amount) / 100`.
9. **Calculate** the final result by adding the percentage amount to the original number.
10. **Display** the percentage amount and final result in their respective HTML elements.
11. **Attach** a click event listener to the calculate button that triggers the `calculatePercentage()` function.
12. **End**.
<img width="566" height="314" alt="image" src="https://github.com/user-attachments/assets/d2e1a31a-e954-4808-964f-d8130d703694" />

# PROJECT - 18 : SAVINGS CALCULATOR
## Algorithm
1. **Create** a basic HTML structure with input fields for goal amount, current savings, and monthly contribution.
2. **Add** Feather icons library via CDN for input field icons and button styling.
3. **Select** all required DOM elements (inputs, button, progress bar, result container).
4. **Attach** a click event listener to the calculate button.
5. **Validate** user inputs ensuring all values are non-negative numbers.
6. **Display** an error message if validation fails and exit the function.
7. **Calculate** the remaining amount by subtracting current savings from goal amount.
8. **Calculate** the number of months needed by dividing remaining amount by monthly contribution.
9. **Update** the progress bar width based on the calculated percentage.
10. **Display** the result message showing months to reach goal or a success message if already achieved.
11. **End**.
<img width="613" height="462" alt="image" src="https://github.com/user-attachments/assets/24da5391-ac10-4f0b-ba8b-9b14f17c3068" />

# PROJECT - 19 : TO DO LIST
## Algorithm
1. **Initialize** global variables for the current filter state and load existing todos from localStorage.
2. **Create** a `saveToDo()` function to persist the todos array to localStorage.
3. **Create** a `renderToDo()` function to display todos based on the current filter (all, completed, pending).
4. **Filter** the todos array according to the selected filter before rendering.
5. **Generate** HTML elements dynamically for each todo with complete and delete action buttons.
6. **Create** an `addToDo()` function to push new tasks to the todos array and clear the input field.
7. **Create** a `toggleToDo()` function to switch the completed status of a todo item.
8. **Create** a `deleteToDo()` function to remove a todo item from the array using splice.
9. **Attach** event listeners to the add button, todo list (for delegation), and filter buttons.
10. **Render** the initial todo list on page load by calling `renderToDo()`.
11. **End**.
 <img width="524" height="401" alt="image" src="https://github.com/user-attachments/assets/c05c2e5d-3eca-4c94-b03d-e0182f19f740" />

# PROJET - 20 : QUICK PORTFOLIO
## Algorithm
1. Initialize responsive navigation bar for seamless user experience.
2. Render header section with dynamic introduction and call-to-action.
3. Display profile image and about section with concise bio.
4. Organize skills into visually distinct cards with icons.
5. Present recent works in a grid layout with project images and links.
6. Implement smooth scrolling for navigation links.
7. Validate contact form fields before submission.
8. Use external fonts and icons for modern UI aesthetics.
9. Ensure mobile-friendly design with adaptive layouts.
10. Add interactive menu button for mobile navigation toggle.
<img width="1908" height="4896" alt="image" src="https://github.com/user-attachments/assets/0009e579-94b4-48db-aef1-f86b2ef6a005" />

# PROJECT - 21 : AWESOME POSTS (API FETCHING)
## ALGORITHM
1. Wait for the DOM to fully load using the 'DOMContentLoaded' event.
2. Select the container element where posts will be displayed ('.posts-container').
3. Define the API endpoint URL for fetching posts.
4. Create an asynchronous function 'fetchPosts' to handle data retrieval.
5. Inside 'fetchPosts', send an HTTP GET request to the API endpoint.
6. Parse the JSON response to obtain the list of posts.
7. Clear any existing content or loading messages in the posts container.
8. For each post in the retrieved data:
    a. Call 'createPostElement' to generate a post card element.
    b. Append the generated post card to the posts container.
9. Define 'createPostElement' to:
    a. Create an article element with the post's title and body.
    b. Return the constructed article element.
10. Invoke 'fetchPosts' to start the process and display posts on the page.

<img width="1855" height="936" alt="image" src="https://github.com/user-attachments/assets/9a31cad2-4490-4605-bd6a-d5255628d211" />

## PROJECT – 22 : Country Explorer (HTML, CSS, JavaScript)

## Algorithm

1. **Start** by creating the basic HTML document structure.
2. **Design** the user interface using input fields, buttons, and a result display section.
3. **Style** the webpage using CSS to ensure a clean and responsive layout.
4. **Accept** the country name from the user through an input field.
5. **Trigger** a JavaScript function when the search button is clicked.
6. **Send** a request to the REST Countries API using the Fetch API.
7. **Receive** the country data in JSON format.
8. **Extract** important details such as country name, capital, population, region, and flag.
9. **Display** the extracted country information dynamically on the webpage.
10. **Handle** invalid inputs or API errors gracefully.
11. **End** the process after displaying the result.


## PROJECT – 23 : Movies Finder (HTML, CSS, JavaScript, API)

## Algorithm

1. **Start** by creating the HTML structure for the Movies Finder application.
2. **Add** an input field for movie search and a search button.
3. **Apply** CSS styling for better user interface and responsiveness.
4. **Wait** for the user to enter a movie name.
5. **Capture** the entered movie name using JavaScript.
6. **Send** an API request to the OMDb API using Fetch.
7. **Receive** the movie details in JSON format.
8. **Verify** whether the movie exists in the response.
9. **Extract** movie information such as title, poster, year, genre, and rating.
10. **Display** the movie details dynamically on the webpage.
11. **Show** an error message if the movie is not found.
12. **End** the process after displaying the output.


## PROJECT – 24 : Gemini AI Chat Application (HTML, CSS, JavaScript)

## Algorithm

1. **Start** by creating the HTML structure for the chat interface.
2. **Design** input fields for user messages and a chat display area.
3. **Style** the application using CSS for a clean chat experience.
4. **Accept** the user’s message through the input box.
5. **Trigger** a JavaScript function when the user sends a message.
6. **Send** the user prompt to the Gemini AI API.
7. **Receive** the AI-generated response from the API.
8. **Parse** the response data.
9. **Display** the AI response in the chat window.
10. **Append** user and AI messages sequentially to maintain conversation history.
11. **Handle** empty inputs and API errors properly.
12. **End** the process after displaying the response.
<img width="1354" height="589" alt="image" src="https://github.com/user-attachments/assets/6644c213-74e9-40b0-8b45-470516c41c44" />

## PROJECT - 25 : CURRENCY CONVERTOR USING API

## Algorithm
1. **Start** by creating the HTML structure for the currency converter interface.
2. **Design** input fields for the amount, currency dropdowns, and buttons for conversion and exchange rates.
3. **Style** the application using CSS for a clean and user-friendly experience.
4. **Accept** the user’s input for amount and selected currencies.
5. **Trigger** a JavaScript function when the user clicks the convert or get rates button.
6. **Send** a request to the ExchangeRate-API with the selected currencies and amount.
7. **Receive** the conversion rate or exchange rates from the API.
8. **Parse** the response data to extract relevant rates.
9. **Display** the converted amount or exchange rates in the result area.
10. **Handle** empty inputs and API errors gracefully, providing user feedback.

<img width="628" height="511" alt="image" src="https://github.com/user-attachments/assets/1d3fdb5d-fe14-4132-9fc3-2d0d23a81ca4" />

More projects will be added soon
